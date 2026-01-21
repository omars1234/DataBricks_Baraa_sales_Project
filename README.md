
## *Simple DataBricks Project*

#### *Architecture*  
*This project follows the Medallion Architecture:*

A. Bronze Layer:  
- Raw data ingestion  
- Schema inference and storage as Delta tables  

B. Silver Layer:  
- Data cleaning and standardization  
- Type casting and validation  

C. Gold Layer:  
- Dimensional Data Model (Business Transformation)  
- Ready for BI and analysis  