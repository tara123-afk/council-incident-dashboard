# council-incident-dashboard
Azure-based Council Incident Dashboard using Logic Apps, Blob Storage, and Static Website hosting.
# Council Incident Dashboard

This project demonstrates a cloud-based data pipeline and dashboard using Microsoft Azure.

## Architecture Overview
- Azure Blob Storage (raw-data, processed-data, public-dashboard-data, archive, logs)
- Azure Logic Apps (automated workflow)
- Static Website Hosting (dashboard UI)

## Workflow
1. CSV file uploaded to raw-data container
2. Logic App processes the data
3. Curated JSON generated and stored
4. Dashboard reads data from public container

## Dashboard URL
https://councilincidentstara01.z8.web.core.windows.net/

## Key Features
- Real-time data processing
- Automated workflow using Logic Apps
- Interactive dashboard with metrics and charts
