# make a database

use Mongo_clingen

# Make a collection in database

i = { name : "px_1" } 
db.px_1.insert(i)

# Importing data (JSON files) from server to MongoDB

mongoimport --host 127.0.0.1:27017 --collection px_1 --db Mongo_clingen -- file=/Users/Mitali/Desktop/ px1M.json

# Querying the database

db.px_1.count( { "gender" : "FEMALE", "race" : "WHITE", "vital_status" : "Alive"})

# greater than function

db.px_1.count({"days_to_last_followup" : {$gte : 900}})

# $in function: any patient who was diagnosed with T1,T1a,T1b or T1c tumor:

db.px_1.count({"pathologic_T" : {"$in" : ["T1", "T1a", "T1b", "T1c"]}})

# Querying for white female who are aged 55 or over and have had the days to last followup greater than 900 

db.px_1.count( { "gender" : "FEMALE", "race" : "WHITE", "vital_status" : "Alive", "age_at_diagnosis" : {"$gte" : 55}, "days_to_last_followup" : {"$gte" : 900}})

# Querying for white female at or over the age of 55, whose days to last followup has been over 900 and the ones who have been treated with the following medications

db.px_1.find( { "gender" : "FEMALE", "race" : "WHITE", "vital_status" : "Alive", "age_at_diagnosis" : {"$gte" : 55}, "days_to_last_followup" : {"$gte" : 900}, "drug_name_1" : {"$in" : ["Tamoxifen", "Doxorubicin", "Epirubicin", "Paclitaxel", "Docetaxel", "Cyclophosphamide", "Taxotere", "taxol", "Carboplatin", "Fluorouracil"]}})
