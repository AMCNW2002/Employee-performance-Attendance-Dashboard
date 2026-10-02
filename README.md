# 📊 Employee Performance & Attendance Dashboard

An interactive **Power BI dashboard** designed to analyze employee attendance, performance, leave patterns, and departmental workforce data.

This project demonstrates how **Excel data can be transformed into meaningful business insights using Power BI**, including interactive filtering, KPI monitoring, performance analysis, and data visualization.

---

## 🚀 Project Overview

Employee attendance and performance data can help organizations understand workforce behavior, identify performance trends, and monitor attendance patterns.

This dashboard provides a centralized view of:

* 👥 Employee workforce distribution
* 📈 Employee performance
* 🕒 Attendance rates
* 🏖️ Leave and absence patterns
* 🏢 Department-wise analysis
* 📅 Monthly attendance trends
* 🔎 Interactive employee-level details

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Analyze employee attendance across different months
* Monitor overall employee performance
* Compare performance between departments
* Analyze employee leave and absence patterns
* Visualize workforce distribution
* Provide interactive filtering for business analysis
* Create a professional and user-friendly HR analytics dashboard

---

## 📊 Dashboard Features

### 🔹 KPI Cards

The dashboard includes key performance indicators such as:

* **Total Employees**
* **Attendance Rate**
* **Average Performance Score**
* **Total Leave Days**

### 🔹 Department Performance

Analyzes the average performance score of employees across different departments.

### 🔹 Monthly Attendance Trend

Shows how employee attendance changes across:

* January 2026
* February 2026
* March 2026

### 🔹 Employees by Department

Visualizes the number of employees in each department.

### 🔹 Leave & Absence Analysis

Compares department-level:

* Leave Days
* Absent Days

### 🔹 Workforce Distribution

A pie chart provides a visual breakdown of employees by department.

### 🔹 Employee Performance Details

A detailed table provides employee-level information including:

* Employee ID
* Name
* Department
* Gender
* Month
* Present Days
* Absent Days
* Leave Days
* Performance Score

### 🔹 Interactive Slicers

Users can dynamically filter the entire dashboard using:

* **Department**
* **Gender**
* **Month**

---

## 🛠️ Tools & Technologies

| Technology             | Purpose                                  |
| ---------------------- | ---------------------------------------- |
| **Microsoft Power BI** | Dashboard development & visualization    |
| **Microsoft Excel**    | Dataset creation & data preparation      |
| **DAX**                | KPI calculations and analytical measures |
| **Power Query**        | Data cleaning and transformation         |

---

## 📁 Dataset

The dataset contains employee performance and attendance information for **20 employees across 3 months**, resulting in **60 records**.

### Dataset Fields

```text
Employee ID
Name
Department
Gender
Month
Working Days
Present Days
Absent Days
Leave Days
Performance Score
```

---

## 📐 Key DAX Measures

### Total Employees

```DAX
Total Employees =
DISTINCTCOUNT(Employee_Data[Employee ID])
```

### Attendance %

```DAX
Attendance % =
DIVIDE(
    SUM(Employee_Data[Present Days]),
    SUM(Employee_Data[Working Days]),
    0
)
```

### Average Performance

```DAX
Average Performance =
AVERAGE(Employee_Data[Performance Score])
```

### Total Leave Days

```DAX
Total Leave Days =
SUM(Employee_Data[Leave Days])
```

### Total Absent Days

```DAX
Total Absent Days =
SUM(Employee_Data[Absent Days])
```

---

## 🔄 Data Preparation Process

The project follows a basic data analytics workflow:

```text
Excel Dataset
      ↓
Power Query
      ↓
Data Cleaning
      ↓
Data Transformation
      ↓
Data Modeling
      ↓
DAX Measures
      ↓
Power BI Visualizations
      ↓
Interactive Dashboard
```

---

## 📸 Dashboard Preview

Add your Power BI dashboard screenshot here:

```markdown
![Employee Performance & Attendance Dashboard](screenshots/dashboard.png)
```

---

## 💡 Business Insights

The dashboard can help HR teams and managers:

* Monitor employee attendance
* Identify departments with attendance variations
* Compare employee performance
* Track leave and absence patterns
* Analyze workforce distribution
* Explore employee-level performance data
* Make data-driven workforce decisions

---

## 📂 Project Structure

```text
employee-performance-attendance-dashboard/
│
├── dataset/
│   └── Employee_Performance_Attendance_Dataset.xlsx
│
├── screenshots/
│   └── dashboard.png
│
├── Employee_Performance_Attendance_Dashboard.pbix
│
└── README.md
```

---

## ▶️ How to Use

1. Download or clone this repository.
2. Open the `.pbix` file using **Power BI Desktop**.
3. If required, update the Excel dataset source path.
4. Refresh the data.
5. Use the slicers to interact with the dashboard.
6. Explore the employee performance and attendance insights.

---

## 🎓 Skills Demonstrated

This project demonstrates practical skills in:

* Power BI
* Data Visualization
* Data Cleaning
* Power Query
* DAX
* Excel
* KPI Development
* Business Intelligence
* Dashboard Design
* Interactive Data Analysis
* Analytical Thinking

---

## 👨‍💻 Author

**AMC SANDARUWAN**

HNDIT – Information Technology

Interested in:

**Data Analytics | Power BI | Software Development | Cloud Computing | Cybersecurity**

---

## ⭐ If you found this project useful

Feel free to explore the repository, review the dashboard, and provide feedback.
