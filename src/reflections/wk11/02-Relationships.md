# C# Relationships between data

## What is the difference between a primary key and a foreign key

* Foreign keys are used to reference data on another table. Primary keys are pieces of unique information that are used to identify records on a table.

## What is an Alias?

* An alias is declared following the first instance of the written table name and can be used in place of writting out the full table name.

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

*  CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  DOCTORID NOT NULL AUTO INCREMET,
  PRIMARY KEY (id)
)

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)

* "SELECT * FROM patients WHERE p.doctorId = @doctorId;"

https://talanweeks.github.io/JobsnContractors/