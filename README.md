# Employee Attrition Dashboard

This repository contains a Power BI dashboard built to analyze employee attrition using an HR dataset extracted from an Excel file. The dashboard provides KPIs and visual breakdowns to help understand which groups are leaving the organization and why.

**Project Purpose**: Provide an interactive view of attrition drivers (demographics, compensation, career progression, and satisfaction) to inform retention strategies.

**Files**
- `Dashboard.pbix`: Power BI dashboard file (report and visuals).
- `dataset.xlsx`: HR dataset used as the data source (one row per employee).
- `README.md`: Project documentation (this file).

**Dataset Description**
- **Age & Demographics**: `Age`, `Gender`, `Marital Status`, `Education`, `Education Field`, `CF_age band` (custom age groups).
- **Employment Info**: `Department`, `Job Role`, `Job Level`, `Business Travel`, `Over Time`, `Work Life Balance`, `Job Involvement`, `Job Satisfaction`, `Environment Satisfaction`, `Performance Rating`, `Relationship Satisfaction`.
- **Compensation**: `Monthly Income`, `Hourly Rate`, `Daily Rate`, `Monthly Rate`, `Percent Salary Hike`, `Stock Option Level`.
- **Career Progression**: `Years At Company`, `Years In Current Role`, `Years Since Last Promotion`, `Years With Curr Manager`, `Total Working Years`, `Num Companies Worked`.
- **Attrition**: `Attrition` (Yes/No), `CF_attrition label` (Current vs Ex-Employee).

**Key KPIs & Visuals**
- **Attrition Rate**: Percentage of employees who have left the organization.
- **Attrition by Job Role**: Distribution of departed employees by `Job Role`.
- **Attrition by Age Band**: Proportion of departures across `CF_age band` groups.
- **Attrition by Education Level**: Distribution of departing employees by `Education`.
- **Average Years Since Last Promotion (by Job Role)**: Average of `Years Since Last Promotion` per `Job Role`.
- **Average Monthly Income (by Job Role)**: Average of `Monthly Income` per `Job Role`.
- **Average Job Involvement (by Job Role)**: Average of `Job Involvement` per `Job Role`.
- **Average Job Satisfaction (by Job Role)**: Average of `Job Satisfaction` per `Job Role`.
- **Average Work-Life Balance (by Job Role)**: Average of `Work Life Balance` per `Job Role`.

Installation & Usage
- **Prerequisite**: Install `Power BI Desktop` (Windows).
- **Open the report**: Double-click or open `Dashboard.pbix` in Power BI Desktop.
- **Data source**: Ensure `dataset.xlsx` is in the same folder or update the data source path in Power BI (`Home` → `Transform data` → `Data source settings`).
- **Refresh data**: In Power BI Desktop, choose `Home` → `Refresh` to load data from `dataset.xlsx` after any changes to the Excel file.
- **Exporting**: Use `File` → `Export` → `Power BI template` or export visuals to PDF/PNG from the report view.

Screenshots
- Add screenshots to this README by placing image files in a `screenshots/` folder and referencing them as:
  - `screenshots/overview.png` (KPI overview)
  - `screenshots/attrition_by_role.png` (Attrition by job role)
- To include images in this README, use markdown image syntax: `![Overview](screenshots/overview.png)`.

Insights & Suggested Analyses
- Check whether attrition concentrates in specific `Job Role` or `Department` groups.
- Compare `Monthly Income` and `Percent Salary Hike` between retained vs departed employees.
- Analyze promotion cadence: high `Years Since Last Promotion` may correlate with higher attrition.
- Investigate satisfaction metrics (`Job Satisfaction`, `Work Life Balance`, `Job Involvement`) for groups with high attrition.
- Explore tenure patterns: `Years At Company` and `Years In Current Role` vs attrition.
- Use cross-filters (e.g., filter by `Job Level` and `Age Band`) to find interaction effects.

Contributing
- To suggest changes to the dashboard or dataset, create an issue or open a PR with the proposed `Dashboard.pbix` or `dataset.xlsx` updates.

Contact
- Maintainer: repository owner

License
- This repository does not include a license by default. Add a `LICENSE` file if you want to make usage terms explicit.

If you want, I can also add:
- Installation / usage step-by-step images and specific data-source update instructions.
- A `screenshots/` folder and example images inserted into this README.
- A short `insights.md` that summarizes top findings from the dataset.

