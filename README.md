# Azure-Learning-Journey
## Day 1 - [01/23/2024]
## Explore core data concepts   
Options for representing and storing data, and about typical data workloads.   
### 1. Identify common data formats
- We can classify data as structured, semi-structured, or unstructured.   
  #### A. Structured Data
        Fixed Schema, Mostly Tabular data.
  #### B. Semi-Structured Data
        Information that has some structure, with some variation allowed, Eg: JavaScript Object Notation (JSON).
  #### C. Unstructured Data
        Not all data is structured or even semi-structured. Eg: documents, images, audio and video data, and binary files.
- There are two broad categories of data store in common use:    
  File stores   
  Databases
### 2. Explore file storage    
Local file systems: Hard disk of personal computer, and on removable media such as USB drives.    
Centralized File storage: Shared, Hosted in the cloud, cost-effective, secure, reliable, can store large volumes of data.   
- File Format Considerations:    
  - Type of data: Structured, semi-structured, or unstructured.    
  - Applications and services: Requirements for reading, writing, and processing.    
  - Human readability: Importance of readability.    
  - Optimization: Considerations for storage and processing efficiency.
- Common File Formats:    
  - **Delimited Text Files:**
       **Format:** Plain text with field delimiters and row terminators.    
      **Common Types:**   
          CSV (Comma-Separated Values)    
          TSV (Tab-Separated Values)    
          Space-Delimited    
          Fixed-Width Data    
      **Structure:** Fields separated by commas, rows terminated by carriage return/new line.
  -   **JavaScript Object Notation (JSON):**
       Definition: Hierarchical document schema.       
       Entities: Data entities (objects) with multiple attributes.      
       Flexibility: Suitable for structured and semi-structured data.
       Objects are enclosed in braces ({..}) and collections are enclosed in square brackets ([..]). Attributes are represented by name : value pairs and separated by commas (,).
## Day 2 - [01/24/2024]
  -   **Extensible Markup Language (XML):**    
        Type: Human-readable data format.Superseded by: JSON (less verbose).    
        Usage: Still used in some systems for data representation.    
  -  **Binary Large Object (BLOB):**    
       Definition: Files stored as raw binary data.    
       All files are ultimately stored as binary data (1's and 0's).    
       Unlike human-readable formats, bytes of binary data are not mapped to printable characters.    
       Common for unstructured data types that require interpretation by applications.    
  -  **Optimized file formats:**    
       Specialized for compression, indexing, efficient storage, and processing.   
       **Common Formats:**           
        **Avro:**
       
          Type: Row-based format.   
          Header: Describes data structure stored in JSON.   
          Storage: Binary information.   
          Use Cases: Efficient compression, minimized storage, and network bandwidth.   
        **ORC (Optimized Row Columnar Format):**   
        
          Organization: Columns rather than rows.   
          Development: HortonWorks for Apache Hive.   
          Structure: Stripes of data with column-wise organization.   
          Footer: Holds statistical information for each column.   
        **Parquet:**     
        
          Type: Columnar data format.   
          Development: Cloudera and Twitter.   
          Organization: Row groups with column-wise storage.   
          Efficiency: Specializes in storing and processing nested data types efficiently.   
          Features: Supports efficient compression and encoding schemes.   
  -  
  -  




  
  
