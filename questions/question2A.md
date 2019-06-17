## Question
There is a parent organization called "ABC Group Inc", which has two child companies named Tech Inc and MPTech. Both companies employee information is given in two separate text file as below. Please do the following activity for employee details.

- Which command will you use to check all the available command line options on HDFS and How will you get the Help for individual command.
- Create a new Empty Directory named Employee using Command line. And also create an empty file named in it Techinc.txt
- Load both companies Employee data in Employee directory (How to override existing file in HDFS).
- Merge both the Employees data in a Single tile called MergedEmployee.txt, merged tiles should have new line character a t the end of each file content.
- Upload merged file on HDFS and change the file permission on HDFS merged file, so that owner and group member can read and write, other user can read the file.
- Write a command to export the individual file as well as entire directory from HDFS to local file System.

## Answer

hdfs --help
hdfs dfs -mkdir Employee
hdfs dfs -touchz Employee/Techinc.txt



