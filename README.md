-- Create the database
CREATE DATABASE IF NOT EXISTS TUTORIALSPOINT;

-- Use the database
USE TUTORIALSPOINT;

-- Create the table
CREATE TABLE IF NOT EXISTS Registration (
    ID INT NOT NULL,
    FirstName VARCHAR(255),
    LastName VARCHAR(255),
    Age INT,
    PRIMARY KEY (ID)
);
