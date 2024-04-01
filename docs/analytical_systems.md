# Analytical Systems

**Transactional systems** are database that record a company's detailed transactions.

**Analytical systems** are read-only systems that store historical data and are specifically designed to support Business Intellingence (BI) and analytical applications, tipically as part of a Data Warehouse.

**Data Warehouse** is a type of data management system that will enable and support your BI activities/needs. 

Analytical systems uses **dimensional modeling** to design your data warehouse. 

A dimensional model contains **dimensions** and **facts**. 

## Dimensions

Dimensions provide the *who*, *what*, *where*, *when*, *why*, and how context surrounding the business process event. 

**Hierarchies** are logical structures that use ordered levels as a means of organizing data. A hierarchy can be used to define **data aggregation**.

*Example: in a time dimension, a hierarchy might aggregate data from the month level to the quarter level to the year level.*

## Facts

Facts are the result of a business process event, which are mostly numeric.

Facts contais attributes (measures) which have an aggregaton defined of the fact column.


