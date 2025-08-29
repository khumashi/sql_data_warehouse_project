/*
====================================================
Create Database and Schemas
====================================================

Script Purpose:
This script creates a new database named 'DataWarehouse' after checking if it already exists.
If the database exists, it is dropped and recreated. Additionally, the script sets up three schemas
within the database: 'bronze', 'silver', and 'gold'.

WARNING:
Running this script will drop the entire 'DataWarehouse' database if it exists.
All data in the database will be permanently deleted. Proceed with caution
and ensure you have proper backups before running this script.
*/



-- Drop DataWarehouse if it already exists
DROP DATABASE IF EXISTS DataWarehouse;

-- Create the DataWarehouse database
CREATE DATABASE DataWarehouse;

-- Switch to DataWarehouse
USE DataWarehouse;

-- MySQL does not support schemas inside a database like SQL Server.
-- In MySQL, SCHEMA = DATABASE.
-- So here we will just create schemas (databases) named bronze and silver.

CREATE DATABASE IF NOT EXISTS bronze;
CREATE DATABASE IF NOT EXISTS silver;
CREATE DATABASE IF NOT EXISTS gold;
