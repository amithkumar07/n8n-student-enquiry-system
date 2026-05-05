# n8n Automation Project

## Overview

This project contains automation workflows built using n8n to handle backend processes such as data extraction, transformation, and storage. It focuses on automating real-world tasks like managing student enquiry data.

## Features

* Reads and processes data from Excel files
* Stores student enquiry details automatically
* Webhook-based workflow triggers
* API integration for data handling
* Structured and reusable automation workflows

## Use Case: Student Enquiry Management

This workflow can:

* Fetch data from an Excel sheet
* Extract student details (name, contact, enquiry, etc.)
* Automatically upload and store the data into a system/database

## How It Works

1. Excel file is used as a data source
2. n8n reads and processes the data
3. Workflow extracts required fields
4. Data is sent via API or stored in the desired destination

## Setup Instructions

1. Import the workflow JSON into n8n
2. Connect your Excel file or data source
3. Configure API/database credentials
4. Run or activate the workflow

## Tech Stack

* n8n (workflow automation)
* Excel (data source)
* REST APIs / Webhooks

## Data Source

The workflow processes data from an Excel file (or cloud storage like Google Drive).
A sample file structure is provided for reference.

 Actual data files are not included 


## Notes

* Credentials are not included for security reasons
* Designed for learning and real-world automation use cases
