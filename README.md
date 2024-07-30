# S3 Bucket Website Hosting with Amazon QuickSight

## Introduction
**Vincent Mostert**  

## Project Overview
**Title**: S3 Bucket Website Hosting with Amazon QuickSight

**Description**: 

This project demonstrates how to host a static website using Amazon S3 and visualize data using Amazon QuickSight. The project involved creating an S3 bucket, uploading website content, configuring static website hosting, and using QuickSight for data analysis and visualization.

## What is Amazon QuickSight?
Amazon QuickSight is a cloud-based business intelligence service that allows users to create interactive dashboards, perform ad-hoc analysis, and derive business insights from their data. It is designed to be fast, easy to use, and scalable, making it a powerful tool for data visualization and analysis.

## How I Used Amazon QuickSight in This Project
I performed an analysis on a Netflix dataset using Amazon QuickSight. The process took under an hour and resulted in seven visuals that effectively told a comprehensive story about the data.

## One Thing I Didn't Expect in This Project
I was pleasantly surprised by how fast and easy to use Amazon QuickSight is. The intuitive interface and powerful features made the data analysis process smooth and efficient.

## Project Duration
This project took under an hour to complete.

## Upload Project Files into S3
S3 was used in this project to store two files: a CSV file (`netflix_titles.csv`) and a JSON file (`manifest.json`). I edited the `manifest.json` file to include my S3 URI, which is crucial for locating the personal Netflix CSV in my bucket.

## Create QuickSight Account
Creating a QuickSight account is free if you use the trial version. The account creation process took me about 5 minutes.

## Download the Dataset
I connected the S3 bucket to QuickSight by visiting the QuickSight page and connecting it through the S3 URI. The `manifest.json` file was important in this step as it describes the structure and organization of the data.

## My First Visualization
To create visualizations on QuickSight, I selected the field `release_year` and dropped it into the visual. QuickSight automatically placed it on the appropriate axis. The resulting chart/graph showed a breakdown of the types of entertainment per release year, distinguishing between movies and TV shows.

## Using Filters
Filters are useful for narrowing down data for different use cases. In this visualization, I focused on the genres Action & Adventure, Thrillers, and TV Comedies, filtering the data to include only entries from 2015 onward.

## Setting Up a Dashboard
As a finishing touch, I renamed the graphs and ensured the data looked good. QuickSight also allows exporting dashboards as PDFs, which I did by selecting the export option and choosing PDF.

## Skills Demonstrated
- AWS S3
- Static Website Hosting
- Access Control Lists (ACLs)
- Web Development
- Troubleshooting
- Data Visualization
- Business Intelligence (BI)
- Amazon QuickSight
- Data Analysis
- Dashboard Creation

## Conclusion
This project showcases the capabilities of Amazon S3 for hosting static websites and Amazon QuickSight for data visualization and analysis. The ease of use and powerful features of QuickSight made it an excellent tool for this project.

---

**Vincent Mostert**  
