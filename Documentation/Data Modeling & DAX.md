## 1. Data Modeling

Data modeling is the process of organizing and structuring data so that it can be analyzed efficiently.

**Star Schema** in Power BI.
- It consists of a central **fact table** and multiple **dimension tables**
- The **fact table** contains key data like IDs and numerical values
- **Dimension tables** contain descriptive details

### Example:
- Fact table → Accident data  
- Dimension tables → Weather, Location, Time  

### Benefits:
- Improves performance  
- Enhances clarity  
- Makes analysis easier  


## 2. Cardinality (Relationships)

Relationships between tables is also called as **cardinality**.

### Types of Relationships:
- One-to-Many  
- Many-to-One  
- One-to-One  
- Many-to-Many  

These relationships define how tables are connected and how data flows between them.


## 3. Data Import vs Live Connection

Initially, data is imported from Excel or CSV into Power BI.

### Limitations of Import:
- Power BI creates a copy of data  
- Data does not update automatically  

If data changes:
- We must reload and redo the work  

### Solution: Live Data Connection
- Power BI connects directly to the database  
- Data updates dynamically  
- No need to recreate dashboards  

This connection is done using an **API (Application Programming Interface)**.


## 4. DAX (Data Analysis Expressions)

DAX is a formula language used in Power BI.  

### Can Create:
- Measures  
- Calculated columns  

### Examples:
- `Total Sales = SUM(Sales)`  
- Count of products  

DAX helps convert raw data into meaningful insights.


## 5. KPI Cards

KPI cards are used to display:
- Important metrics  
- Summary values  

### Examples:
- Total accidents  
- Total casualties  
- Total sales  

### Important Point:
- DAX calculates values  
- KPI cards display them  


## 6. Data Visualization & Dashboard Design

### Key Elements:
- **Title** → Simple and clear  
- **KPI Cards** → Placed at the top  
- **Charts** → For analysis  
- **Slicers** → For filtering  
