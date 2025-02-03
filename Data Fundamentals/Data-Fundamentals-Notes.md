# Fundamentals of the Data-Driven Enterprise

## Objectives
- Understand what makes a data-driven culture
- Understand the fundamentals of data
- Identify standards and engineering best practices

## Key Concepts
- Data-driven culture  
- Data types

### What Makes a Data-Driven Culture?

**First Steps**
- Build relationships
- Choose transparency in algorithms
- Celebrate and embrace small wins
- Raise data literacy

### The Characteristics of Data

**The 5 Vs of Data**  
**Volume** - The amount of data  
**Variety** - The different types and sources  
**Velocity** - The speed at which it is generated, collected, and processed  
**Veracity** - The reliability and accuracy  
**Value** - The insights and benefits we can get from it  

### Big Data vs Small Data
Big data has a larger volume typically with more variety, and streams in faster.  
Small data typically has higher data quality as it is more manageable and easier to clean.  
Small data often delivers immediate value through straightforward analysis compared to the advanced analytics and predictive modeling of big data.  

### Data Types

**Qualitative** - Anything that cannot be described as a number
  - Binomial - One of two values, e.g., Yes/No, 0/1
  - Nominal - Named data, e.g., UK, USA, France or Green, Yellow, Red
  - Ordinal - Has an order, e.g., Small, Medium, Large or Poor, Average, Good
    
**Quantitative** - Anything that can be described as a number
  - Discrete - Data that is usually counted, e.g., chairs in an office or people in a town
  - Continuous - Data that is measured, e.g., weight, height, or distance

### Engineering Best Practices

**GDPR** - The European regulation governing data privacy and consent  
**ISO27001** - The international standard that provides guidelines and best practices for establishing, implementing, maintaining, and continuously improving an Information Security Management System (ISMS)

**Data Stewardship**  
- Data quality - Ensuring accuracy and reliability for informed decision-making
- Data governance - Establishing policies for managing data assets throughout their lifecycle  
- Data ethics - Adhering to ethical guidelines for responsible data usage

Products must be scalable, reliable, secure, performance-optimized, and documented.

# Introduction to Data Quality

## Objectives
- Recognize the core metrics in data engineering essential for ensuring data quality

## Key Concepts
- Importance of data quality
- Importance of data standards
- Importance of following best practices, guidelines, and regulations
- Data testing methodologies
  
**Data quality dimensions/metrics**

| Data quality metric | Alternative names | Answers the questions |
|---------------------|-------------------|-----------------------|
| Accuracy            | Correctness, Validity | How well does our data reflect the real world? Are false items likely? |
| Integrity           | Completeness      | How well does our data cover the real world? Are missing items likely? |
| Consistency         | Uniformity        | How well does our data conform to a single standard? Are discrepancies likely? |
| Timeliness          | Recency, Availability | How up-to-date is our data? Are stale items likely? |

**The reliability metric** - How trustworthy and dependable data is over time and across different use cases

**Open standards** are guidelines for technology that anyone can use and contribute to. They offer:
- Compatibility
- Flexibility
- Innovation
- Cost-effectiveness

**FAIR data standard**  
**F**indable  
**A**ccessible  
**I**nteroperable  
**R**eusable  

**Dublin Core Metadata Initiative (DCMI)** offers a set of metadata standards used to describe resources in various domains. Its core elements provide a basic framework for describing digital resources such as documents, images, videos, and web pages  

**Structured data** - Data that is easily converted into a form usable for data analysis.  

It has the following properties:  
- May reside in relational databases
- Predefined and formatted to a given structure
- Highly organized
- Easy to scale
- Easy to access
- Easy to store
- Examples of structured data: Excel Spreadsheet.

**Unstructured data** - More complex data and is possibly stored in a format that is not easily decoded.

It has the following properties:  
- Any data not residing in relational databases.
- They have internal structures (bits)
- Stored in data warehouses/lakes
- Requires significant storage options compared to structured data
- Requires additional pre-processing before analysis
- Examples of sources of unstructured data: Audio, Social media, Images

**Semi-structured data** - Textual data files with a discernible pattern that allows them to be parsed easily. Examples include XMLs and JSONs.  

**Data policies** are formalized guidelines and procedures that govern how data is collected, managed, used, and protected within an organization. 

**Automated validation tools** help organizations identify anomalies and inconsistencies in their data.  
Benefits include - Real-time anomaly detection, proactive quality assurance, timely corrections.  

**Data profiling** involves examining the structure, content, and quality characteristics of data to identify errors, inconsistencies, and patterns contributing to data quality issues.  

**Data lineage** - The lifecycle of data, encompassing its origin, usage, and movement over time.  

**Unique identifiers (UIDs)** are codes or numbers assigned to individual data records to distinguish them from others, think PK in table.  

**Universally Unique Identifiers (UUIDs)** are standardized and globally unique across different systems.  

### Data Testing Methodologies

**Horizontal testing** is a fundamental data quality testing methodology that focuses on ensuring data consistency and integrity across multiple data sources.  

**Historical analysis** plays a vital role in data quality management by enabling organizations to track changes in data quality over time.  

**Rule-based testing** is an essential component of data quality assurance, involving the validation of data against predefined rules or criteria.  

**Statistical testing** techniques help assess the reliability and quality of datasets by detecting deviations from expected patterns or distributions.
