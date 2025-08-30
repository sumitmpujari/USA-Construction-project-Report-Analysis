# USA-Construction-project-Report-Analysis
This project tracks multiple construction projects across locations in the U.S. It includes sales, costs, timelines, progress, managers, and team members. The dashboard provides actionable insights into financial performance, project progress, resource allocation, and geographical distribution.

#Dataset

#The dataset has two main tables:

#1️⃣ Projects Table
| Project ID | Project Name         | Location      | Project Type  | Start Date | End Date   | Sales (\$)  | Est. Cost (\$) | Actual Cost (\$) | Progress % | Status      | Client Name   | Phase      | Manager ID | Manager Name   |
| ---------- | -------------------- | ------------- | ------------- | ---------- | ---------- | ----------- | -------------- | ---------------- | ---------- | ----------- | ------------- | ---------- | ---------- | -------------- |
| P001       | Skyline Towers       | New York, NY  | Residential   | 2025-01-15 | 2026-06-30 | 120,000,000 | 100,000,000    | 45,000,000       | 45%        | In Progress | Green Realty  | Structural | M001       | John Anderson  |
| P002       | Ocean View Villas    | Miami, FL     | Residential   | 2025-02-10 | 2026-04-20 | 80,000,000  | 70,000,000     | 30,000,000       | 40%        | In Progress | Blue Estates  | Foundation | M002       | Maria Gonzalez |
| P003       | TechPark Hub         | San Francisco | Commercial    | 2025-03-01 | 2026-12-15 | 200,000,000 | 180,000,000    | 90,000,000       | 50%        | In Progress | FutureTech    | Framing    | M003       | Alex Chen      |
| P004       | Midtown Plaza Mall   | Chicago, IL   | Commercial    | 2025-04-05 | 2026-08-10 | 150,000,000 | 140,000,000    | 70,000,000       | 48%        | In Progress | Retail Corp   | Electrical | M004       | Nisha Patel    |
| P005       | Riverside Hospital   | Houston, TX   | Institutional | 2025-05-12 | 2026-09-25 | 250,000,000 | 230,000,000    | 120,000,000      | 52%        | In Progress | HealthCareX   | Mechanical | M005       | George Miller  |
| P006       | Greenfield Warehouse | Dallas, TX    | Industrial    | 2025-06-20 | 2026-11-30 | 95,000,000  | 85,000,000     | 40,000,000       | 47%        | In Progress | LogiBuild     | Foundation | M006       | Hannah Lee     |
| P007       | Lakeside Resort      | Orlando, FL   | Hospitality   | 2025-07-15 | 2026-10-05 | 180,000,000 | 160,000,000    | 75,000,000       | 46%        | In Progress | Holiday Group | Structural | M007       | Kevin Brown    |

#2️⃣ Team Members Table
| Member ID | Member Name  | Role                | Assigned Project  | Project ID | Manager ID |
| --------- | ------------ | ------------------- | ----------------- | ---------- | ---------- |
| T001      | Priya Sharma | Architect           | Skyline Towers    | P001       | M001       |
| T002      | Ahmed Khan   | Structural Engineer | Skyline Towers    | P001       | M001       |
| T003      | Raj Mehta    | Site Supervisor     | Ocean View Villas | P002       | M002       |
| T004      | Chen Wei     | Civil Engineer      | Ocean View Villas | P002       | M002       |
| T005      | Sam Wilson   | Project Planner     | TechPark Hub      | P003       | M003       |
| T006      | Kiran Patel  | Mechanical Engineer | TechPark Hub      | P003       | M003       |
| T007      | Sofia Lopez  | Electrical Engineer | Midtown Plaza     | P004       | M004       |
| T008      | Robert Davis | Procurement Officer | Midtown Plaza     | P004       | M004       |
| T009      | Fatima Noor  | Medical Consultant  | Riverside Hosp.   | P005       | M005       |
| T010      | Rahul Verma  | Project Coordinator | Riverside Hosp.   | P005       | M005       |
| T011      | Amir Hassan  | Warehouse Planner   | Greenfield WH     | P006       | M006       |
| T012      | Leo Martin   | Logistics Engineer  | Greenfield WH     | P006       | M006       |
| T013      | Olivia White | Hospitality Expert  | Lakeside Resort   | P007       | M007       |
| T014      | Sanjay Rao   | Structural Engineer | Lakeside Resort   | P007       | M007       |

#Dashboard Features

The Power BI dashboard includes:
KPIs (Cards): Total Sales, Estimated Cost, Actual Cost, Profit, Avg Progress, Cost Overrun %
Timeline Tracking (Gantt Chart): Start & End dates with Progress %
Financial Comparison (Column Chart): Sales vs Estimated vs Actual Costs
Geographical View (Map): Projects by Location with Progress coloring
Project Overview (Matrix): Project → Manager → Team with Costs & Progress
Phase Distribution (Donut Chart): Foundation, Structural, Electrical, etc.
Filters (Slicers): Project Type, Status, Manager, Location, Phase

#Tools & Technologies
Power BI (Dashboard, DAX, Visuals)
Excel / CSV (Data Preparation)
GitHub (Project Documentation & Sharing)

#Insights from Dashboard
Riverside Hospital is the largest project ($250M).
Skyline Towers has the highest sales ($120M) but a cost overrun risk.
TechPark Hub is the most expensive commercial project.
Miami’s Ocean View Villas is behind schedule at 40% progress.
Cost overruns are visible in multiple projects, highlighting the need for tighter control.


