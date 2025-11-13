# 🎵 Chinook Music Store Analytics Dashboard

A comprehensive multi-page Power BI dashboard analyzing music store operations, sales performance, customer behavior, employee metrics, and music catalog insights for Chinook digital media store.

---

## 📊 Project Overview

This Power BI project delivers a complete business intelligence solution for Chinook, a digital music store, providing actionable insights across six interconnected dashboards. The project demonstrates advanced data modeling, DAX calculations, interactive visualizations, and professional dashboard design principles.

### Business Objectives
- Monitor key sales and revenue metrics across different time periods
- Analyze customer purchasing patterns and retention
- Track employee performance and customer support metrics
- Understand music catalog composition and popularity trends
- Identify top-performing artists, albums, and tracks
- Visualize geographic sales distribution

---

## 🎯 Key Features

### Multi-Page Navigation System
- **Performance Overview**: Executive summary with key business metrics
- **Sales Analysis**: Revenue trends and sales breakdowns
- **Customers Analysis**: Customer segmentation and purchasing behavior
- **Employees Analysis**: Workforce metrics and support rep performance
- **Tracks Analysis**: Music catalog composition and trends
- **Artists Analysis**: Artist performance and popularity metrics

### Interactive Elements
- Year-based filtering (2021-2025) across all pages
- Dynamic slicers for country and city selection
- Cross-page drill-through capabilities
- Responsive visualizations with hover tooltips
- Clear, icon-based navigation system

### Professional Design
- Consistent color scheme (sage green/teal palette)
- Clean, modern UI with rounded corners and shadows
- Branded header with company logo
- Icon-enhanced KPI cards
- Well-organized layout with visual hierarchy

---

## 📈 Dashboard Pages Breakdown

### 1️⃣ Performance Overview
**Purpose**: Landing page with high-level KPIs for quick business health assessment

**Key Metrics**:
- Total Sales: 2.33K
- Number of Sold Tracks: 2K
- Total Transactions: 412
- Most Sold Artist: Iron Maiden

**Features**: Clean summary view with navigation to detailed analysis pages

---

### 2️⃣ Sales Analysis
**Purpose**: Comprehensive sales performance tracking and revenue analysis

**Key Metrics**:
- Total Sales: 2.33K
- Number of Orders: 412
- Average Sales per Order: 1.03
- Total Price: 5.74K

**Visualizations**:
- **Total Sales Per Artist**: Horizontal bar chart showing Iron Maiden leading with 334 sales
- **Sales Per Media Type**: Bar chart with MPEG audio files dominating at 4.8K
- **Sales Over Time**: Line chart displaying trend from 2021-2025 with peak at 1,180 in 2024
- **Total Sales Per Album**: Horizontal bar chart featuring top albums
- **Sales By Country**: Interactive geographic map showing global distribution

**Key Insights**:
- Rock music (Iron Maiden, U2, Metallica) drives majority of sales
- MPEG audio format is the dominant media type
- Sales peaked in 2024 before declining in 2025
- Global customer base with strong presence across multiple continents

---

### 3️⃣ Customers Analysis
**Purpose**: Customer behavior analysis and segmentation

**Key Metrics**:
- Total Customers: 59
- Average Orders per Customer: 5.65
- Repeat Customer Rate: 100%

**Visualizations**:
- **Customer Distribution**: Dual-axis breakdown by country and city with clear buttons
- **Top 10 Purchasing Customers**: Horizontal bar chart showing customer lifetime value
- **Top Purchasing Companies**: Bar chart with Yahoo leading at 1.7K

**Key Insights**:
- USA leads customer count with 13 customers
- São Paulo is the top Brazilian city with 2 customers
- Perfect customer retention (100% repeat rate)
- Strong corporate customer segment led by Yahoo

**Interactive Features**: Country and city filters for drill-down analysis

---

### 4️⃣ Employees Analysis
**Purpose**: Workforce composition and employee performance tracking

**Key Metrics**:
- Total Employees: 8
- Number of Cities: 3
- Job Titles: 5 distinct roles
- Average Employee Age: 60.50 years

**Visualizations**:
- **Years of Experience per Employee**: Bar chart showing range from 21-23 years
- **Employees per Title**: Sales Support Agent is most common (3 employees)
- **Customers per Support Rep**: Jane Peacock handles 21 customers
- **Employee per City**: Pie chart showing Calgary dominates with 62.5%

**Key Insights**:
- Experienced workforce with 21-23 years average tenure
- Sales Support Agent is the most common role
- Calgary is the primary employee hub
- Balanced customer distribution across support representatives

---

### 5️⃣ Tracks Analysis
**Purpose**: Music catalog composition and track performance analysis

**Key Metrics**:
- Total Tracks: 1,984
- Rock Tracks: 745
- Most Sold Genre: Rock (2.33K sales)
- Most Sold Track: "Dazed and Confused" (2.33K)

**Visualizations**:
- **Tracks per Album**: Greatest Hits leads with 25 tracks
- **Tracks per Playlist**: Music playlist dominates with 1,881 tracks
- **Total Sales per Track**: Bar chart identifying top performers
- **Tracks per Genre**: Rock leads with 745 tracks
- **Tracks Over Time**: Area chart showing consistent 442-455 tracks annually (2021-2025)

**Key Insights**:
- Rock genre dominates catalog and sales
- "Greatest Hits" compilation format is popular
- Consistent catalog size maintained year-over-year
- Music playlist is the primary categorization

---

### 6️⃣ Artists Analysis
**Purpose**: Artist catalog size and sales performance

**Key Metrics**:
- Total Artists: 275
- Total Tracks: 2K
- Total Playlists: 18
- Total Albums: 347

**Visualizations**:
- **Top 5 Artists per Tracks**: Iron Maiden leads with 213 tracks
- **Top 5 Albums**: Battlestar Galactica soundtrack tops with 36 tracks
- **Top 5 Artists by Sales**: Iron Maiden dominates with 334 sales
- **Top 3 Playlists**: Donut chart showing Music playlist at 75.25%

**Key Insights**:
- Iron Maiden is the top artist by both track count and sales
- Strong classic rock representation (Iron Maiden, U2, Led Zeppelin, Metallica)
- Diverse catalog with 275 artists across 347 albums
- Music playlist contains three-quarters of all content

---

## 🛠️ Technical Implementation

### Data Model
- Star schema design for optimal query performance
- Date table for time intelligence calculations

### DAX Measures (Inferred)
- Total Sales calculations
- Average order value
- Customer retention metrics
- Year-over-year comparisons
- Ranking and Top N calculations
- Time intelligence for trends

### Visualizations Used
- KPI Cards with custom formatting
- Horizontal and vertical bar charts
- Line and area charts for trends
- Pie and donut charts for distribution
- Geographic maps for spatial analysis
- Interactive slicers and filters

---

## 📸 Screenshots

The repository includes high-quality screenshots of all six dashboard pages:

1. `overview-page.jpg` - Performance Overview landing page
2. `sales-dashboard.jpg` - Comprehensive sales analysis
3. `customers-dashboard.jpg` - Customer behavior insights
4. `employees-dashboard.jpg` - Workforce analytics
5. `tracks-dashboard.jpg` - Music catalog analysis
6. `artist-dashboard.jpg` - Artist performance metrics

---

## 💡 Business Impact & Insights

### Sales Insights
- Identified Iron Maiden as the top-performing artist.
- Discovered MPEG format preference, informing digital format strategy
- Tracked sales decline from 2024 peak (1,180) to 2025 (1,105).

### Customer Insights
- 100% repeat customer rate indicates strong customer loyalty
- Geographic concentration in USA, Brazil, and Canada suggests market expansion opportunities
- Average 5.65 orders per customer shows healthy engagement

### Operational Insights
- Sales Support Agents handle average of 20 customers each
- Calgary-based workforce concentration may impact support coverage
- Experienced team (21-23 years tenure) provides stability

### Product Insights
- Rock genre dominates both catalog (745 tracks) and sales
- Compilation albums (Greatest Hits) perform well
- Consistent catalog size maintenance shows stable operations

---

## 📁 Repository Structure

data_chinook_dashboard/
│
│── overview-page.jpg
│── sales-dashboard.jpg
│── customers-dashboard.jpg
│── employees-dashboard.jpg
│── tracks-dashboard.jpg
│── artist-dashboard.jpg
└── README.md


### Technologies Used
- **Power BI Desktop**: Dashboard development
- **DAX**: Measure calculations and data manipulation
- **Power Query**: Data transformation and cleansing
- **Chinook Database**: Sample data source

---

## 📧 Contact & Connect
Feel free to reach out to discuss this project or potential collaborations! 
**LinkedIn**: [MyLinkedIn](https://www.linkedin.com/in/hossam-badawy)
**Email**: hossam.mousa779@gmail.com

---

**Last Updated**: November 2025

