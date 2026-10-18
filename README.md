
# Grazioso Salvare Rescue Animal Dashboard

**CS 499: Computer Science Capstone — Database Enhancement**

Michael Rodman | Southern New Hampshire University | October 2026

## Project Overview

The Grazioso Salvare Rescue Animal Dashboard is a Python-based application originally developed in CS 340: Client/Server Development. It connects to MongoDB and allows users to filter animal shelter records based on search-and-rescue profiles.

The dashboard uses interactive tables, breed visualizations, and geolocation information to support the identification of potential rescue animals.

For CS 499, I enhanced the database implementation to improve security, efficiency, reliability, and maintainability.

## Original Artifact

The [original artifact](original/) includes the CS 340 dashboard, CRUD Python module, logo, and project documentation.

Credentials were removed from the publicly shared version to protect sensitive information.

## Enhanced Artifact

The [enhanced artifact](enhanced/) demonstrates:

- Environment-based MongoDB configuration
- Compound indexing for frequently used queries
- MongoDB aggregation pipelines for breed summaries
- Improved database input validation
- Protection against unrestricted update and delete operations
- Safer database error handling
- Automated unit and regression testing

The enhancement includes 12 automated tests, all of which passed during milestone testing.

## Technical Files

- [Original Dashboard](original/ProjectTwoDashboard.ipynb)
- [Original CRUD Module](original/CRUD_Python_Module.py)
- [Enhanced Dashboard](enhanced/ProjectTwoDashboard.ipynb)
- [Enhanced CRUD Module](enhanced/CRUD_Python_Module.py)
- [Automated Test Suite](enhanced/test_database_enhancement.py)
- [Environment Configuration Template](enhanced/.env.example)

## Enhancement Narrative

[Read the CS 499 Milestone Four Narrative](enhanced/CS499_Module5_Milestone4_Michael_Rodman.docx)

The narrative describes the enhancements, technical decisions, challenges, lessons learned, and alignment with the Computer Science program outcomes.

## Course Outcomes

This enhancement primarily demonstrates:

**Course Outcome Four:** Using computing techniques, skills, and tools to implement solutions that deliver value.

**Course Outcome Five:** Applying a security mindset to identify vulnerabilities, mitigate design flaws, and protect data.

It also supports professional technical communication through documentation, testing, and reflection.

## Security and Configuration

Database credentials are not included in the published source code. Environment variables are required to establish a MongoDB connection.

The enhanced artifact includes a configuration template and Git ignore rules to support safer local development.

## Portfolio

This repository supports my CS 499 professional ePortfolio and demonstrates my growth in database development, software security, testing, and maintainable application design.
