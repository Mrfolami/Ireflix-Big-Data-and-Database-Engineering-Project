Ireflix – Big Data & Database Engineering Project
This repository contains the Big Data Analytical Methods.
The project focuses on designing a scalable database system for a Netflix‑style platform called Ireflix, along with Big Data concepts and MapReduce processing.

Project Overview
Ireflix is a streaming platform concept where users can watch movies and series.
This project implements:

A fully designed SQL relational database

Synthetic data generation (1000+ records)

Big Data analysis and scaling concepts

Python MapReduce implementation

Additional analytical SQL queries

The goal is to demonstrate practical skills in data modelling, large‑scale data handling, and distributed processing.

Database Design
The database includes the following core tables:

Users

Movies

Series

Actors

Directors

User Activity (Movies & Series)

Features implemented:

Appropriate field lengths and constraints

Primary & Foreign Key relationships

Added year fields for movies and series

Logical enhancements to improve data integrity

Synthetic Data Generation
Python was used to generate 1000+ realistic synthetic records, ensuring:

Consistent relationships

Valid genres, names, durations, and ratings

Meaningful links between users, movies, and series

All scripts are included in the repository.

SQL Queries Included
The project contains:

Actor appearance analysis

Actors who appear in movies but not series

Three additional queries using WHERE, GROUP BY, and HAVING

Year‑based filtering and aggregation

Big Data Concepts
The written section covers:

Definition of Big Data

The 3 Vs (Volume, Velocity, Variety)

Scaling challenges for a platform with 50M+ users

Vertical vs horizontal scaling

Case studies of three real‑world organisations using Big Data tools

MapReduce (Python)
A Python‑based MapReduce implementation processes Ireflix viewing logs:

Mapper function

Reducer function

Main driver

Output screenshot

Insight on most‑watched genre

Technologies Used
MySQL 

Python

Pandas / Faker

MapReduce (Python implementation)

