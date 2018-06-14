# Make a SQL Database

echo “Creating a Database named “Mysql_Clingen”
mysql -trgndata516 -p -e ‘CREATE DATABASE Mysql_Clingen’

# Creating a Database “Mysql_Clingen”

CREATE DATABASE Mysql_Clingen; 

# Selecting Database in MySQL

USE Mysql_Clingen;

# Make a table and define variables

mysql> CREATE TABLE px1_Clingen
    -> (px VARCHAR(30),
    -> gender VARCHAR(30),
    -> race VARCHAR(30),
    -> vital_status VARCHAR(30),
    -> days_to_last_followup INT,
    -> age_at_diagnosis INT,
    -> pathologic_T VARCHAR(30),
    -> pathologic_N VARCHAR(30),
    -> pathologic_M VARCHAR(30),
    -> pathologic_stage VARCHAR(30),
    -> surgical_procedure_first VARCHAR(30),
    -> drug_name_1 VARCHAR(30),
    -> drug_name_2 VARCHAR(30),
    -> drug_name_3 VARCHAR(30),
    -> drug_name_4 VARCHAR(30),
    -> drug_name_5 VARCHAR(30),
    -> radiation_type_1 VARCHAR(30),
    -> anatomic_treatment_site_1 VARCHAR(30),
    -> Pathogenic_Chr_Pos_1 VARCHAR(30),
    -> Pathogenic_Chr_Pos_2 VARCHAR(30),
    -> Pathogenic_Chr_Pos_3 VARCHAR(30),
    -> Pathogenic_Chr_Pos_4 VARCHAR(30),
    -> Pathogenic_Chr_Pos_5 VARCHAR(30),
    -> Pathogenic_Chr_Pos_6 VARCHAR(30),
    -> Pathogenic_Chr_Pos_7 VARCHAR(30),
    -> Pathogenic_Chr_Pos_8 VARCHAR(30),
    -> Pathogenic_Chr_Pos_9 VARCHAR(30),
    -> Pathogenic_Chr_Pos_10 VARCHAR(30),
    -> Pathogenic_Chr_Pos_11 VARCHAR(30),
    -> Pathogenic_Chr_Pos_12 VARCHAR(30),
    -> Pathogenic_Chr_Pos_13 VARCHAR(30),
    -> Pathogenic_Chr_Pos_14 VARCHAR(30),
    -> Pathogenic_Chr_Pos_15 VARCHAR(30),
    -> Pathogenic_Chr_Pos_16 VARCHAR(30),
    -> Pathogenic_Chr_Pos_17 VARCHAR(30),
    -> Pathogenic_Chr_Pos_18 VARCHAR(30),
    -> Exon_1_RPKM_1 VARCHAR(30),
    -> Exon_2_RPKM_2 VARCHAR(30),
    -> Exon_3_RPKM_3 VARCHAR(30),
    -> Exon_4_RPKM_4 VARCHAR(30),
    -> Exon_5_RPKM_5 VARCHAR(30),
    -> Exon_6_RPKM_6 VARCHAR(30),
    -> Exon_7_RPKM_7 VARCHAR(30),
    -> Exon_8_RPKM_8 VARCHAR(30),
    -> Exon_9_RPKM_9 VARCHAR(30),
    -> Exon_10_RPKM_10 VARCHAR(30),
    -> Exon_11_RPKM_11 VARCHAR(30),
    -> Exon_12_RPKM_12 VARCHAR(30),
    -> Exon_13_RPKM_13 VARCHAR(30),
    -> Exon_14_RPKM_14 VARCHAR(30),
    -> Exon_15_RPKM_15 VARCHAR(30),
    -> Exon_16_RPKM_16 VARCHAR(30),
    -> Exon_17_RPKM_17 VARCHAR(30),
    -> Exon_18_RPKM_18 VARCHAR(30));
# Populating the table

INSERT INTO px1_Clingen 
VALUES ('px1', 'FEMALE', 'WHITE', 'Alive', '852', '67', 'T2', 'N1’, 'M0', 'StageIIB', 'ModifiedRadicalMastectomy', 'NotAvailable’, 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'EXTERNALBEAM’, 'RegionalSite', '13_32890572', '13_32906729', '13_32915411’, '13_32915412', '13_32915413', '13_32915414', '13_32929387’, '13_32953388', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null’, 'Null', 'Null', 'Null', '13_32890572', 'Null', 'Null', 'Null', 'Null’, '13_32915414', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null’, 'Null', 'Null', 'Null', 'Null', 'Null'); 

INSERT INTO px1_Clingen 
VALUES ('px2', 'FEMALE', 'WHITE', 'Alive', '3153', '66', 'T1c', 'N0i-’, 'M0', 'StageIA', 'Lumpectomy', 'Arimidex', 'Cytoxan', 'Adriamycin’, 'Null', 'Null', 'Null', 'Null', 'Null', 'EXTERNALBEAM’, 'PrimaryTumorField', '13_32903685', '13_32906729’, '13_32910430', '13_32929387', '13_32936646', '13_32953388’, 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null’, 'Null', 'Null', 'Null', '13_32906729', '13_32910430’, '13_32929387', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null’, 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null'); 

INSERT INTO px1_Clingen 
VALUES ('px3', 'FEMALE', 'BLACKORAFRICANAMERICAN', 'Alive’, '2365', '36', 'T1', 'N0i-', 'M0', 'StageIA', 'Lumpectomy’, 'Anastrozole', 'Tamoxifen', 'Adriamycin', 'Cytoxan', 'Taxol', 'Null’, 'Null', 'Null', 'EXTERNALBEAM', 'PrimaryTumorField’, '13_32906729', '13_32912299', '13_32929387', '13_32968743’, '13_32972884', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null’, 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', '13_32906729’, '13_32912299', '13_32929387', 'Null', '13_32972884', 'Null’, 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null’, 'Null', 'Null'); 

INSERT INTO px1_Clingen 
VALUES ('px4', 'FEMALE', 'WHITE', 'Alive', '764', '53', 'T2', 'N1mi’, 'M0', 'StageIIB', 'SimpleMastectomy', 'Zometa', 'Tamoxifen’, 'Herceptin', 'Taxol', 'Adriamycin', 'Cytoxan', 'Null', 'Null’, 'EXTERNALBEAM', 'PrimaryTumorField', '13_32890572’, '13_32903685', '13_32911888', '13_32915411', '13_32915412’, '13_32915413', '13_32915414', '13_32929232', '13_32929387’, '13_32936646', '13_32953388', 'Null', 'Null', 'Null', 'Null', 'Null’, 'Null', 'Null', '13_32890572', 'Null', '13_32911888', 'Null', 'Null’, 'Null', 'Null', '13_32929232', '13_32929387', 'Null', 'Null', 'Null’, 'Null', 'Null', 'Null', 'Null', 'Null', 'Null'); 

INSERT INTO px1_Clingen 
VALUES ('px5', 'FEMALE', 'BLACKORAFRICANAMERICAN', 'Alive’, '1827', '37', 'T3', 'N2a', 'M0', 'StageIIIA’, 'ModifiedRadicalMastectomy', 'Zometa', 'Arimidex', 'Tamoxifen’, 'Adriamycin', 'Cytoxan', 'Taxol', 'Null', 'Null', 'EXTERNALBEAM’, 'PrimaryTumorField', '13_32912299', '13_32929387’, '13_32931887', '13_32968743', '13_32972884', 'Null', 'Null’, 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null’, 'Null', '13_32912299', '13_32929387', '13_32931887', 'Null’, '13_32972884', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null', 'Null’, 'Null', 'Null', 'Null', 'Null', 'Null', 'Null'); 

# Selecting all components of a table

SELECT * FROM px1_Clingen;

# Querying SQL database

SELECT px FROM px1_Clingen WHERE drug_name_1='Taxol' OR drug_name_2='Taxol' OR  drug_name_3='Taxol' OR drug_name_4='Taxol' OR drug_name_5='Taxol' OR drug_name_6='Taxol' OR drug_name_7='Taxol' OR drug_name_8='Taxol' AND Pathogenic_Chr_Pos_1='13_32972884';

SELECT px FROM px1_Clingen WHERE race='BLACKORAFRICANAMERICAN' AND drug_name_1='Tamoxifen' OR drug_name_2='Tamoxifen' OR  drug_name_3='Tamoxifen' OR drug_name_4='Tamoxifen' OR drug_name_5='Tamoxifen' OR drug_name_6='Tamoxifen' OR drug_name_7='Tamoxifen' OR drug_name_8='Tamoxifen' AND Exon_6_RPKM_6='13_32972884';

# Joining two tables in a database 

 SELECT * FROM px1_Clingen
    -> LEFT JOIN Mitali ON px1_Clingen.px=Mitali.px
    -> UNION ALL
    -> SELECT * FROM px1_Clingen
    -> RIGHT JOIN Mitali ON px1_Clingen.px=Mitali.px;

# Union of two tables

SELECT px,gender,race,vital_status,days_to_last_followup,age_at_diagnosis,pathologic_T,pathologic_N,pathologic_M,pathologic_stage,surgical_procedure_first,drug_name_1,drug_name_2,drug_name_3,drug_name_4,drug_name_5,drug_name_6,drug_name_7,drug_name_8,radiation_type_1,anatomic_treatment_site_1,Pathogenic_Chr_Pos_1,Pathogenic_Chr_Pos_2,Pathogenic_Chr_Pos_3,Pathogenic_Chr_Pos_4,Pathogenic_Chr_Pos_5,Pathogenic_Chr_Pos_6,Pathogenic_Chr_Pos_7,Pathogenic_Chr_Pos_8,Pathogenic_Chr_Pos_9,Pathogenic_Chr_Pos_10,Pathogenic_Chr_Pos_11,Pathogenic_Chr_Pos_12,Pathogenic_Chr_Pos_13,Pathogenic_Chr_Pos_14,Pathogenic_Chr_Pos_15,Pathogenic_Chr_Pos_16,Pathogenic_Chr_Pos_17,Pathogenic_Chr_Pos_18,Exon_1_RPKM_1,Exon_2_RPKM_2,Exon_3_RPKM_3,Exon_4_RPKM_4,Exon_5_RPKM_5,Exon_6_RPKM_6,Exon_7_RPKM_7,Exon_8_RPKM_8,Exon_9_RPKM_9,Exon_10_RPKM_10,Exon_11_RPKM_11,Exon_12_RPKM_12,Exon_13_RPKM_13,Exon_14_RPKM_14,Exon_15_RPKM_15,Exon_16_RPKM_16,Exon_17_RPKM_17,Exon_18_RPKM_18 FROM px1_Clingen
    -> UNION                                                                                                                                                                                              -> SELECT px,gender,race,vital_status,days_to_last_followup,age_at_diagnosis,pathologic_T,pathologic_N,pathologic_M,pathologic_stage,surgical_procedure_first,drug_name_1,drug_name_2,drug_name_3,drug_name_4,drug_name_5,drug_name_6,drug_name_7,drug_name_8,radiation_type_1,anatomic_treatment_site_1,Pathogenic_Chr_Pos_1,Pathogenic_Chr_Pos_2,Pathogenic_Chr_Pos_3,Pathogenic_Chr_Pos_4,Pathogenic_Chr_Pos_5,Pathogenic_Chr_Pos_6,Pathogenic_Chr_Pos_7,Pathogenic_Chr_Pos_8,Pathogenic_Chr_Pos_9,Pathogenic_Chr_Pos_10,Pathogenic_Chr_Pos_11,Pathogenic_Chr_Pos_12,Pathogenic_Chr_Pos_13,Pathogenic_Chr_Pos_14,Pathogenic_Chr_Pos_15,Pathogenic_Chr_Pos_16,Pathogenic_Chr_Pos_17,Pathogenic_Chr_Pos_18,Exon_1_RPKM_1,Exon_2_RPKM_2,Exon_3_RPKM_3,Exon_4_RPKM_4,Exon_5_RPKM_5,Exon_6_RPKM_6,Exon_7_RPKM_7,Exon_8_RPKM_8,Exon_9_RPKM_9,Exon_10_RPKM_10,Exon_11_RPKM_11,Exon_12_RPKM_12,Exon_13_RPKM_13,Exon_14_RPKM_14,Exon_15_RPKM_15,Exon_16_RPKM_16,Exon_17_RPKM_17,Exon_18_RPKM_18 FROM Mitali;

