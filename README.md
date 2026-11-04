# HR Attrition Dashboard (Power BI)

A 3-page interactive Power BI dashboard that analyses employee attrition for a company of 1,200 employees. It shows who is leaving, why they leave, and how attrition relates to tenure, overtime, salary, satisfaction and performance.

> **Note:** The dataset is synthetic (practice data), created for learning and portfolio purposes. It does not come from a real company.

---

## Key Findings

- **1,200 employees, 233 exits, 19% attrition rate**
- Top exit reasons: **better compensation (27%)** and **career growth (25%)**
- Attrition is highest among employees with **under 1 year of tenure**
- Employees working **overtime leave far more often: about 31% vs 15%** for those who do not

---

## Dashboard Pages

### Page 1: Overview
Headline KPIs (total employees, exits, active employees, attrition rate, average salary, estimated attrition cost) and attrition by department.

![Overview](Screenshots/page1.png)

### Page 2: Why People Leave
Exit reasons and the factors linked to attrition: tenure, age group, overtime, job satisfaction and salary band.

![Why People Leave](Screenshots/page2.png)

### Page 3: People and Performance
How attrition connects with workforce and performance data.

![People and Performance](Screenshots/page3.png)

---

## Tools Used

| Tool | Used for |
|------|----------|
| **Power BI Desktop** | Dashboard design and interactive visuals |
| **Power Query** | Cleaning and shaping the data |
| **DAX** | Measures and calculations |
| **Excel** | Source dataset |

---

## DAX Measures

The dashboard uses measures for:

- Exits
- Active employees
- Attrition rate
- Average salary
- Estimated attrition cost

---

## Data Modelling and Cleaning

- Loaded the Excel dataset into Power Query
- Cleaned and shaped the data (data types, categories, groupings such as tenure, age group and salary band)
- Designed the data model and wrote the DAX measures used across all three pages

---

## What I Learned

- Building a multi-page Power BI report from raw data to finished dashboard
- Writing DAX measures for business KPIs
- Turning data into clear findings about a business problem (employee attrition)

---

## How to Open This Project

1. Download or clone this repository.
2. Install **Power BI Desktop** (free from Microsoft).
3. Open the `.pbix` file from this repository in Power BI Desktop.
4. If asked, refresh the data or point the source to the Excel file included in the repo.

---

## Repository Contents

- `.pbix` file: the Power BI dashboard
- `Screenshots/`: images of the three dashboard pages
- `README.md`: this file

---

## Author

**Rutik Kumbhar**
Junior Data Analyst | Power BI | SQL
Pune, India

- GitHub: [github.com/Rutik2908](https://github.com/Rutik2908)
- LinkedIn: [linkedin.com/in/rutik-kumbhar-a02841302](https://linkedin.com/in/rutik-kumbhar-a02841302)
- Email: rutikkumbhar9@gmail.com
