# What is BIA?

Business intelligence (BI) is a technology-driven process for analyzing data and presenting actionable information to help executives, managers and other corporate end users make informed business decisions.

# What is Data Warehouse?

A data warehousing is a technique for collecting and managing data from varied sources to provide meaningful business insights.

 - **Central repository**: populated from operational databases and external data sources.
 - **Transformed**:Many transformations to clean, standardize, and integrate.
 - **Summarized**: Summary data for optimizing reporting.
 
# Source Platform and Format of Data

 - **Sources**: ERP, Ticket and Change management system, point of sale, legacy system, unstructured data
- **Format** (Type of Data): Relational, Hierarchical, Columnar, Multi-dimensional, Big data MapReduce Databases, Unstructured text data
- **Platform**: IBM, Oracle, Microsoft, Sybase, SAS.

# BI Services Components

- **Integration services**: Extract, Transform, and Load (ETL), Enterprise Application Integration EII, Operational data feeds (ODS)
- **Data Management services**: Data warehouse, OLAP,
- **Reporting and Analytical Services**: A collection of tools for manipulating, mining, analyzing the data in the data warehouse, and unstructured text data,  business performance management dashboards/scorecards.
- **Information Delivery and Consumption Services**:  (Web portals, subscription, direct user access, internal portals.

# BI Applications

**Strategic**

- Helps executives assess progress in achieving long-term.
- Helps identify Enterprise-wide goals such as increased revenue, market share, reduced costs, better customer retention and improved profitability.
- For example:
Strategic dashboards can reflect enterprise-wide strategic goals, as well as corresponding KPIs.

**Tactical**
 - Focus on analyzing short-term initiatives within specific domains, such as marketing, sales, purchasing or customer service.
 - Helping sales managers optimize their region-wide campaigns is an example of this type of BI application.
- For example:
Tactical (also called analytical) dashboards measure the business’s progress according to related trends, in accordance with each strategic initiative. Progress is measured against a preset goal, such as a budget or a certain target.
 - Drilldowns reveal details and break down data for analysis
 - For example, they help determine why certain targets were not met and where a potential problem might be.

**Operational**
- Focuses on process-centric solutions for monitoring and optimizing specific business processes, such as call center operations, loan processing i.e. day to day bussiness tasks.
- Operational dashboards monitor specific business processes, such as order processing and shipping.
- They are mainly used at the departmental level, where operations take place.
- Updates are tracked daily or weekly using real time charts and reports, and detailed data is presented with strong analytical functionality in order to perform a root-cause analysis.

**Root-Cause Analysis**
Root cause analysis (RCA) is a systematic process for identifying “root causes” of problems or events and an approach for responding to them.
 

# What is Data Mart?
A data mart is a simple section of the data warehouse that delivers a single functional data set.Data marts might exist for the major lines of business, but other marts could be designed for specific products.

A data mart is a subset of the data warehouse. It specially designed for a particular line of business, such as sales, finance, sales or finance. In an independent data mart, data can collect directly from sources.

# Data Warhouse Characteristic
- **Integrated**: The way data is extracted and transformed is uniform, regardless of the original source.
- **Time-variant**: Data is organized via time-periods (weekly, monthly, annually, etc.).
- **Non-volatile**: A data warehouse is not updated in real-time. It is periodically updated via the uploading
of data, protecting it from the influence of momentary change.


# Top Down Architecture:
![Top Down](http://dwgeek.com/wp-content/uploads/2016/09/Data-Warehouse-Design-Approaches-Top-Down.jpg)

- Data is extracted from the various source systems. The extracts are loaded and validated in the stage area. Validation is required to make sure the extracted data is accurate and correct. You can use the ETL tools or approach to extract and push to the data warehouse.
- Data is extracted from the data warehouse in regular basis in stage area. At this step, you will apply various aggregation, summerization techniques on extracted data and loaded back to the data warehouse.
- Once the aggregation and summerization is completed, various data marts extract that data and apply the some more transformation to make the data structure as defined by the data marts.

# Bottom Up Architecture:

![Bottom Up](http://dwgeek.com/wp-content/uploads/2016/09/Data-Warehouse-Design-Approaches-Bottom-Up.jpg)

- As per this method, data marts are first created to provide the reporting and analytics capability for specific business process, later with these data marts enterprise data warehouse is created.

# Federated Architecture
![Federated Architecture](http://www.zentut.com/wp-content/uploads/2012/10/rf-fdw.jpg)

- A federated data warehouse is a practical approach to achieving the “single version of the truth” across the organization. The federated data warehouse is used to integrate key business measures and dimensions.


# Olap
- OLAP is a category of software that allows users to analyze information from multiple database systems at the same time. It is a technology that enables analysts to extract and view business data from different points of view. OLAP stands for Online Analytical Processing.

- Enables users to gain insight into multi-dimensional data cube structure through fast, consistent, and interactive access.

# Olap Operations
[Read About Olap Operations](https://www.guru99.com/online-analytical-processing.html)

# Aggregation Properties
- Additive
- Semi-Additive
 - Non-Additive
 
[View Here](https://www.youtube.com/watch?v=RRCq3Jgd5Zk)


# MDX query Basics
[View Here](https://www.youtube.com/watch?v=tlAcR0mqWYQ)






  
 
