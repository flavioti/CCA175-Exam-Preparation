# Question

source: <http://cca175cloudera.training4exam.com/module-8>

Problem Scenario 8 : You already have a table name "SAMPLE_07" in a default schema. With following structure.


code string
description string
total_emp int
salary int

Sample data as below.

sample_07.code sample_07.description sample_07.total_emp sample_07.salary
00-0000 All Occupations 134354250 40690
11-0000 Management occupations 6003930 96150


Create Hive table and data as below.

CREATE TABLE SAMPLE_07
(code string ,
description string ,
total_emp int ,
salary int
);

INSERT INTO SAMPLE_07 VALUES ('00-0000','All Occupations' ,134354250,40690);
INSERT INTO SAMPLE_07 VALUES ('11-0000','Management occupations' ,6003930,96150);
INSERT INTO SAMPLE_07 VALUES ('02-0000','All Occupations' ,134354250,140690);
INSERT INTO SAMPLE_07 VALUES ('12-0000','Management occupations' ,6003930,99150);
INSERT INTO SAMPLE_07 VALUES ('03-0000','All Occupations' ,134354250,140690);
INSERT INTO SAMPLE_07 VALUES ('13-0000','Management occupations' ,6003930,101150);

## Answer
