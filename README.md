# PSHS-Main Campus Printing Request Tracker
 
## Overview
 
The **PSHS-Main Campus Printing Request Tracker (PRT)** is a centralized system designed to monitor, record, and analyze printing requests submitted by teachers and staff across all academic and non-academic units of Philippine Science High School Main Campus.
 
The primary goal of the system is to provide accurate data on paper consumption and printing resource utilization, enabling informed decision-making, budgeting, sustainability initiatives, and operational planning.
 
---
 
## Objectives
 
The system aims to:
 
- Track the total number of printing requests submitted across the campus.
- Determine the exact quantity of paper consumed for all printing activities.
- Monitor paper usage by unit, department, requester, and time period.
- Record the type and size of paper used for each printing request.
- Identify whether paper was supplied by:
  - The requesting individual/unit
  - The school
- Track printing configurations that affect resource consumption, including:
  - Single-sided printing
  - Back-to-back (duplex) printing
  - Multiple pages per sheet (2-up, 4-up, etc.)
  - Record color settings used during printing:
  - Black and White
  - Grayscale
  - Full Color
- Generate reports for resource allocation, budgeting, and sustainability monitoring.
 
---
 
## Key Features
 
### Request Management
- Submission and tracking of printing requests
- Request status monitoring
- Historical request records
 
### Paper Consumption Tracking
- Total sheets used per request
- Estimated actual paper consumption based on print settings
- Unit-level and campus-wide aggregation
 
### Paper Information
- Paper size
  - A4
  - Letter
  - Legal
  - Other custom sizes
- Paper type
- Bond Paper
- Specialty Paper
- Photo Paper
- Other
 
### Paper Source Monitoring
Each request records whether the paper was:
 
- School-provided
- Requester-provided
 
This allows the school to accurately assess institutional paper expenditures versus externally supplied materials.
 
### Print Configuration Tracking
 
The system records:
 
| Setting | Examples |
|----------|----------|
| Print Mode | Single-Sided, Duplex |
| Pages per Sheet | 1, 2, 4, 6, 8 |
| Color Mode | Black & White, Grayscale, Color |
| Copies | Number of copies produced |


These settings help calculate actual paper usage and printing costs.
 
### Reporting and Analytics
 
Generate reports such as:
 
- Total paper consumption by month
- Paper consumption by department/unit
- School-provided vs. requester-provided paper usage
- Color printing utilization
- Duplex printing adoption rate
- Top printing requestors
- Printing trends over time

 
---
 
## Intended Users
 
- Faculty Members
- Administrative Staff
- Academic Units
- Non-Academic Units
- Printing Personnel
- School Administrators
 
---
 
## Sample Data Fields
 
| Field | Description |
|---------|-------------|
| Request ID | Unique request identifier |
| Date Submitted | Date request was made |
| Requester Name | Teacher or staff member |
| Unit/Department | Requesting office/unit |
| Document Title | Name/description of document |
| Number of Pages | Total pages in document |
| Number of Copies | Copies requested |
| Pages per Sheet | Printing layout |
| Print Type | Single-sided or duplex |
| Color Mode | B&W, Grayscale, Color |
| Paper Size | A4, Letter, Legal, etc. |
| Paper Type | Bond, Specialty, etc. |
| Paper Source | School or Requester |
| Estimated Sheets Used | Computed actual paper consumption |
| Status | Pending, Printing, Completed |
 
---
 
## Paper Consumption Formula
 
Actual paper consumption may be calculated using:
 
```
Estimated Sheets Used =
(Number of Pages × Number of Copies)
÷ Pages Per Sheet
÷ Duplex Factor
```
 
Where:
 
- Duplex Factor = 2 for back-to-back printing
- Duplex Factor = 1 for single-sided printing
 
Additional adjustments may be applied depending on institutional policies and print setup.
 
---
 
## Benefits
 
### Operational Benefits
- Improved monitoring of printing activities
- Better accountability across units
- Streamlined documentation of requests
 
### Financial Benefits
- Accurate paper cost tracking
- Improved budgeting and procurement planning
- Identification of high-volume printing areas
 
### Sustainability Benefits
- Reduced paper waste
- Encouragement of duplex printing
- Data-driven environmental initiatives
- Support for green campus programs
 
---
 
## Future Enhancements
 
- User authentication and role management
- Approval workflows
- Cost estimation module
- Printer utilization analytics
- Dashboard visualizations
- Export to Excel and PDF reports
- Automated monthly summaries
- Integration with inventory management systems
 
---
 
## Project Vision
 
The PSHS-Main Campus Printing Request Tracker serves as a data-driven solution for responsible resource management by providing clear visibility into paper consumption, printing practices, and operational costs across the institution. Through accurate tracking and reporting, the system supports efficiency, accountability, sustainability, and informed decision-making.
