# Question

source: <http://cca175cloudera.training4exam.com/module-9>

Problem Scenario 9 : You already have two tables (Hive) name "SAMPLE_07" and "SAMPLE_08" in a default schema. With following structure (both the tables have same structure).

code string
description string
total_emp int
salary int

Create another table named Employee100K2 in a Family schema, which has all the employees whose salary is >= 100000 from both the tables.

Create required Hive table as below.

CREATE TABLE SAMPLE_08
(code string ,
description string ,
total_emp int ,
salary int
);

INSERT INTO SAMPLE_08 VALUES ('20-0000','All Occupations' ,134354250,40690);
INSERT INTO SAMPLE_08 VALUES ('11-0000','Management occupations' ,6003930,96150);
INSERT INTO SAMPLE_08 VALUES ('22-0000','All Occupations' ,134354250,140690);
INSERT INTO SAMPLE_08 VALUES ('22-1000','Management occupations' ,6003930,99150);
INSERT INTO SAMPLE_08 VALUES ('23-0000','All Occupations' ,134354250,140690);
INSERT INTO SAMPLE_08 VALUES ('23-1000','Management occupations' ,6003930,101150);

## Answer
