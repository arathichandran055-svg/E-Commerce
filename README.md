# Week-1

E-Commerce Order Management Database System

 Project Overview

The E-Commerce Order Management Database System is designed to manage and streamline the operations of an online shopping platform. This system helps in handling customer data, product information, orders, payments, shipments, and reviews efficiently.

Objectives

* Automate order management processes
* Maintain accurate customer and product records
* Reduce manual errors
* Improve operational efficiency
* Enhance customer satisfaction

Business Scenario

A growing e-commerce company requires a centralized database system to manage its daily operations. The system supports customer registration, product management, order processing, payment tracking, shipment tracking, and customer feedback.


Core Entities

* Customer
* Category
* Product
* Supplier
* Order
* Order Details
* Payment
* Shipment
* Review

 Features

* Customer Registration and Login
* Product and Category Management
* Inventory Tracking
* Order Processing
* Payment Management
* Shipment Tracking
* Customer Reviews and Ratings

Stakeholders

Customer : Places orders and gives reviews
Admin : Manages system operations
Supplier : Provides products
Delivery Team : Handles shipments


 Documents Included

* Requirement Analysis Report
* Business Requirement Document (BRD)
* Software Requirement Specification (SRS)

Technologies Used

* Database: MySQL / Oracle
* Platform: Web-based system
* Tools: GitHub for version control

 Project Structure

Week1
│── Requirement_Analysis_Report.pdf  
│── Business_Requirement_Document.pdf  
│── SRS_Document.pdf  
│── README.md  

Assumptions

* Users have internet access
* Data entered is correct and valid

Constraints

* Fixed database entities
* Limited system resources
* No modification of predefined attributes

 Conclusion

This project provides a structured approach to designing a database system for e-commerce operations. It ensures efficient data management, improved accuracy, and better decision-making.


# Week-2

# Week 2 – Entity and Relationship Analysis

Project Title

E-Commerce Order Management Database System

Description

This repository contains the Entity Analysis and Entity Relationship Analysis for the E-Commerce Order Management Database System. The purpose of this phase is to identify all the data entities, define their attributes, and establish relationships between them based on the system requirements gathered in Week 1.

Objectives

* To identify all entities involved in the system
* To define attributes for each entity
* To assign Primary Keys (PK) and Foreign Keys (FK)
* To apply constraints such as NOT NULL, UNIQUE, CHECK, and DEFAULT
* To analyze relationships between entities
* To define cardinality (One-to-One, One-to-Many)

Entities Identified

* Customer
* Product
* Category
* Order
* Order_Item
* Payment
* Shipping
* Cart
* Cart_Item

Key Components

1. Entity Analysis

Includes identification of entities and their attributes along with constraints to ensure data integrity.

2. Key Identification

* Primary Keys uniquely identify each record
* Foreign Keys establish relationships between entities

3. Relationship Analysis

Defines how entities are connected, such as:

* Customer places Orders
* Orders contain Order_Items
* Products belong to Categories
* Orders are linked with Payment and Shipping

4. Cardinality

* One-to-One: Order–Payment, Order–Shipping, Customer–Cart
* One-to-Many: Customer–Order, Order–Order_Item, Product–Order_Item, Category–Product, Cart–Cart_Item

Files Included

* Entity_Analysis_Report.pdf
* Entity_Relationship_Analysis.pdf

Tools & Concepts Used

* Database Management System (DBMS)
* ER Modeling
* Normalization Concepts

Conclusion

This analysis provides a structured representation of the database design by clearly defining entities, attributes, and relationships. It ensures efficient data organization, minimizes redundancy, and supports scalable system development.



