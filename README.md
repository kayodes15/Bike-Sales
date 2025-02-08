# Bike-Sales
httfhtfhtrhjyjyhjytjytjytjyt
-- Samuel Aikulola
-- This is My SQL note with Ebuka

-- 1. Select Statement
select * from dbo.customers;
select * from [dbo].[Customers];

-- I only need customerid, companyname and contactname

select CustomerID, CompanyName, ContactName from dbo.customers;

-- Classwork
-- give me all the details of our employees
-- I need the ID, LastName, FirstName, date of birth and coutntry of 
-- all our staff- from employee table

-- 2. Top Function
select top 10 * from dbo.customers;

-- classwork
-- give me top 5 out of the employees table

-- 3 Alias
select CustomerID as ID, CompanyName as Organization, ContactName as "full name"
from dbo.customers;

select CustomerID ID, CompanyName Organization, ContactName "full name"
from dbo.customers;

--  Class work
-- I need the employeeID and Lastname but change the column names to
-- Staff ID and Father's Name from the employees table

