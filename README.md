# Cyclistic Case Study

Course: [Google Business Intelligence Certificate](https://www.coursera.org/professional-certificates/google-business-intelligence)

## Background

In this case study, I will perform many real-world tasks of a data analyst at a fictional company, Cyclistic. Cyclistic is a fictional bike-share company based in New York City, NY. Currently, there are bike stations located throughout Manhattan and neighboring boroughs. Customers are able to rent bikes for easy travel between stations at these locations.

## The Problem

Cyclistic's Customer Growth Team is creating a business plan for next year. The team wants to understand how their customers are using their bikes: their top priority is identifying customer demand at different station locations.

## Project Goals:

- To understand how their customers are using their bikes
- Top priority is identifying customer demand at different station locations
- Understand what customers want, what makes a successful product, how new stations might alleviate demand in different geographical areas.
- Understand how current line of bikes are used
- How can we apply customer usage insights to inform new station growth?
- How different users (subscribers and non-subscribers) use bikes.

These insights will be used to help support the growth of Cyclistic.

## Project Planning

In order to ensure that we stay on task with the big-picture and small details, project planning will be broken down into three phases with accompanying documents:

### The Stakeholder Requirements Document

The [Stakeholder Requirements Document](https://docs.google.com/document/d/19JuVN5qY5vfJJYMBdPMETev7EW8IdGakcjcSU1Oi5Ys/edit?tab=t.00) enables me to capture stakeholder requests and requirements to better understand their needs before planning the rest of the project details or strategy.

### The Project Requirements 

The [Project Requirements Document](https://docs.google.com/document/d/1zDnNjGHbwMNVZcvShWyiMs_jj1f1WG7FsRnvooGfRuE/edit?usp=sharing) helps brainstorm what is needed to achieve the stakeholder requirements.

### The Strategy Document

The strategy document helps to align with stakeholders about project deliverables. This includes what visualization functionalities, metrics and charts are used.

## Data Processing

Two public datasets have been provided on BigQuery:
- [NYC Citi Bike Trips](https://console.cloud.google.com/marketplace/details/city-of-new-york/nyc-citi-bike?project=eco-notch-431817-a3)
- [Census Bureau US Boundaries](https://console.cloud.google.com/marketplace/product/united-states-census-bureau/us-geographic-boundaries?project=eco-notch-431817-a3)
- [GSOD from the National Oceanic and Atmospheric Administration](https://console.cloud.google.com/marketplace/details/noaa-public/gsod?project=eco-notch-431817-a3)
- [Zip Codes Excel Sheet](https://docs.google.com/spreadsheets/d/1IIbH-GM3tdmM5tl56PHhqI7xxCzqaBCU0ylItxk_sy0/template/preview#gid=806359255)

To ensure data maturity, we will need to create a pipeline using ETL (Extract, Transform, and Load). This will gather the data from both source systems, covert them into a useful format, and load it into a centralized data warehouse.
