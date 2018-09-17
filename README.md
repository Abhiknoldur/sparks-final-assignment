# sparks-final-assignment

##Apache Spark
##Final Assignment



##Aim​ :
Complete all the questions given below using Spark Shell or creating an SBT application using
Spark dependencies.
Description of Data​ :


Power plant has a lot of machines. Each machine has a thermostat attached to it. Each thermostat
emits temperature (in o​ ​ C) information along with the timestamp of the temperature recorded.
Eg​ :
Timestamp, Temperature
2010-03-08T17:19:59.000Z, 84.96
2010-03-08T17:20:00.000Z, 88.41
...
...
Note​ : The data will be provided with email.
Aim​ :
We need to save data in Parquet file format with following requirements:
1. Saved data should be indexed.
2. Saved data can be retrieved by specific date or time period (span) efficiently (i.e., by
index).
Form of Submission​​ :
Assignment can be submitted in 2 ways
1. By Creating a SBT application containing answers and code for the above questions.
2. Or, by giving answers and code snippets for above questions, if you are using Spark
Shell.
Note​​ : All submissions should be done by sharing answers and code via GitHub. You can create
a public repository on your GitHub account, push your answers to it and provide its link for
submission. The last date for submission is 18 September 2018, 10:00 AM. A Form will be sent
via which the answers can be submitted.



Run following commands to execute this repo :-

1.git clone https://github.com/Abhiknoldur/sparks-final-assignment.git
2.cd sparks-final-assignment/
3.sbt clean compile run
