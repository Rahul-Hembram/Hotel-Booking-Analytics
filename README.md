# 🏨 Hotel Booking Cancellation Analysis & Dashboard

> 📊 **Data Analytics Project | Excel | Power Query | Data Cleaning | Exploratory Analysis | Interactive Dashboard**

An end-to-end **Hotel Booking Cancellation Analysis** project built to explore booking patterns, cancellation behavior, customer characteristics, and hotel performance using real-world hotel booking data.

The project uses a **Kaggle hotel bookings dataset in CSV format**, which was cleaned, transformed, analyzed, and visualized using **Microsoft Excel and Power Query**. The final outcome is a colorful, interactive analytical dashboard designed to turn raw booking data into meaningful business insights.

---

## 📌 Project Overview

Hotel cancellations can significantly affect hotel revenue, room utilization, staffing, and overall operational planning.

This project analyzes hotel booking data to answer questions such as:

* 📈 How many bookings are being cancelled?
* 🏨 Which hotel type has more cancellations?
* 🌍 Which countries contribute the most bookings and cancellations?
* 📅 How do bookings and cancellations change over time?
* 👥 Which customer types are more likely to cancel?
* 💳 Does the deposit type influence cancellation behavior?
* 🛏️ How do room types and booking characteristics affect cancellations?
* ⏳ Does lead time have a relationship with cancellation?
* 💰 What patterns can be identified that may help hotels reduce cancellations?

The goal is to transform a large raw dataset into a **clear, visually appealing, and business-focused dashboard**.

---

## 🎯 Objectives

The main objectives of this project were:

1. **Clean and prepare raw hotel booking data**
2. Handle missing and inconsistent values
3. Transform the dataset using **Power Query**
4. Perform exploratory data analysis using Excel
5. Identify important cancellation patterns
6. Create meaningful KPIs and analytical metrics
7. Build interactive Pivot Tables and Pivot Charts
8. Design a professional dashboard using a custom color palette
9. Convert raw data into actionable business insights

---

## 📂 Dataset

The dataset used for this project was obtained from **Kaggle** and provided in CSV format.

The dataset contains detailed information about hotel reservations, including booking status, customer characteristics, arrival information, room details, market segments, and other booking attributes.

### 🔑 Important Dataset Columns

Some of the major variables analyzed include:

| Category       | Variables                                 |
| -------------- | ----------------------------------------- |
| 🏨 Hotel       | Hotel Type                                |
| 📅 Booking     | Arrival Date, Lead Time                   |
| ❌ Cancellation | Is Cancelled                              |
| 👥 Customer    | Adults, Children, Babies, Customer Type   |
| 🛏️ Room       | Reserved Room Type, Assigned Room Type    |
| 💳 Payment     | Deposit Type                              |
| 🌍 Location    | Country                                   |
| 📊 Market      | Market Segment, Distribution Channel      |
| 🧑‍💼 Agent    | Agent / Company                           |
| 🛎️ Stay       | Weekend Nights, Week Nights               |
| 💰 Revenue     | ADR                                       |
| 📋 Booking     | Previous Cancellations, Previous Bookings |

---

## 🛠️ Tools & Technologies

### 📊 Microsoft Excel

Used for:

* Data exploration
* Pivot Tables
* Pivot Charts
* KPI calculations
* Dashboard creation
* Conditional formatting
* Data visualization

### 🔄 Power Query

Used for:

* Importing the CSV dataset
* Data cleaning
* Removing unnecessary columns
* Handling missing values
* Transforming data types
* Preparing data for analysis
* Creating a structured analytical dataset

### 📈 Excel Dashboard

Used to create:

* KPI cards
* Bar charts
* Column charts
* Line charts
* Donut/Pie charts
* Interactive filters
* Pivot-based visualizations

---

## 🔄 Data Analytics Workflow

```text
Raw Kaggle Dataset
        ↓
     CSV File
        ↓
   Power Query
        ↓
   Data Cleaning
        ↓
 Data Transformation
        ↓
   Exploratory Analysis
        ↓
   Pivot Tables
        ↓
   Pivot Charts
        ↓
   Dashboard Design
        ↓
 Business Insights
```

---

## 🧹 Data Cleaning & Transformation

The raw dataset was processed using **Power Query** before performing the analysis.

The cleaning process included:

* 🔍 Inspecting the dataset structure
* 🧹 Removing unnecessary fields
* 🔄 Correcting data types
* 🕳️ Handling missing values
* 📝 Standardizing categorical values
* 📅 Formatting date-related fields
* 🔢 Preparing numerical columns for analysis
* 📊 Creating analysis-ready data

Power Query helped make the transformation process **repeatable and structured**, instead of manually modifying thousands of records.

---

## 📊 Key Analysis Areas

### 1. Cancellation Analysis

The primary focus of the project is understanding hotel booking cancellations.

Metrics analyzed include:

* Total Bookings
* Cancelled Bookings
* Confirmed Bookings
* Cancellation Rate
* Cancellation trends
* Cancellation distribution by hotel type

---

### 2. Hotel Performance

The analysis compares different hotel categories to understand:

* Booking volume
* Cancellation volume
* Cancellation rate
* Customer behavior
* Booking patterns

---

### 3. Customer Analysis

Customer characteristics were analyzed to understand cancellation behavior across:

* Customer type
* Number of adults
* Number of children
* Number of babies
* Previous cancellations
* Previous bookings

---

### 4. Geographic Analysis 🌍

Country-level booking data was explored to identify:

* Major booking markets
* Countries with high booking volume
* Countries contributing to cancellations
* Geographic patterns in customer behavior

---

### 5. Booking Lead Time ⏳

Lead time was analyzed to understand whether the time between booking and arrival is associated with cancellation behavior.

This can help hotels identify potentially high-risk reservations.

---

### 6. Market Segment Analysis

Different market segments and distribution channels were compared to identify:

* Booking contribution
* Cancellation behavior
* Customer acquisition patterns
* Channel performance

---

### 7. Deposit Type Analysis 💳

Deposit types were analyzed to understand their relationship with cancellations.

This provides a useful business perspective because payment and deposit policies can influence booking commitment.

---

## 📌 Dashboard KPIs

The dashboard focuses on important high-level metrics such as:

| KPI                   | Purpose                                  |
| --------------------- | ---------------------------------------- |
| 🏨 Total Bookings     | Overall booking volume                   |
| ❌ Cancelled Bookings  | Number of cancelled reservations         |
| ✅ Confirmed Bookings  | Number of non-cancelled reservations     |
| 📊 Cancellation Rate  | Percentage of bookings cancelled         |
| 💰 Average Daily Rate | Average room price                       |
| 👥 Customer Count     | Overall customer/booking volume          |
| ⏳ Average Lead Time   | Average time between booking and arrival |

---

## 🎨 Dashboard Design

The dashboard was designed with a **modern, colorful analytical theme** to make the information easier to understand and visually engaging.

### 🎨 Color Palette

```text
#FFF4BF  → Light Cream / Background
#FFBEFB  → Soft Pink
#DC95FF  → Light Purple
#8C56D4  → Deep Purple
```

The palette was used across KPI cards, charts, backgrounds, and dashboard elements to create a consistent visual identity.

---

## 📈 Visualizations

The dashboard includes multiple visualization types, including:

### 📊 Bar Charts

Used to compare:

* Hotel types
* Customer types
* Market segments
* Countries
* Cancellation categories

### 📈 Line Charts

Used to analyze:

* Booking trends
* Cancellation trends
* Arrival patterns
* Time-based changes

### 🍩 Donut / Pie Charts

Used for:

* Booking composition
* Cancellation vs non-cancellation
* Hotel distribution
* Customer segmentation

### 📋 KPI Cards

Used to provide an immediate overview of the most important metrics.

---

## 💡 Business Insights

The analysis aims to identify insights that can support hotel management in areas such as:

### Revenue Management

Understanding cancellation patterns can help hotels improve revenue forecasting and pricing strategies.

### Capacity Planning

Identifying periods with high cancellation risk can help hotels manage room inventory more effectively.

### Customer Segmentation

Understanding which customer groups cancel more frequently can help hotels create targeted policies.

### Booking Policies

Analysis of lead time and deposit types can help evaluate whether stricter booking policies could reduce cancellation risk.

### Marketing & Distribution

Understanding which market segments and distribution channels generate bookings can help hotels optimize their acquisition strategy.

---

## 📸 Dashboard Preview

> Add your dashboard screenshot here.

```markdown
![Hotel Booking Analytics Dashboard](images/hotel-booking-dashboard.png)
```

If your screenshot is stored in the repository under an `images` folder, the above Markdown will display it directly on GitHub.

---

## 📁 Project Structure

```text
Hotel-Booking-Analytics/
│
├── 📂 data/
│   └── hotel_bookings.csv
│
├── 📂 dashboard/
│   └── hotel_booking_dashboard.xlsx
│
├── 📂 images/
│   └── hotel-booking-dashboard.png
│
└── README.md
```

---

## 🚀 Key Skills Demonstrated

This project demonstrates practical experience with:

* 📊 Data Analytics
* 🧹 Data Cleaning
* 🔄 Power Query
* 📑 Microsoft Excel
* 📌 Pivot Tables
* 📈 Data Visualization
* 🎨 Dashboard Design
* 🔍 Exploratory Data Analysis
* 📊 KPI Development
* 💼 Business Analysis
* 💡 Insight Generation
* 🧠 Data-driven Decision Making

---

## 📚 What I Learned

Through this project, I gained practical experience in taking a **raw dataset and converting it into a structured analytical solution**.

The project helped strengthen my understanding of:

* Real-world data cleaning
* Data transformation
* Exploratory data analysis
* Pivot-based analysis
* Dashboard storytelling
* Choosing appropriate visualizations
* KPI design
* Business-oriented data interpretation

Most importantly, the project helped me understand that **data analytics is not only about creating charts — it is about finding patterns and translating those patterns into useful business insights.**

---

## 🔮 Future Improvements

Potential improvements for the project include:

* 🐍 Recreating the analysis using Python and Pandas
* 📊 Building an interactive Power BI version
* 🤖 Developing a cancellation prediction model
* 📈 Adding advanced customer segmentation
* 💰 Estimating potential revenue loss from cancellations
* 🎯 Developing a cancellation-risk scoring system
* 📅 Creating more detailed seasonal analysis

---
