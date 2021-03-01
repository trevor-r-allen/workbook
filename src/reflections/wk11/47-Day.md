# Day 47
__02/23/2020__

## Thoughts on Dotnet WebAPI Relationships

### What is the difference between a primary key and a foreign key?
Primary key values must be unique and can't be null.  Foreign keys are references to the primary key of another table.

### What is an Alias?
An alias is a declared shorthand or alternate name for a table. They can also be used to rename columns when joining tables with duplicated column names.

### Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:
    CREATE TABLE doctors (
    id INT NOT NULL   AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
    )
  
    CREATE TABLE patients (
    id INT NOT NULL   AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
    )
  
    CREATE TABLE doctors (
    id INT NOT NULL   AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,
  
    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients (id),
    )
  Answer:
    SELECT dp.*, d.*, p.*, 
    FROM doctorpatients dp
    JOIN patients p ON p.id = dp.patientId
    JOIN doctors d ON d.id = dp.doctorId;

#### Afternoon Lab: [C# Contractors](https://github.com/trevor-r-allen/csharp-contractors)