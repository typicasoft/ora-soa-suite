1- Configure the Data Source at you SOA server level

2- Create the following DB objects

--------------------------------------------------------
--  DDL for table xxasf_sample_record1 
--------------------------------------------------------
drop table xxasf_sample_record1;
/

create table xxasf_sample_record1 (
C_pk VARCHAR2(50), 
C2 VARCHAR2(50), 
C3 VARCHAR2(50), 
C4 VARCHAR2(50), 
C5 VARCHAR2(50), 
C6 VARCHAR2(50), 
C7 VARCHAR2(50), 
C8 VARCHAR2(50), 
C9 VARCHAR2(50));
/





--------------------------------------------------------
--  DDL for table xxasf_sample_record2
--------------------------------------------------------
drop table xxasf_sample_record2;
/

create table xxasf_sample_record2 (
C_fk VARCHAR2(50),
C2 VARCHAR2(50), 
C3 VARCHAR2(50), 
C4 VARCHAR2(50), 
C5 VARCHAR2(50), 
C6 VARCHAR2(50), 
C7 VARCHAR2(50), 
C8 VARCHAR2(50), 
C9 VARCHAR2(50),
C10 VARCHAR2(50)
);
/

--------------------------------------------------------
--  DDL for Sequence XXASF_SAMPLE_REC1_SEQ
--------------------------------------------------------

CREATE SEQUENCE  "APPS"."XXASF_SAMPLE_REC1_SEQ"  MINVALUE 1 MAXVALUE 9999999999999999999999999999 INCREMENT BY 50 START WITH 1050 CACHE 20 NOORDER  NOCYCLE ;
/

