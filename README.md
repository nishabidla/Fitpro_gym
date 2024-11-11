# FitPro Gym SQL Analysis Project

<p align="center">
  <img src="https://github.com/nishabidla/Fitpro_gym/blob/main/fitpro%20gym.jpg" alt="FitPro Gym Banner">
</p>

Hello and thank you for visiting my project repository! I'm Nisha, a data enthusiast with a passion for uncovering insights through data analysis. This project is a deep dive into the dataset from FitPro Gym, encompassing over 10,000 records of gym visits. Here, I apply SQL techniques to extract, analyze, and interpret data to help FitPro Gym better understand its client base and optimize its service offerings.

## Table of Contents
- [**Introduction**](#introduction)
- [**Project Overview**](#project-overview)
- [**Database Schema**](#database-schema)
- [**Key Questions Addressed**](#key-questions-addressed)
- [**SQL Queries & Insights**](#sql-queries--insights)
- [**Setup Guide**](#setup-guide)
- [**Connect**](#connect)

## Introduction

This project is designed to showcase essential SQL skills through the analysis of a comprehensive dataset from FitPro Gym. By utilizing SQL, I have examined various aspects of gym operations, including membership details, demographic information, and visitation patterns. The aim is to derive actionable insights that can enhance decision-making and improve gym management practices. Throughout this project, I demonstrate core SQL techniques such as creating tables, writing complex queries, and performing detailed data analysis, all aimed at uncovering trends and patterns that are critical to the gym’s success.


## Project Overview
**Project Structure:**

- **SQL Scripts**: This folder contains all SQL scripts, including schema definitions and queries.
- **Data**: A sample dataset that simulates the gym's operational data.
- **Documentation**: Detailed explanations of the queries and their outcomes.

**Files Description:**

- `schema.sql`: Sets up the database schema.
- `analysis.sql`: SQL queries crafted to analyze the gym's data thoroughly.

## Database Schema

The database is designed to hold detailed records of gym operations and is structured as follows:

- **Members Table**
  - `member_id`: Unique identifier for each member.
  - `name`: Member's name.

- **Memberships Table**
  
  - `membership_id`: Unique identifier for each membership.
  - `member_id`: Linked to Members.
  - `type`: Membership type (e.g., Monthly, Quarterly).
  - `start_date`: Membership start date.
  - `status`: Current status (Active, Cancelled).

- **Visits Table**

  - `visit_id`: Unique identifier for each visit.
  - `member_id`: Linked to Members.
  - `date`: Date of visit.

## Key Questions Addressed

The following queries were created to solve specific business questions. Each query is designed to provide insights based on gym membership and visit data.

1. Retrieve the **name** and **membership_type** of female members.
2. Find members who have a **Monthly membership** and joined after **2023-11-01**.
3. List the **name** and **status** of active members over **25**.
4. Get details of **visits** on a specific date (**2024-01-01**).
5. List members with a **Quarterly membership** aged between **20 and 30**.

Additional aggregations and grouping:
6. Count total visits made by each member.
7. Count members by membership type (e.g., Monthly, Weekly, Quarterly).
8. Calculate the average age of members, grouped by membership type.
9. Total visits for each visit date.
10. Count members by status (e.g., Active or Cancelled).

Advanced queries:
11. Top 3 members with the highest visits.
12. Active Monthly members grouped by membership type, sorted by recent join dates.
13. Members with more than 2 visits, sorted by total visits, displaying the top 5.
14. Members who joined in 2023, grouped by membership type (where each group has >1 member).
15. Average age of active members, grouped by membership type, limited to the top 3 results.

## SQL Queries & Insights

The `analysis.sql` file houses all SQL scripts used to interrogate the dataset. Each script is accompanied by comments explaining the purpose of the query and the insights derived from the results.

## Setup Guide
**Prerequisites:**

- PostgreSQL (or any SQL-compatible database)
- Basic understanding of SQL

**How to Get Started:**

1. Clone this repository:

   ```bash

   git clone https://github.com/nishabidla/Fitpro_gym.git

   ```

2. Set up your database using `schema.sql`.

3. Load the sample data.

4. Begin executing the queries within `analysis.sql` to explore the data.


## Connect

I'm always looking for feedback and opportunities to improve! If you have questions, suggestions, or just want to connect, please reach out to me at:

- **Email**: [nishabidla0817@gmail.com](mailto:nishabidlabidla0817@gmail.com)

- **LinkedIn**: [LinkedIn Profile]([https://linkedin.com/in/yourusername](https://www.linkedin.com/in/nisha-kumari-bidla-850255146/))

Thank you for exploring my FitPro Gym SQL Analysis Project!
