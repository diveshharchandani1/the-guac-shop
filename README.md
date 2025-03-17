# **The Guac Stop: End-to-End Data Warehousing and Analytics Solution**

## **Overview**
This project showcases a comprehensive **data warehousing and analytics solution** designed for **The Guac Stop**, leveraging industry-standard tools and cloud services to streamline **data ingestion, transformation, and visualization**. The goal was to create an efficient and scalable **data pipeline** that enables real-time insights and decision-making.

### **Tech Stack**
- 📂 **Oracle Cloud** – Data warehouse hosting and management  
- 🔄 **Apache Hop** – ETL pipeline design and orchestration  
- 📈 **Tableau** – Data visualization and dashboard development  

## **Project Workflow**
### **1️⃣ Setting Up the Cloud Data Warehouse**
- Configured a cloud-based data warehousing environment using **Oracle Cloud**.
- Built **dimension and fact tables** using **SQL DDL statements** to define relationships and enforce data integrity.
- Addressed key architectural considerations:
  - ✅ **Date Dimension Enhancement** – Implemented dynamic date structures for efficient time management.
  - ✅ **Fact Table Relationships** – Ensured a **star schema** design by linking fact tables only through shared dimensions.

#### 📌 **Dimensional Model**
*(Insert an image of your dimensional model here)*
```md
![Dimensional Model](images/dimensional_model.png)
```

---

### **2️⃣ Creating the ETL Pipeline with Apache Hop**
- Designed an **ETL pipeline** to populate the data warehouse.
- **Key challenges and solutions:**
  - ⚠️ **Reserved Keywords** – Renamed the `Date` column in the `Date_Dim` table to avoid conflicts in Oracle SQL.
  - 🛠️ **Schema Consistency** – Identified and corrected missing attributes (e.g., `ProductKey` in the `Product` table).
  - 🔗 **Foreign Key Handling** – Managed relationships through **ETL mappings** instead of database constraints for flexibility.

#### 📌 **ETL Pipeline Flow**
*(Insert an image of your Apache Hop ETL pipeline here)*
```md
![ETL Pipeline Flow](images/etl_pipeline.png)
```

---

### **3️⃣ Building the Business Intelligence Dashboard**
- Developed an **interactive dashboard in Tableau** to visualize sales performance.
- **Dashboard Features:**
  - 📊 **Total Sales KPI** – Aggregated key performance indicators (KPIs) for quick insights.
  - 📉 **Sales by Brand & Category** – Breakdown of sales performance across different product segments.
  - 📆 **Month-over-Month Trends** – Analyzed sales trends and seasonality.
  - 🎛️ **Filters** – Enabled city and category-based data exploration.

#### 📌 **Dashboard Screenshot**
*(Insert an image of your Tableau dashboard here)*
```md
![Dashboard Screenshot](images/dashboard.png)
```

---

## **Key Takeaways**
- ✅ **Data Integrity**: Ensured consistency through structured **SQL relationships**.  
- 🚀 **ETL Optimization**: Leveraged **Apache Hop** to streamline data transformation and improve efficiency.  
- 📊 **Visual Analytics**: Used **Tableau** to make complex data more accessible for business users.  

## **Repository Structure**
```md
├── data/                    # Sample data files and SQL scripts
├── etl/                     # Apache Hop ETL pipeline files
├── dashboard/               # Tableau workbook and screenshots
├── README.md                # Project documentation (this file)
```

## **Next Steps**
- Automate ETL pipeline for **real-time data ingestion**.
- Expand dataset to include **customer behavior insights**.
- Optimize **dashboard performance** for large datasets.

## **Author**
👨‍💻 **Divesh Harchandani**  
📧 [Your Email]  
🔗 [LinkedIn Profile]  
🚀 **University at Buffalo | Business & Entrepreneur Partnerships**  

