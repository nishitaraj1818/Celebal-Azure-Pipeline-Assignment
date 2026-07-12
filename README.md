# Celebal-Azure-Pipeline-Assignment

## Objective

Build an end-to-end data pipeline using Azure Blob Storage and Azure Data Factory.

## Services Used

- Azure Resource Group
- Azure Storage Account
- Azure Blob Storage
- Azure Data Factory
- Azure IAM

## Pipeline Flow

Blob Storage (Source)
        ↓
Get Metadata
        ↓
Copy Data
        ↓
Blob Storage (Destination)

## Steps Performed

- Created Resource Group
- Created Storage Account
- Created Blob Containers
- Uploaded Superstore CSV
- Created Azure Data Factory
- Configured Linked Service
- Created Source and Destination Datasets
- Implemented Get Metadata Activity
- Implemented Copy Data Activity
- Validated Pipeline
- Debugged Pipeline
- Triggered Pipeline
- Monitored Pipeline Execution
- Verified Output File
- Assigned IAM Roles

## Metadata Validation

- Exists
- Size

## Result

The pipeline successfully copied the CSV file from the source Blob container to the destination Blob container after validating metadata.

