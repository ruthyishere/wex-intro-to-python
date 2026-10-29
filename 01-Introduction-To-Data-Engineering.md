# Introduction to Data Engineering

### Welcome to Introduction to Data Engineering. 

The course aims to prepare individuals for a Junior Data Engineer role, providing foundational knowledge for a career in data engineering. 

The job of a data engineer hinges on the accuracy of data and the efficiency with which we're able to access the data we need, when we need it. 

Data is growing at an exponential rate and is pivotal to guide decisions acorss various sectors globally.

## Module 1 - What is Data Engineering?

### Modern Data Ecosystem


“The constant increase in data processing speeds and bandwidth, the nonstop invention of new tools for creating, sharing, and consuming data, and the steady addition of new data creators and consumers around the world, ensure that data growth continues unabated. Data begets more data in a constant virtuous cycle.” - Forbes 2020 report ["6 Predictions About Data In 2020 And The Coming Decade"](https://www.forbes.com/sites/gilpress/2020/01/06/6-predictions-about-data-in-2020-and-the-coming-decade/)

A modern data ecosystem is a network of many different parts that work together to collect, store, process, and use data. It is always changing and growing as new technologies and tools are invented.

#### Data Sources
Data can come from many places and in many forms:
- Structured data (like tables in databases)
- Unstructured data (like text, images, videos, social media posts)
- Clickstreams, user conversations, IoT (Internet of Things) devices, real-time events, legacy databases, and data from professional providers

The first step is to copy the data you need from these sources into a central data repository. At this stage, you need to:
- Understand the data formats and where the data comes from
- Use the right tools and interfaces to collect the data
- Make sure the data is reliable, secure, and its integrity is maintained

#### Organizing and Preparing Data
Once the raw data is collected, it must be:
- Organized and cleaned up so it is easy to use
- Optimized for fast and secure access by users
- Made to follow rules and standards set by the organization (for example, privacy laws for personal data, or using master data tables for consistency)

Challenges here include making sure the data is always available, flexible, accessible, and secure.

#### Using Data
Different people and applications use the data in different ways:
- Data analysts may need raw data for analysis
- Business stakeholders may want reports and dashboards
- Applications may need custom APIs to access data

The main challenge is to provide the right interfaces and tools so everyone can get the data they need, in the format they need.

#### Technologies Shaping the Data Ecosystem
New technologies are making the data ecosystem more powerful:
- **Cloud Computing**: Gives access to unlimited storage and high-speed computing
- **Machine Learning**: Lets us find patterns and make predictions from data
- **Big Data**: Helps us work with huge and complex datasets that traditional tools can't handle

These technologies allow organizations to store more data, analyse it faster, and gain new insights to make better decisions.

### Key Players in the Data Ecosystem

Organisations that are using data to uncover opportunities and are applying that knowledge to differentiate themselves are the ones leading into the future. To get value from data, you need a vast number of skillsets and people playing different roles that tap into vast amounts of data and turn them into actionable insights. 

Data engineers develop and maintain data architectures and make data available for business operations and analysis. They work within the data ecosystem to extract, integrate, and organise data from disparate sources. They clean, transform, and prepare data; design, store, and manage data in data repositories. They enable data to be accessible in formats and systems that the various business applications and users can utilize. A Data Engineer must have good knowledge of programming, sound knowledge of systems and technology architectures, and in-depth understanding of relational databases and non-relational datastores.

Data Analysts translate data and numbers into plain language, so organisations can make decisions. Data Analysts inspect, and clean data for deriving insights; identify correlations, find patterns, and apply statistical methods to analyse and mine data; and visualise data to interpret and present their findings.

Data scientists analyse data for actionable insights and build Machine Learning or Deep Learning models that train on past data. Require knowledge of Mathematics, Statistics, and a fair understanding of programming languages, databases, and building data models. 

Business Analysts leverage the work of Data Analysts and Data Scientists to look at possible implications for their business and the actions they need to take or recommend. BI Analysts do the same, except their focus is on the market forces and external influences that shape their business.

- Data Engineering converts raw data into usable data. 
- Data Analytics uses this data to generate insights. 
- Data Scientists use machine learning to predict the future using data from the past. 
- Business Analysts and Business Intelligence Analysts use these insights and predictions to drive decisions that benefit and grow their business.

### Specialisations in Data Engineering

#### Data Warehouse Engineer: The Builder of Data Pipelines
- Designs, builds, and maintains data warehouses (large storage systems for data)
- Develops ETL (Extract, Transform, Load) processes to move and clean data for efficient integration
- Implements data lakes for storing unstructured data (like images, text, etc.)
- Helps organisations store and process many types of data
- Uses tools like Apache Kafka, Spark, and cloud data warehouses
- Works with data architects, database administrators (DBAs), and business intelligence (BI) analysts
- Supports data accessibility for analytics and reporting

**Healthcare Example:**
- Designs and maintains the data warehouse for patient records
- Ensures efficient storage and retrieval of patient information
- Develops ETL processes for structured data storage
- Ensures secure and efficient data access for analytics

#### Data Architect: The System Designer
- Designs the overall structure of data systems (how data is stored, connected, and accessed)
- Defines strategies for data integration, governance, and security
- Establishes methods for organising data (schema, indexing, partitioning)
- Models data relationships and designs scalable solutions
- Plans for disaster recovery and future growth
- Uses tools like ERD (Entity Relationship Diagram) tools, MySQL, MongoDB, and cloud platforms
- Engages with engineers, DBAs, and business leaders
- Ensures scalable and adaptable data management

**Healthcare Example:**
- Develops a scalable framework to store patient records
- Designs indexing strategies for quick searches
- Plans for future system expansion and integration

#### Data Manager: The Strategic Overseer
- Focuses on the organisation's data governance and strategy
- Ensures data quality, compliance, and accessibility
- Develops frameworks for managing data (data governance)
- Defines who can access data (access control policies)
- Fosters collaboration between departments to align data usage
- Promotes a culture of data literacy (helping people understand and use data)
- Uses data governance platforms
- Works with business and technical teams
- Aligns data with business goals

**Healthcare Example:**
- Ensures compliance with healthcare regulations
- Oversees data quality assurance processes
- Collaborates with medical researchers
- Aligns IT operations with operational goals

#### Database Administrator (DBA): The Operational Gatekeeper
- Manages the day-to-day operations of databases
- Conducts routine backups and optimizes performance
- Manages patches to address security concerns
- Monitors database activity and implements encryption protocols
- Maintains audit logs for security
- Uses SQL and database monitoring tools
- Partners with engineers and architects
- Maintains data reliability and security

**Healthcare Example:**
- Maintains the seamless operation of the electronic health record (EHR) system
- Performs regular database backups
- Identifies and resolves performance issues
- Manages user access to protect sensitive data
- Implements disaster recovery measures

#### Summary Table
![Summary of key roles in Data Engineering](img/01-1.png)

### What is Data Engineering?

Data engineering focusses on the flow and acces of data. The goal is to make quality dat aavailable for fact-finding and data-driven decision making. tasks include collecting, processing, storing and making data available securely.

#### Collecting Required Data
- Develop tools, worklflows and processes for acquiring data from multiple sources.
- Design and maintain scalable data archiecture for storage.

#### Processing Data
- Implement and maintain distributed systems for large-scale data processing
- Design pipelines for data extraction, transformation and loading.
- Ensure data quality, privacy, security, compliance and optimise performance.

#### Storing Data
- Architect or implement data stores for storing processed data.
- Ensure scalability and omplement tools/systems for privacy, security, compliance and recovery.

#### Making Data Available
- Use APIs, services and interfaces to retrieve and present data for user insights.
- Implement security measures for access control and data integrity.

### Viewpoints: Defining Data Engineering 

Data engineering is all about designing, building, and maintaining the systems that help organisations manage their data. These systems include databases, big data repositories, and data pipelines that move and transform data so it can be used by others.

**What does a Data Engineer do?**
- Develops and optimises data systems to make data available for analysis
- Makes sure data is highly available, consistent, secure, and recoverable
- Focuses on preparing data for others (like analysts and data scientists) to use
- Works closely with other data professionals to ensure data meets their needs

**How is Data Engineering different from Data Analytics and Data Science?**
- Data Engineers build and maintain the infrastructure and tools that store and move data
- Data Analysts use the data to find insights and create reports
- Data Scientists use the data to build models and make predictions

Think of Data Engineers as the plumbers of data—they make sure the data flows smoothly and is ready for others to use. Data engineering is the foundation that enables data analytics and data science to happen.

**In summary:**
- Data engineering comes first: it collects, transforms, and stores raw data
- Data analysts and data scientists use this prepared data to generate insights and predictions
- Data engineers also help choose the right databases, storage systems, and cloud platforms so data can be delivered quickly and easily to those who need it

### Viewpoints: Evolution of Data Engineering 

Data engineering has changed dramatically over the past 20 years. What data engineers do today is very different from what they did two decades ago.

**Major Changes in Data Engineering:**

1. **Quantity and Variety of Data**
   - Twenty years ago, the amount of data was much smaller
   - Today, we handle massive amounts of data in many different formats
   - New types of data sources exist now that didn't exist before (like social media, IoT sensors, real-time streams)

2. **From Relational to Diverse Databases**
   - Two decades ago: mostly relational databases and data warehouses
   - Today: many types of databases including NoSQL, column stores (like Cassandra), key-value stores, document stores (like MongoDB), and Big Data systems (like Hadoop)

3. **Cloud Computing Revolution**
   - Data infrastructure is now available as a service in the cloud
   - Data engineers spend less time setting up systems from scratch
   - More time can be spent on solving actual data problems

4. **Speed and Automation**
   - Before: solutions could take days to develop
   - Now: organisations expect solutions within hours
   - Automation tools are essential to deliver services quickly

5. **Big Data**
   - Twenty years ago, Big Data didn't exist
   - Today, it's a standard part of many organisations
   - Data engineers must know how to work with Big Data systems and pipelines

6. **Shift in Decision-Making**
   - Before: a top-down approach where architects decided how to store data (usually 2-3 supported platforms)
   - Now: developers often drive requirements for how data should be stored
   - Data engineers must learn new technologies and work collaboratively with developers

7. **Expanded Skillset Requirements**
   - Traditional focus: database management, ETL pipelines, data visualisation
   - Modern requirements: distributed computing, DevOps, machine learning implementation
   - Data engineers need to know a wider variety of tools and systems

**Why These Changes Happened:**
- The internet and connected devices generate more data
- New data sources like IoT, APIs (Twitter, weather data, etc.), and social media
- Organisations need faster insights to stay competitive
- Technology has advanced to handle more complex data challenges

**The Bottom Line:**
Data engineering has evolved from a specialised role focused on a few database platforms to a dynamic field requiring knowledge of many different systems, faster delivery times, and close collaboration with other teams.

### Responsibilities and Skillsets of a Data Engineer
The diverse responsibilities and skillsets necessary for a data engineer, stressing the need for a balance between specialisation and broad understanding to effectively contribute to the field.

Responsibilities of a Data Engineer:
- Providing analytics-ready data to data consumers.
- Ensuring data accuracy, reliability, compliance, and accessibility.

Key Responsibilities at a Broad Level:
- Extracting, organising, and integrating data from diverse sources.
- Preparing data for analysis by transforming and cleansing it.
- Designing and managing data pipelines from source to destination systems.
- Setting up and managing infrastructure for data ingestion, processing, and storage.

Technical Skills Required for Data Engineers:
- Operating system proficiency (UNIX, Linux, Windows) and administrative tools.
- Knowledge of infrastructure components like virtual machines, networking, and application services.
- Familiarity with cloud-based services (Amazon, Google, IBM, Microsoft).
- Experience with databases (RDBMS, NoSQL, data warehouses) and data pipeline tools.
- Proficiency in querying languages, programming languages (Python, R, Java), and scripting languages.
- Understanding and familiarity with Big Data processing tools.

Understanding of Tools and Technologies:
- Ability to assess different tools and make recommendations based on trade-offs.

Intersection of Software Engineering and Data Science:
- Data engineers need to understand how data scientists, analysts, and business users utilise analysis-ready data.

Functional Skills Required:
- Ability to translate business requirements into technical specifications.
- Proficiency across the software development lifecycle.
- Understanding of data's business applications and risks associated with poor data management (data quality, privacy, security, compliance).

Collaboration and Interpersonal Skills:
- Data engineering involves teamwork and collaboration among data engineers and various stakeholders.
- Effective communication with both technical and non-technical stakeholders is crucial.

Continuous Learning and Specialisation:
- Acknowledgment that no single data engineer can master all required skills.
- Need for specialisation while maintaining a good understanding of other areas for informed decision-making.
- Emphasis on skill growth through experience, focus areas, and continuous upskilling.

### Viewpoints: Skills and Qualities to be a Data Engineer

To be a successful data engineer, you need a combination of technical skills and personal qualities. The specific skills you need may vary depending on the industry (retail, healthcare, social media, etc.), but there are core skills and qualities that all data engineers should have.

**Essential Technical Skills:**

1. **Programming Languages**
   - Python, Java, or C
   - Programming knowledge is very valuable for data engineering work

2. **SQL and Data Modeling**
   - Must be very proficient at SQL (querying databases)
   - Understanding how to organize and structure data

3. **Databases**
   - Knowledge of both relational databases (RDBMS) and NoSQL databases
   - Understanding when to use each type

4. **Operating Systems**
   - Proficiency with UNIX, Linux, and Windows
   - Understanding administrative tools

5. **Networking and Storage**
   - Good understanding of LAN (local networks) and WAN (wide area networks)
   - Knowledge of local storage and cloud storage

6. **IT Infrastructure**
   - Understanding of cloud services, virtual machines, containers
   - Knowledge of how different storage systems work

7. **ETL Methodologies**
   - Understanding Extract, Transform, Load processes
   - Building data pipelines

8. **Automation**
   - Automation skills are very valuable in today's data engineering landscape
   - Helps deliver work faster and more reliably

9. **Big Data Ecosystem** (helpful but not required to start)
   - Data warehouses, data lakes, Big Data systems
   - Tools like Kafka Streams, Cassandra, Google BigTable

**Important Soft Skills and Qualities:**

1. **Love for Learning**
   - Data engineering is constantly changing
   - You must enjoy learning new technologies
   - If you don't enjoy change, data engineering is not for you

2. **Problem-Solving and Troubleshooting**
   - Must enjoy solving problems
   - Need to think logically and debug issues

3. **Communication Skills**
   - Must communicate well with both technical and non-technical people
   - Need to explain your choices to management
   - Work with developers, business users, and other teams

4. **Curiosity**
   - Ask lots of questions to understand business and technical needs
   - Use answers to build better data solutions

5. **Detail-Oriented**
   - Pay close attention to details
   - Make sure nothing is overlooked
   - "Don't leave any boxes unchecked"

6. **Teamwork and Collaboration**
   - Data engineering involves constant collaboration with multiple teams
   - Work well with others

7. **Control and Awareness**
   - Be aware of choices being made in your data environment
   - Understand the tradeoffs of different technical decisions
   - Advocate for good practices

8. **Passion and Work Ethic**
   - Show dedication to your work
   - Care about the quality of your data systems

**Key Insight:**
The most important skills are the soft skills—communication, curiosity, and eagerness to learn. Technical skills can be learned, but having the right mindset and personal qualities is what makes you successful in the long run.

**Remember:**
Different jobs and industries require different technical skills, so you need to be flexible and willing to learn what's needed for each situation. The basic theory of data structures and working with data is more important than knowing every specific tool.

### Day in the Life of a Data Engineer

Let's follow Sarah Flinch, a data engineer at a multinational hair care company, as she works on a real project.

**The Business Problem:**
Sarah's company is launching a new shampoo and wants to track what customers say about it on social media from day one. They want to know:
- What people are saying on Twitter, Facebook, Instagram, eCommerce sites, and blogs
- Whether the feedback is positive, negative, or includes suggestions
- How different customer groups feel about the product

**Step 1: Creating a Prototype**
The data science team created a prototype dashboard using dummy (fake) data. The dashboard showed:
- Graphs of customer sentiments (feelings) as scores
- Information organized by social media source and customer demographics
- The business team loved it and approved it for real implementation

**Step 2: Data Collection (Sarah's First Task)**
Sarah needed to collect real data from multiple sources:
- Used **APIs** to pull tweets and posts with the product's hashtag into temporary storage
- Used **web scraping** to collect data from eCommerce sites and product review blogs
- The data came in many formats: tweets, posts, comments, articles, even memes

**Step 3: Data Inspection and Planning**
Sarah examined all the collected data to figure out:
- What transformations (changes) were needed
- How to clean up the messy data
- How to prepare it for the database

**Step 4: Data Processing and Loading**
- Created a **Python program** to process the data
- Cleaned up the data (removed errors, fixed formatting)
- Transformed it into a format that could be stored in the database
- Loaded it into the database that the dashboard uses to display reports

**Step 5: Testing and Validation**
- Showed the results to the data scientists
- They confirmed it was exactly what they needed
- Success!

**Step 6: Automation (Making it Better)**
The first solution worked, but had a problem:
- Every time business users wanted updated statistics, they had to ask the data team to manually pull new data
- This was inefficient and slow

**The Better Solution:**
- Build a **data pipeline** that automatically extracts, transforms, and loads data on an ongoing basis
- This allows business teams to see **real-time** customer sentiment whenever they log into the dashboard
- No more manual requests needed!

**Key Takeaways:**
This example shows what data engineers do every day:
1. **Collect data** from multiple sources (social media, websites, etc.)
2. **Clean and transform** messy data into usable formats
3. **Load data** into databases for others to use
4. **Build automated pipelines** so data updates continuously
5. **Collaborate** with data scientists and business teams
6. **Solve real business problems** by making data accessible and useful

This is the ETL (Extract, Transform, Load) process in action—the core work of a data engineer!

## Module 2 - The Data Engineering Ecosystem

### Overview of the Data Engineering Ecosystem (!)
Ecosystem includes:
- extracting data from disparate sources;
- archiecting and managing data pipelines, which integrate, transform and place data into storage;
- architecting/managing data repositories/storage;
- automating and optimising flow of data between system and other workflows;
- developing any applications needed for the DE workflow.

| Structure of data                                                                                                                 ||
|-----------------|-----------------------------------------------------------------------------------------------------------------|
| Structured      | Organised into rows and columns; seen in relational databases and spreadsheets, CSV                             |
| Semi-structured | Has some structure but doesn't follow a rigit format, mix of consustent characteristics with some unstructured elements e.g. email contains name and recipient (structure) but also text (unstructured); JSON; XML                                            |
| Unstructured    | Complex, qualitative information difficult to organise into a neat structure e.g. photos, video, audio, social media content                                                                                                                             |

Data comes in a diverse range of file formats, from relational to non-relational databases, APIs, web servuces, data streams, social media platforms, IoT sensor devices. These influence types of data repositories/stores and tools used to collate, process and query data.

Transactional Systems (OLTP --> Online Transactional Processing) - store hugh volume day-to-day operational data e.g. airline bookings or online banking transactions; typically relational but can be non-relational.  
Analytical Systems (OLAP --> Online Analytical Processing) - for complex data analytics over large datasets; includes relational + nonrelational DBs but also data warehouses, lakes and other data archiecture.
Type, sources of data and context of use influence which repository is ideal.

Data flow example:
Collated --> Processed/cleansed --> integrated --> Accessed via single interface by users.

Integration rools combine data form disparate sources into a unified view/repository for unified querying and manipulation of data.

Data pipeline - a set of tools and prcesses that cover the entire journey from data source to destination; employs ETL/ELT processes. 

Query languages (e.g., SQL), programming languages (e.g., Python), shell and scripting languages are vital for data manipulation, development, and operational tasks.

BI (business intelligence) and reporting tools present data visually through interactive dashboards; we can connect to and visualise the data in (near) real-time and on a pre-defined schedule.


### Types of Data (!)
Data - unorganised information processed to make it meaningful. Comprised of facts, observations, perceptions, numbers. characters, symbols, images, videos, audio etc. that can be interpreted to derive meaning.

Data is categorised by its structure:\
**Structured Data:**
- Has a well-defined structure
- Can be stored in well-defined schemas e.g. databases
- Can be represented in a tabular manner\
Sources of structured data: SQL databases, OLTP systems (e.g. business transctions), Spreadsheets, Online forms, Sensors (GPS, RFID tags), Network and web logs.

**Semi-structured:**
- some organisational properties but lacks a fized schema
- cannot be stored in tabular format in databases
- Contains tags and elements (metadata) used to group data and organise it in a hierarchy.\
Sources: emails, XML, JSON, binary executables, tcp/ip packages, zipped files.\
XML/JSON - define tags and attributes to store data in hierarchical format and used to store and exchange semi-structured data.

**Unstructured data:**
- doesn't have easily identifyable structure
- cannot be stored in a mainstream relational database in tabular format
- doesn't have a particular format, sequence, semantics or rules.\
Sources: Web pages, social media feets, images, video/audio, media logs, word documents


### Understanding Different Types of File Formats (!)
**Delimited text files**\
Text files used to store data as text in which each line/row has values separaetd by a delimiter, where a delimiter is a sequence of one or more characters for specifying the boundary between independent entities or values. Any character can be used as a delimiter, but common ones are comma (,), tab(   ), colon (:), verticle bar (|), space ( ).
CSV (comma separated values) and TSV (tab sepeated values) are most common.
Each row in the text file has values separated by delimiter and represents a record. First row usually works as a column header - each column can have a different data type.
Delimited files allow field values of any length and are considered standard format for providng straightforward information schema. Can be procesed by almost all applications.
Delimiters also represent one of many ways to specify boundaries in a data stream.

**Microsoft Excel Open XML Spreadsheet .XLSX**\
XML-based spreadsheet file format, also known as a workbook. Each workbook can have multiple worksheets, with each worksheet organised into rows and columns, at the intersection of which is the cell, which contains the data. Uses opem file format - generally accessible to most other applications. 

**Extensible Markup Language XML**\
Markup language with set rules for encoding data. Readable by humans and machines. Designed to send information over the internet. Doesn't use pre-defined tags like HTML. Platform and programming language independent -- simplifies sharing of data between various systems. 

**Portable Document Format PDF**\
Documents independent of application software, hardware and OS - it can be viewed the same way on any device.

**JavaScript Object Notation JSON**\
Text-based open standard designed for transmitting structured data over the internet. Programming langugae independent and easy to use, compatible with many browsers. Used by many APIs and Web services.



### Sources of Data (!)

Orgs have applications that support their business needs and transactions. These systems use data stored in a structured way within relational databases and data warehouses, which can be used as a source for downstream analysis. There are publically and privately available datasets external to an org. 

Some companies sell specific data which others use to help them make business decisions -- these usually come in:
- Flat files - store data in plain text format; each line/row = one record; delimiter separated; all data in flat file = one single table; e.g. CSV.
- Spreadsheets - type of flat file; organises data in a tabular format; can contain multiple worksheets where worksheet ≈ table; can include additional formatting, formulas etc.; e.g. XLSX
- XML - contain data identified or marked up using tags; can support hierarchical structures.

Application Program Interfaces (APIs) and web services which users/applications interact with to pull data from their sources for processing or analytics. APIs listen for incoming requests (web requests from users or network requests from apps) and return data in plain text, XML, HTML, JSON or media files.

Web scraping extracts data from unstructured sources; downloads specific data based on defined parameters. They extract text, imaes, videos etc. 

Data streams and feeds aggregate streams of data flowing from instruments, IoT devices and apps, GPS data from cars, computer programs, web sites and social media posts. Data generally timestamped and geo-tagged for geographical identification. RSS (Really Simple Syndication) feeds capture updated data from online forums and news sites where data is refreshed on an ongoing basis. A feed reader is an interface that converst RSS text files into a stream of updated data, which are then sent to user devices.

### Languages for Data Professionals

Query Languages - designed for accessing an dmanipulating data in a database
- SQL (Structured Query Language) is designed for accessing and manipulating data in databases, allowing operations like inserting, updating, and deleting records.
- SQL is portable, has a simple syntax, and can retrieve large amounts of data quickly, making it a popular choice among data professionals.

Programming Languages - developing applications and controling their behaviour.
- Python is a high-level, open-source language known for its simplicity and readability, making it ideal for beginners. It supports various programming paradigms and has extensive libraries for data manipulation and analysis.
   - Pandas - data cleaning and analysis
   - Numpy, Scipy - statistical analysis
   - BeautifulSoup, Scrapy - web scraping
   - Matplotlib, Seaborn - produce visual graphs and charts
   - Opency - image processing
- R is an open-source, platform-independent language focused on data analysis and visualization, offering powerful libraries for creating visualizations and handling both structured and unstructured data.
- Java is an object-oriented, platform-independent language used in various data analytics processes, including data cleaning and visualization. Java is foundational for many big data frameworks like Hadoop and Spark.

Shell and Scripting Languages - repetative operational tasks.
- Unix/Linux Shell scripts automate repetitive tasks and are useful for file manipulation and system administration.
- PowerShell is a cross-platform tool by Microsoft for working with structured data formats, allowing for automation and data manipulation in various environments.

### Viewpoints: Working with Varied Data Sources and Types

Data Sources and Types

- Data professionals often work with relational databases, utilizing SQL for data movement, structuring, and security.
- The challenges of moving data between different relational databases include versioning issues and the need for flexibility in solutions.

Evolution of Data Formats

- The rise of unstructured data (e.g., logs, documents) has led to the popularity of NoSQL databases like Cassandra and HBase, which address limitations of relational databases in handling heavy write-intensive applications.
- Different data formats (CSV, JSON, XML) present unique challenges, with JSON becoming preferred due to its efficiency over XML.

Working with Diverse Data

- Data engineers must adapt to various data formats and sources, including proprietary formats, and learn new skills as needed.
- Specific challenges arise from data characteristics, such as using appropriate delimiters for data separation, especially when special characters are involved.

### Metadata and Metadata Management (!)

Metadata is data that provides insightful information about other data.

**Technical metadata**
- Provides information about and defines the data structures in data repositories/platforms. 
- For example, technical metadata in a datawarehouse could include tables that record information about tables in a database such as each table's name, number of rows and columns.
- A data catalog is an inventory of tables that contain the name of each database in the DW, name of each column in the database, names of every table that each column is contained in, types of data that each column contains.
- The system catalog is a component of the DBMS that stores all this technical metadata.

**Process Metadata**
- Describes the operations and processes that operate behind business systems and tools. It descriibes the steps taken to collect and process the data.
- Contains information that help with moniotring critical systems for failures and performance anomalies.
- Contains things like process start and end times, disk usage, where data has moved from/to, how many users are accessing the system at a given time.
- Vital for troubleshooting and optimisation.

**Business Metadata**
- Some users engage in data discovery to find data in their business which is meaningful and valuable to them and to know where that data can be access from.
- Business metadata is information about the data described in readily interpretable ways, such as how the data is acquired, what it is measuring/describing and the connection between the data and other sources.
- Serves as documentation for DW system.


Good metadata management ensures information can be accessed and integrated from various sources and appropriately shared across the entire org. It helps users understand the business context associated with the enterprise data. For example, a web based server interface for allowing users to easily search for information on key table attributes e.g. CustomerName.

A good, user-friendly data catalog serves as the main asset for metadata management, helping it with the inventory and organisation of their data systems. This greatly enhances data discovery, repeatability, governance and can also facilitate access to data. 

Data lineage provides information about the origin of the data and how it gets transformed and moved, facilitating the tracing of data errors back to their root cause. 

Data governance enables an org to ensure that high data quality exists throughout the complete lifecycle of the data, and data controls are implemented that support business objectives. Key focus areas - availability, usability, consistency, data integrity and data security. Orgs need to establish processes to ensure effective data management such as accountability for poor data quality and ensuring data discoverability and democracy. 


### Overview of Data Repositories (!)

Data repository - a general term used for data that has been collected, organised and isolated. 
- Database - collection of data/information designed for the input, storage, search, retrieval and modification of data. 
   - A DBMS is a set of programs that creates and maintains the database, allowing for the storage, modification and extraction of information from the database via querying.
   - Choise of database depends on: data type and structure, querying mechanisms, latency requirements, transaction speeds and intended use of the data.
   - Relational database (RDBMS) - data organised into a tabular format, with rows & columns, and a well-defined structure/schema. Optimised for data operations and querying involving large size/number of tables.
   - Non-relational database (NoSQL) emerged in response to the vast volume, diversity and speed at which data is now being generated, influenced by cloud computing, IoT and social media. Built for flexibility, speed, scale and allows for schema-less and free-form storage of data. Used for Big Data.
- A data warehouse works as a central repository that merges data from disparate sources and consolidates it through the ETL process into one comprehensive database for analytics and BI.

   ![alt text](img/01-02.png) 
   - ETL - Extract data from disparate sources, Transform the data into a clean and usable state, and Load the data into the data repository.
   - Data marts and warehouses have historically been relational since much of the traditional enterprise data has resided in RDBMSes (e.g. SQL Server). However, with the emergence of NoSQL technologies and new sources of data, NoSQL repositories are also being used for DW. 
- Big Data stores use distributed computational and storage infrastructure to store, scale and process very large data sets.


### RDBMS (!)

A relational database is a collection of data organised into a table structure, where data can be linked, related or based on data common to each - e.g. fact tables and dimension tables. Tables are made of rows (records) and columns (attributes). The ability of relating tables based on common data enables you to retrieve an entirely new table from data in one or more tables with a single query. Allows you to understand the relationships among all available data and gain new insights for making better decisions. 
- Ideal for optimised storage, retrieval and processing of data for large volumes of data.
- Each table has a unique set of rows and columns.
- Relationships can be defined between tables (normal forms) - reduces redundancy.
- Fields can be restricted to specific data types and values - greater consistency and integrity
- Can retrieve millions of records in seconds. 
- Security architecture of relational DBs provides controlled access to data and ensures the standards and policies for governing data are enforced. 
- Ease of backup and disaster recovery.
- Offers ACID compliance - atomicity, consistency, isolation, durability; ensures accurate and reliable database transactions.

Transactions in a OLTP database are a set of actions that change data records in the database. Relational DBs are suitable for Online Transactional Processing (OLTP) applications - focussed on transaction oritented tasks that run at high rates. They can:
- Accomodate a large number of users.
- Insert, update or delete small amounts of data (transactions)
- Support frequent queries and updates as well as fast response times.

Relational DBs are suitable for 
- Data warehousing, where Online Analytical Processing (OLAP) is used for historical data analysis and BI. 
- IoT solutions - provide the speed nd ability to collect and process data from edge devices.

Relational DBs:
- Aren't suitable for semi/unstructured data.
- Migration between two RDBMSes is only possible when the source and destination tables have identical schemas and data types.
- Enyering a value greater than he defined length of a data field may result in loss of information - many RDMSs have limit on length of data fields. 

PostgreSQL, Microsoft SQL Server, Azure SQL Database, Azure SQL MI, SQL Database in Microsoft Fabric, Fabric Data Warehouse, MySQL...


### NoSQL (!)

NoSQL is a non-relational database design that provides flexible schemas for the storage and retrieval of data. 
- Gained popularity from emergence of cloud computing, big data and high volume web and mobile applications. 
- Chosen for their scale, performance, ease of use
- Has flexibile schemas that allow programmers to create and manage modern applications.
- Do not typically use traditional row/column/table databases with fixed schema -- they allow data to be stored in a schema-less or free-form fashion. Any data (structure/semi/un) can be stored in any record. 
- Has the ability to run as a distributed system across multiple data centres, enabling the use of cloud compute. 
- An efficient and cost-effective scale-out architecture that provides additional capacity ​and performance with the addition of new nodes;
- ​Simpler design, better control over availability, and improved scalability that enables you ​to be more agile, more flexible, and to iterate more quickly

Common type of NoSQL DBs:
- Key-value store - data is tored as a collection of key-value pairs
   - The key represents an attribite of data and is a unique attribute;
   - Both keys and valyes can be simple integers or strings to even complex JSON docs.
   - Great for storing user session data, user preferences, RT recommendations, targeted ads and in memory data caching. 
   - Not great for querying data on specific data values, defining relationships between data values or having multiple unique keys.
   - Redis, Memcached, DynamoDB, Azure Managed Redis, Azure CosmosDB for Table or NoSQL
- Document - store each record and associated data within a single document e.g. JSON.
   - Enable flexible indexing, powerful ad hoc queries and analytics over a collection of docs.
   - Preferred for eCommerce platforms, medical records storage, CRM platforms and analytics platforms.
   - Not suitable for complex search queries and multi-operation transactions.
   - MongoDB, DocumentDB, Azure DocumentDB CouchDB, Azure SQL DB, Azure CosmosDB for NoSQL, (Azure AI Search service)
- Column - stores data in cells grouped as columns instead of rows.
   - a logical grouping of columns that are usually accessed together are called a column family -- e.g. customer name and profile information likely stored together in col family.
   - All cells corresponding to a column are saved as a continuous disk entry, making access and search easier and faster.
   - Great for systems that require heavy write requests, storing time series data, weather data, IoT data.
   - Not suitable for complex queries, change querying patterns frequently.
   - CassandraDB, HBase, HBase on HDInsights, 
- Graph - uses a graphical model to represent and store data; useful for visualising, analysing and finding connections between pieces of data.
   - Nodes contain the data and edges represent relationships. 
   - Excellent choice for connected data, social networks, product recommendations, network diagrams, fraud detection and access management.
   - Noy suitable for high volume transactions.
   - Neo4j, CosmosDB for Gremlin.

| Relational DB | NoSQL DBs |
|---------------|-----------|
| Schemas are rigidly define how all data are to be structured and managed | Can be schema-agnostic, allowing un/semi-structured data to be stored and manipulated |
| Maintaining high-end, commercial RBDMSes can be expensive | Designed for low-cost commodity hardware |
| ACID-compliant, ensuring reliability of transactions and crash recovery | Most NoSQL DBs are not ACID complaint |
| A mature and well-documented technology, risks are perceivable | A relatively new technology |



### Data Warehouses, Data Marts and Data Lakes (!)

A data warehouse is a central repository of data integrated from multiple sources. DW serve as the single source of truth, storing current and historical data that has been cleansed, conformed and categorised. When data gets loaded into the DW, it is already modelled and structured for a specific purpose - it's analytics ready. Traditionally, DW are known to store relational data from transactional systems and operational databases (e.g. CRM, ERP, HR, finance). But it can also be used in NoSQL data repositories. \
The DW has a three-tier architecture:
- Bottom tier: database servers (relational or non-relational) that extract data from different sources
- Middle tier: OLAP server process and analyse information coming from the db servers
- Client front end tier: includes all the tools and applications for querying, reporting and analysing 

![alt text](img/01-03.png)

_A DW is "a subject-oriented, integrated, time-variant and non-volatile collection of data in support of management’s decision making process" - Bill Imnon._

Cloud based DW have lower costs, limitless storage and compute capabilities, scale on a PAYGO basis and faster disaster recovery. \
Use a DW to store and process massive amounts of data from operational systems that need to be readily available for reporting and analysis.


A data mart is a subsection of the data warehouse, built specifically for a particular business function, purpose or community of users. 
![alt text](img/01-04.png) \
Three types of DM:
- Dependent - subsection of an enterprise DW; offers analytic capabilities for a restricted area of the DW, it also provides isolated security and isolated performance. They pull data from enterprise DW where data has already been cleaned and transformed. 
- Independent - created from sources other than an enterprise DW. They need to carry out their own transformation process in the source data. 
- Hybrid - combined data from the DW and other sources such as external systems.
![alt text](img/01-05.png)

The purpose of a DM is to:
- Provide data to users that is most relevant to them when they need it.
- Accelerate business processes by providing efficient response times.
- Provide cost and time efficient way in which data-driven decisions can be taken.
- Imporve end-user response time.
- Provide secure access and control.


A data lake is a repository that stores large amounts of structured and semi-/unstructured data in their native format. Data can be loaded without defining the structure and schema of data. Exists as a repository of raw data straight from the source, to be transformed based on use case as and when needed. Data is still classified, protected and governed. Can be deployed using cloud object storage or large scale distributed systems or (non-)relational DBMS. \
Benefits include:
- Ability to store all types of data.
- Agility to scale based on storage capacity - from TB to PT of data
- Saving time in defining structures, schemas and transformations since data is imported in it's original format.
- Ability to repurpose data in several different ways and wide-ranging use cases -- it is hard for businesses to foresee all the ways in which they could potentially leverage their data.


### Data Lakehouses Explained

A data lakehouse combines the low-cost, flexible storage of a **data lake** with the high-performance analytics and structure of a **data warehouse**.

**Restaurant analogy (from lecture):**
- Raw ingredients arriving at a loading dock ≈ raw data arriving from many sources (apps, cloud systems, social media, streams).
- Storage areas (pantry/freezer) with sorting rules ≈ curated data layers with organisation, quality controls and governance.
- Cooks needing ingredients quickly ≈ analysts/BI/ML workloads needing trusted, queryable data.

**Why data lakes alone are not enough:**
- Great for cheap, scalable ingestion of structured, semi-structured and unstructured data.
- Governance and quality can become weak over time, creating a **data swamp** (duplicate, incomplete, stale data).
- Query performance for complex analytics is often limited.

**Why data warehouses alone are not enough:**
- Excellent query performance and trusted, governed data for BI/reporting.
- Can be expensive at scale; not ideal for storing everything.
- Less flexible for rapidly growing semi-structured/unstructured data.
- Batch preparation can delay access to the freshest data for some use cases.

**What a lakehouse provides:**
- Cost-effective storage for diverse and rapidly growing data sources.
- Built-in management and governance layers to improve trust and discoverability.
- Better support for both **business intelligence** and **machine learning/AI** workloads from a unified platform.
- A practical path to modernise data lakes and complement existing enterprise data warehouses.


### Viewpoints: Considerations for Choice of Data Repository

Key factors data professionals consider when selecting a data repository:

**Use Case and Data Characteristics**
- What is the repository going to be used for — storing structured, semi-structured or unstructured data?
- Is the schema known beforehand?
- Is the data at rest, streaming, or in motion?
- Does data need to be updated and accessed frequently, or stored long-term (e.g. archival/backup)?

**Performance and Volume**
- Are there specific performance requirements?
- What is the volume of data? Does it require a Big Data system?
- Is access in short intervals or via long-running queries?
- Is it used for transactional processing, analytics, archival or data warehousing?

**Storage and Security**
- What are the storage requirements?
- Does the data need to be encrypted?

**Scalability**
- Can the repository scale as the organisation grows? Performance today is not enough — future scalability matters.

**Compatibility**
- How compatible is the repository with the existing ecosystem of programming languages, tools and processes?

**Organisational Standards and Skills**
- Organisations often have preferred/approved repositories for different task types — engineers may not always get to choose freely.
- Consider the skills already available within the organisation (e.g. expertise in IBM Db2 may steer the choice to Db2).
- Consider the costs of the various solutions.

**Hosting Platform**
- The hosting platform matters — e.g. using IBM Db2 vs. Microsoft SQL Server is no longer the only decision; you must also decide whether to run it on AWS RDS, Amazon Aurora, Google Cloud, etc.

**Practical Guidance by Use Case:**
- Most cases: a relational database (IBM Db2, Oracle, PostgreSQL) is sufficient.
- High-volume ingestion (GB/TB per day): document stores like MongoDB or wide-column stores like Cassandra.
- Product recommendations or social network relationships: graph databases like Neo4j or Apache TinkerPop.
- Analytical mining of TB/PB of data: Hadoop with MapReduce.

**Summary:**
The structure of the data, the nature of the application, and the volume of data ingestion are the primary determinants when choosing a data repository. Most organisations use multiple repositories — one for enterprise relational workloads, one for open-source/smaller projects and one for unstructured data.


### ETL, ELT and Data Pipelines (!)

Extract, Transform, Load (ETL) converts raw data into analysis-ready data by:
- Gathering raw data from a variety of sources;
- Extracting information needed for reporting and analysis;
- Cleaning, standardizing and transforming data into a usable format;
- Loading data into a data repository.

Extract is the step where data from source locations is collected for transformation.
Data extraction could be through:
- Batch processing - source data is moved in large chunkcs from source to target in scheduled intervals.
- Stream processing - source data is pulled in real-time form source and transformed while in transit before loaded into data repository.

Transformation involves the execution of rules and functions that convert the raw data into data that can be used for analysis.
Examples:
- Standardising dat formats and measurements
- Removing duplicate data
- Aggregating data e.g. summing, averaging, grouping
- Filtering out data
- Enriching data e.g. splitting full name into first, middle and last name
- Establishing key relationships across tables
- Applying business rukes and data validations

Load is the transportation of processed data into a destination data repository.
- Initial load - populating all data in the repository for the first time
- Incremental load - applying ongoing updates and modifications as needed periodically
- Full load/refresh - erasing/overwriting contents of one or more tables with fresh data

Load verification includes checks for:
- Missing or null values
- Server performance
- Load failures

![alt text](img/01-06.png)

With ELT, extracted data is first loaded into the target system, then transformations are applied in the target system, with the target storage being a data lake or warehouse. Largely used in cloud computing and big data.

![alt text](img/01-07.png)

ELT:
- Helps process large sets of unstructred and non-relational data
- Ideal for data lakes, which is designed to handle and store large amounts of raw data.
- Shortens the cycle between extraction and delivery as data is directly delivered to the destination system
- Allows you to ingest volumes of raw data as immediately as the data becomes available
- Afords greater flexibility to analysts and data scientists for exploratory data analytics
- Transforms only the data that is required for a particular use case, so that the rest or raw data can be used for other purposes.
However, in the ETL process, the entire structure of the DW may need to be modified if it's not suitable for a new use case. 

A data pipeline encompasses the netire journey of moving data from one system to another, including the ELT/ETL process. Can be used for both batch and streaming data. Supports long running batch querues and smaller interactive queries. 


### Data Integration Platforms (!)

Data integration allows organisations to ingest, transform, combine and provision across various data types. Applies in data consistency across apps, master data management, data sharign between enterprises and data migration and consolidation.

Includes 
- Accessing, queuing, extracting data from operational systems
- Transforming and merging extracted data logically or physically
- Data quality and governance
- Delivering data through an intergrated approach for analytics purposes

Capabilities of a modern data integration platform includes:
- A variety of prebuilt connectors and adapaters from a wide range of data sources e.g. IoT logs, social media, databases, flat file object storage etc.
- Open source architecture
- Optimisation for both batch processing of large scale data and/or sontinuous data streams
- Integration with big data sourcess
- Functionalities for data quality and governance, compliance and security.
- Portability between on-premesis and different types of cloud environments. 



### Viewpoints: Tools, Databases and Data Repositories of Choice

| Category | Technologies | Purpose |
|----------|--------------|---------|
| **Programming languages** | Python, Shell, Perl, Java | Data processing, automation, scripting, APIs, and custom ETL solutions |
| **Relational databases (RDBMS)** | MySQL, PostgreSQL, IBM Db2, Microsoft SQL Server, MariaDB | Store and manage structured data |
| **NoSQL databases** | MongoDB, Cassandra | Store semi-structured or large-scale distributed data |
| **Graph databases** | Neo4j | Store and query connected data and relationships |
| **Data warehouses** | AWS Redshift | Central repository for analytics and reporting |
| **Data lakes & cloud storage** | AWS S3, cloud storage | Store raw, large-scale, and archival data |
| **Big data processing** | Apache Spark, Hadoop | Process and analyze large datasets |
| **Streaming & messaging** | Apache Kafka, WebSphere MQ | Real-time data streaming, messaging, and replication |
| **ETL / Data integration** | Talend, SSIS (SQL Server Integration Services), Apache NiFi, Okada (as mentioned), internal ETL tools | Extract, transform, load, and move data between systems |
| **Workflow orchestration** | Apache Airflow | Schedule and orchestrate data pipelines |
| **Web scraping** | Beautiful Soup, Scrapy | Extract data from websites |
| **Version control & DevOps** | Git, GitHub | Source code management and collaboration |
| **CI/CD & automation** | Jenkins | Automate builds, deployments, maintenance, and workflows |
| **Database change management** | Liquibase | Track and manage database schema changes |
| **Infrastructure** | Containers | Deploy and manage applications consistently |

### Foundations of Big Data (!)

Big data refers to teh dynamic, large and disparate volumes of data creatred by people, tools and machines. It requires new, innovative and scalable technology to collect, host and analytically process the vast amount of data gathered in order to derive real-time business insights that relate to consumers, risk, profit, performance, productivity management and enhanced shareholder value.

The five V's of Big Data:
- Veclocity is the speed at which data accumulates - data is being generated extremely fast.
- Volume is the scale of data or increase in the amounts of data stored. Drivers of this are increase in data sources, higher resolution sensors and scalable infrastructure.
- Variety is the diversity of data formats e.g. structured, semi-structured, unstructured. Also reflects data coming from different sources. Drivers are the increase in the variety of data sources themselves - new technologies for example.
- Veracity is the quality and origin of data, and its conformity to facts and accuracy. Attributes include consistency, completeness, integrity and ambiguity. Drivers include cost and the need for traceability.
- Value is our ability and need to turn data into real world value such as profit, or medical and social decisions and benefits. 

The scale of the data being collected means that it's not feasible to use conventional data analysis tools, and thus data engineers turn to leverage distributed computing such as Apache Spark and Hadoop, which extract, load, analyse and process the data across distributed compute resources. 

### Big Data Processing Tools

Big data processing technologies help organizations work with large volumes of structured, semi-structured, and unstructured data to derive business value.

This section focuses on three major open-source technologies and their roles in big data analytics:

1. Apache Hadoop
2. Apache Hive
3. Apache Spark

**Apache Hadoop**
- Hadoop is an open-source, Java-based framework for distributed storage and processing of large datasets across clusters of computers.
- A **node** is a single computer; multiple nodes form a **cluster**.
- Hadoop can scale from a single node to many nodes, each contributing local storage and compute.
- It is designed to be reliable, scalable, and cost-effective, with no strict data format requirements.

**What Hadoop enables**
- Ingests emerging and diverse data formats (for example: streaming audio/video, social media sentiment, clickstream data) alongside traditional structured/semi-structured/unstructured data.
- Supports real-time, self-service access for stakeholders.
- Helps optimize enterprise warehouse costs by consolidating data and offloading infrequently used ("cold") data to Hadoop-based systems.

**HDFS (Hadoop Distributed File System)**
- HDFS is Hadoop’s distributed storage layer, built to run on commodity hardware.
- It partitions large files across multiple nodes, enabling parallel access and parallel computation.
- It replicates file blocks across nodes (typically 3 copies by default) for fault tolerance and high availability.

**Why HDFS matters**
- **Parallelism:** Work is split into smaller chunks and executed across many servers.
- **Data locality:** Computation is moved close to where data resides, reducing network traffic and improving throughput.
- **Fast recovery:** Automatic fault detection and recovery from hardware failures.
- **High-throughput access:** Suitable for streaming and large-scale data flows.
- **Scalability:** Can scale to hundreds of nodes in a cluster.
- **Portability:** Works across different hardware and operating systems.

**Apache Hive**
- Hive is an open-source data warehouse system built on top of Hadoop.
- It supports reading, writing, and managing large datasets in HDFS (and systems like Apache HBase).
- It is well-suited to data warehousing workloads such as ETL, reporting, and analytical querying.
- Hive provides SQL-like access, making big data querying more accessible.

**Hive limitations**
- Queries have high latency because Hive relies on Hadoop’s batch-oriented processing.
- Not ideal for applications requiring very fast response times.
- Primarily read-oriented; not suitable for heavy transactional, write-intensive workloads.

**Apache Spark**
- Spark is a general-purpose distributed processing engine for large-scale analytics.
- Key workloads include:
   - Interactive analytics
   - Stream processing
   - Machine learning
   - Data integration
   - ETL
- Spark uses in-memory computation for high speed, spilling to disk only when needed.
- It supports multiple languages: Java, Scala, Python, R, and SQL.
- It can run standalone or on top of other infrastructures (including Hadoop).
- It reads from many data sources, including HDFS and Hive.

**Key Spark use case**
- Fast stream processing and complex real-time analytics.

**Quick comparison**
- **Hadoop:** Foundation for distributed storage/processing at scale.
- **Hive:** SQL-friendly warehouse layer for analytics on Hadoop data.
- **Spark:** High-performance engine for real-time and advanced analytics.


### Viewpoints: Impacts of Big Data on Data Engineering

Data professionals highlight that big data has significantly reshaped data engineering into a broader and more dynamic field.

**How Big Data is characterized**
- Big data is described through the four Vs:
   - Velocity
   - Veracity
   - Volume
   - Variety

**Core impact on data engineering**
- Data engineering has become more diverse and opportunity-rich.
- Organizations now collect data at much larger scale, making insight generation more business-critical.
- The field has expanded beyond traditional database administration to include distributed systems, new storage paradigms, and advanced analytics.

**Technology and talent shift**
- Big data growth has driven the emergence of new technologies, products, and architectures.
- Demand has increased for professionals who can:
   - Build and manage big data platforms
   - Analyze high-volume and high-variety datasets
   - Work across both structured and unstructured data ecosystems

**From traditional ingestion to high-velocity data ecosystems**
- In earlier systems (before social media and large-scale IoT), data ingestion paths were limited and often slow (for example, manual data entry).
- Over the last decade, APIs, connected devices, and machine-to-machine updates have changed both the scale and nature of data ingestion.
- This evolution exposed limits of traditional RDBMS-only approaches (not a one-size-fits-all model).

**Resulting evolution of tools and platforms**
- With growing source diversity and volume, data engineers adopted and built new technologies, including:
   - Google Bigtable
   - Cassandra
   - Graph databases
   - Hadoop
   - MapReduce
- Engineers increasingly had to create internal tools and continuously upskill on new platforms.

**Storage mindset shift**
- Organizations have become much more comfortable storing very large amounts of data.
- Raw storage cost and capacity are less of a bottleneck than before.
- The big data era emphasized both:
   - Storing more data
   - Handling large datasets more effectively

**Structured vs unstructured data implications**
- Unstructured data has become a major part of enterprise data landscapes.
- It is often not managed in traditional relational databases.
- When persisted in databases, document-oriented systems (for example, MongoDB) are commonly used.

**Bottom line**
- Big data transformed data engineering from a mostly traditional database discipline into a multi-platform, high-scale engineering domain centered on variety, scale, and speed.


## Module 3 - Data Engineering Lifecycle

### Architecting the Data Platform (!)
Data collection layer connects to data sources, transfers data from data sources to the platform in streaming and batch modes, maintain info about the data collected in the metadata repository e.g. how much data was ingested, from which data sources etc.

Data storage and integration layer stores data for procesing and long term use, transform and merge extracted data and make data available for processing. Reliable, scalable, high performing, cost efficient.

Data processing layer is responsible for data validations, transformations and application of business logic to the data. Reads data from storage and apply transformations; support popular querying tools and languages; scale to meet the processing demands; provide a way for analysts and scientists to work on the data platform. This layer performs:
- structuring - actions that change the form and schema of data;
- Normalisation - cleaning the data of unused data, reducing redundancy and inconsistency
- denormalisation - combining data from multiple tables into a single table for more efficient querying.
- data cleaning - fixes irregularities in data for better credible data for downstream uses.

In RDB, storage and processing are the same layer. In Big Data systems, data is stored in HDFS then processed in an engine such as Spark. Data processing may also preceed sata storage - ELT instead of ETL - where data is loaded before transforms apply.


The analysis and user interface delivers processed data to data consumers - BI analyssis and business users who consume the data via dashboards/reports, Data scientists and analyst for more processing, other apps and services. Needs to support quering tools, dashboarding and BI apps like PowerBI and programming languages and APIs for online and offline and real time processing. 

Data pipeline layer is responsible for implementing and maintaining a continuouslyflowing data pipeline.


### Factors for Selecting and Designing Data Stores (!)
A data store / repository refers to a data that has been collected, organised and isolated so that it can be used for business operations, or mined for reporting or data analysis. Can be a database, warehouse, mart, big data store or data lake. Needs to be scalable and caoable of operating during high workloads.

Primary considerations for designing a data store:
- Types of data
   - Databses can be relational or non-relational
   - Relational (RDBMS) is best used for structured data with a well-defined schema and can be organised into a tabular format.
   - Non relational (NoSQL) best for semi/unstructured data - schema less and free form data. 
   - Four types of NoSQL: key-value, document based (e.g. not best for complex search queries and multi-operation transactions), column based, graph based (not for high volume transactions).
- Volume of data 
   - data lake stores large volumes of raw data in its native format straight from the source; stores both relational and non relational data at scale without defining the data's structure and schema. 
   - For a big data store, they store data that is high volume and velocity, of diverse types and data that needs distributed processing for fast analytics; they split large files across muultiple computers (nodes) allowing computations and processing to run parallel on each node where the partitioned data is stored.
- Intended use of data 
   - consider the number of transacitions, frequency of updates, type of operations, response time and backup/recovery requirements
   - Consider whether a usecase requires OLTP or OLAP data store.
   - Schema design, indexing and partitioning strategies have abig role to play in performance of systems based on how data is getting used.
   - Also need to consider scalability, which is the data store's capabilitiy to handle growth in the amount of data, users and workloads.
   - Need to also consider normalisation - helps with optimising use of storage space, making database maintenance easier and faster access to data; used in OLTP but difficult to use with OLAP as it may lead to performance issues. 
- Storage considerations - conisder performance, availability, integrity and recoverability of data.
   - Performancce - throughput is the rate at which information can be read from/written to the storage; latency is the time it takes to access a specific location in storage. 
   - Availability - storage soln must enable access to the data when it is needed with no exception - no downtime.
   - Integrity - data must be safe from corruption, loss and outside attack
   - Recoverability - storage soln must exure data can be recovered in the event of failutes and natural disasters.
- Privacy, security an governance needs - a good strategy is a layered approach that includes access control, multizone encrytion, data management and monitoring systems.
   - Data needs to be made available through controlled data flow and data manegement by using multiple data protection techniques. 
   - Need to consider privacy, security and governance as a part of the data store's design from the very start.


### Security (!)

Need to tackle security at multiple levels.
- Security of physical infrastructure
- Network security
- Application security
- Data security

CIA triad details the key components to creating an effecrive strategy for information security
- Confidentiality through controlling unauthorised access
- Integrity through validating that your resources are trsutworthy and have not been tampered with
- Availability by ensuring authorised users have access to resources when they need it.

**Network security**
- Firewalls to prevent unauthorised to private networkes
- Network access control to ensure endpoint security by allowing only authorised devices to connect to the network e.g. no devices with outdated features can connect. 
- Network segmentations to create silos, or virtual local area networks, within a network so that assets are segmented based on level of security needed to access those assets.
- Security protocols to ensure attackers cannot tap into data in transit.
- intrusion detection and prevention systems inspect incoming traffic for intrusion attempts and vulnerabilities.

**Application security**
- Security needs to be built into the foundation of an application in order to prevent other applications and services from introducing vulnerabilities.
- Thread modelling to identify weaknesses and attack patterns related to the application.
- Secure design that mitigates risks
- Secure coding guides and practices that prevent vulnerabilities
- Security testing to fix problems before the application is deployed and to validate that it is free of known security issues.

**Data security**
- Data is either at rest in storage, or in transit between systems, applications, services and workloads.
- Data security is enabled using:
   - Authentication - verifies a user is who they say they are using passwords, tokens, biometrics
   - Authorisation - ensures users access information based on their role and privileges assigned to their roles.
- Data at rest includes files, objects and storage, stored physically in a database, warehouse, tapes, offsite backups and mobile devices. Protect data at rest using encryption to protect information from disclosure even if data is lost or intercepted
- Data in transit is moving from one location to another over the internet and is encrypted using HTTPS, SSL, or TLS.


### Viewpoints: Importance of Data Security

Data security is foundational in data engineering: if data is not secure, its business value and reliability are compromised regardless of how advanced the pipeline or analytics stack is.

**Why security is critical**
- Data is now treated as one of an organisation's most valuable assets ("data is the new oil"), so it must be protected accordingly.
- Serious breaches can be catastrophic: reputational damage, compliance penalties, operational disruption, and for smaller firms, even business failure.
- Security is not a final "hardening" step before go-live; it must be built in from day one and enforced throughout the lifecycle.

**Organisation-wide responsibility**
- Security, governance, and compliance are not only technical concerns for data engineers.
- They must be embedded into data architecture, operating processes, and team behaviors across the organisation.

**Core operational controls highlighted**
- Strict separation of production and non-production environments.
- Prevent unmasked production data from being exposed in lower environments (dev/test).
- Restrict production data access only to users who genuinely need it.
- Apply least-privilege access: each user should have only the minimum permissions required for their role.

**Insider risk awareness**
- Many real-world data threats originate inside the organisation rather than from external attackers.
- Over-permissioned internal users are a major source of data misuse and breach incidents.
- Access abuse examples (e.g., viewing sensitive records without business need) reinforce the need for monitoring and controls.

**Security includes resilience and recovery**
- Data security also means preserving availability, not just confidentiality.
- Backup, restore, and disaster recovery capabilities are essential because hardware failure can cause effective data loss/access loss.
- If data cannot be recovered quickly after failure, security objectives are not fully met.

**Bottom line**
- Protecting data means combining prevention (access control, masking, environment isolation), governance/compliance, and recovery readiness.
- The goal is to reduce breach risk, protect business value, and ensure trusted, continuous access to critical data.



### How to Gather and Import Data (!)

SQL offers simple commands to specify:
- What is to be retrieved from the database;
- Table from which it needs to be extracted;
- Grouping records with matching values
- Dictating the sequence in which the query results are displayed.
- Limiting the number of results that can be returned by the query.

NoSQL DBs can be queries using SQL or SQL like queries, but some come with their own querying tools (CQL --> Cassandra; GraphQL --> Neo4J).

Application Programming Interfaces (APIs) are invoked from applications that require the data and access an endpoint containing the data. Endpoints can include databases, web services and data marketplaces. APIs are also used for data validation e.g. one can use them to validate addresses and post codes.

Web scraping is used for downloading specific data from web pages based on defined parameters. Used to extract data such as text, contact info, images, videos, pod casts etc from a web property. RSS feedsused for capturing updated data from online forums or news sites where data is refreshed on an ongoign basis.

Data streams aggregate constant streams of data flowing from sources such as instruments, IoT devices, applications and GPS data. Also used for extracting data from social media sites and interactive platforms. 

Data exchange platforms allow the exchange of data between data providers and data consumers. Exchanges have a set of well defined exchange standarrds, protocols and formats relevant for exchanging data. Ensure that security and governance are maintained - provide data licesing workflows, de-identification of PPI, legal frameworks and a quarantined analytics environment. Examples: AQS DataExchange, Snowflake.

Data that has been identified and gathered from the various data sources now needs to ​be loaded or imported into a data repository before it can be wrangled, mined, and analyzed. ​The importing process involves combining data from different sources to provide a combined ​view and a single interface using which you can query and manipulate the data. ​Depending on the data type, the volume of data, and the type of destination repository, ​you may need varying tools and methods. 

Since relational databases store structured data with a well defined schema, it is optimised to store data with a well-defined structure, e.g. data from OLTP systems, spreadsheets, online forms, sensors, network and web logs etc. However, structured data can be store din NoSQL.

For semi-structured data with some organisational properties but no rigid schema (emails, XML, zip files, biinary exe, ), they can be stored in NoSQL clusters, with XML and JSON commonly used for storing and exchanging semi-structured data. 

For unstructured data that doesn't have a structure and cannot be organised into a schema, such as web pages, socia media feeds, images, videos, documents, media logs and surveys, NoSQL databases and data lakes are good options to store and manipulate unstructured data -- data lakes can store all types of data. 

ETL tools and data pipelines provide automated functions that facilitate the process of importing data. 

### Data Wrangling (!)

Data wrangling is an iterative process that involves:
- Data exploration
- Transformation
- Validation
- Making data available for credible and meaningful analysis.

**Key Data Transformations**

Structuring - changes the form and schema of the data. 
- For example, if raw incoming data comes from relational database and another from e.g. JSON logs, then combining them will necessitate schema changes such as changing the order of fields/columns or combining fields in complex transformations.
- Joins add columns from several tables into one or more bigger tables, extending all rows to contain columns from both tables ("horizontal extension").
![alt text](img/01-08.png)
- Unions add rows, where rows from several tables are added after each other to produce a bigger table - each row in the resultant table is from one source table or another. 
![alt text](img/01-09.png)

Normalisation and denormalisation of data
- Normalisation includes cleaning unused data and reducing redundancy and inconsistency. OLTP systems are highly normalised so that data can be quickly updated in one place without duplication.
- Denormalisation combines data from multiple tables into a single table for faster querying of data for reports and analysis.

Cleaning - fixing irregularities in data in order to produce a credible and accurate analysis. 
1. First step is inspection - detecting issues and errors in the dataset, then using scripts and tools to define rules and constraints the data must adhere to and validate the data against those rules and constraints; can also use profiling to inspect source data and use visualisation of data via statistical methods. 
   - Data profiling helps inspect the source data to understand the structure, content and interrelationships in the data, uncovering anomalies and data quality issues (e.g. null/blank data, duplicate, out of bounds/incorrect type).
   - Visualisation via statistical methods can help spot outliers.
2. Next is the actual cleaning of the data - the techniques you apply for cleaning your data will depend on the use case and the type of issues you encounter. 
   - Missing values can cause unexpected or biased results. can either filter out records with missing data or source the missing data, or calculate (impute) the missing data based using statistics. 
   - Duplicate data need to be removed.
   - Irrelevant data that is not needed or contextual to the use case - remove too!
   - Data type conversion used to change the data types of values with the wrong data type for the field they are stored in.   
   - Standardising data is needed to ensure formats and units of measurements for certain data types are standard across the whole data. 
   - Syntax errors need to be fixed.
   - Outliers neeed to be examined for accuracy and inclusion in the dataset.
   

### Tools for Data Wrangling
Spreadsheets like Microsoft Excel and Google Sheets offer manual data wrangling features with built-in formulas and add-ins such as Power Query and Google Sheets Query. OpenRefine is an open-source tool that supports multiple data formats and provides menu-based operations for easy data cleaning and transformation.

Google DataPrep is a cloud-based service that visually helps clean and prepare structured and unstructured data with automatic schema and anomaly detection.

IBM Watson Studio’s Data Refinery enables discovery, cleansing, and transformation of large datasets with automatic data type detection and governance enforcement.

Trifacta Wrangler is a cloud service known for interactive data cleaning and collaboration, exporting data to tools like Excel and Tableau.

Python offers powerful libraries such as Jupyter Notebook for data tasks, Numpy for numerical operations, and Pandas for fast data analysis and transformation.

R provides libraries like Dplyr for data wrangling, Data.table for fast aggregation, and Jsonlite for JSON parsing and web API interaction.

Selection depends on factors like data size, structure, cleaning needs, infrastructure, ease of use, and team capabilities.

### Querying and Analysing Data (!)

Query languages help us access and understand data in databases. The same analysis techniques apply across SQL and SQL-like systems (for example, Cassandra CQL, Cypher for Neo4j), and can also be used through APIs.

Core querying techniques for analysis:
- Counting and aggregation
- Identifying extreme values
- Slicing/filtering data by conditions
- Sorting data
- Pattern filtering
- Grouping data

**1. Count how much data you have**
- `COUNT()` returns the number of rows/records in a dataset.
- `DISTINCT()` returns unique values in a column.
- `COUNT(DISTINCT column)` gives the number of unique values.
- Lecture example: 15 total records and 8 unique car dealers.

**2. Aggregate for quick summaries**
- `SUM()` totals a numeric column.
- `AVG()` returns the mean of a numeric column.
- `STDDEV()` shows how spread out values are (dispersion).
- Insight: a high standard deviation means values are widely spread, even if the average seems moderate.

**3. Find extreme values**
- `MAX()` returns the highest value in a column.
- `MIN()` returns the lowest value in a column.
- Useful for quickly understanding bounds and detecting unusual values.

**4. Slice data using conditions**
- Retrieve subsets based on one or more conditions (for example, location, dealer area, price range).
- Common SQL tools for slicing include `WHERE`, `BETWEEN`, `AND`, and `OR`.
- Helps answer focused questions (for example, customers spending between 1000 and 2000 in a specific area).

**5. Sort data to reveal trends**
- `ORDER BY` arranges results in a meaningful order.
- Supports ascending (`ASC`) and descending (`DESC`) sorting.
- Example use: sort by purchase date to inspect sales spikes around festival periods.

**6. Filter patterns with partial matches**
- `LIKE` matches patterns, unlike strict equality (`=`).
- Use wildcards to represent unknown characters.
- Example: if first 3 pincode digits identify a region, use a pattern with wildcards for remaining digits.

**7. Group data for segmented insights**
- `GROUP BY` groups rows by one or more columns.
- Often combined with aggregates such as `SUM()` to summarize each group.
- Example: total customer spend by pincode.

**Key takeaway:**
Basic querying operations are foundational for data analysis. They help you profile data volume, summarize distributions, isolate subsets, detect trends, match patterns, and compute grouped business insights.

### Performance Tuning and Troubleshooting (!)

A data pipeline typically runs with a combination of complex tools and can face several different types of performance threats such as:
- Scalability in the face of increasing data sets and workloads.
-  Application failures
- Scheduled jobs not functioning accurately, waiting on dependencies, not running in the correct sequence or not running at all.
- Tool incompatibilities. 

The following performance metrics benchmark or evaluate performance:
- Latency - time it takes for a service to fulfill a request;
- Failures - rate at which a service fails;
- Resource utilisation patterns
- Traffic - number of user requests received in a given period.

To troubleshoot a pipeline issue:
1. Collect information about the incident to ascertain if observed behavuour is an issue.
2. Check is you're working with all the right versions of software and source codes.
3. Ceck the logs and metrics early to isolate whether an issue is related to infrastructure, data, software or combination of these.
4. Reproduce the issue in a test environment to create a root cause hypothesis through a series of tests.

Performance metrics for database:
- System outages
- Capacity utilisation
- Application slowdown
- Performance of queries
- Conflicting activities and queries being executed simultaneously
- Batch activities causing resource constraints

Capacity planning determins the optimal hardware and software resources required for performance. 
Factors in load on a system fluctuating on a day to day basis and future growth requirements.

Database indexing - locating data without searching each row in a database, resulting in faster querying. It minimises the number of times a disk needs to be accessed when a query is processed.  

Database partitioning divies large tables into smaller, individual tables, improving performance and manageability. Queries run faster becayse they're accessing a smaller part of the data.

Database normalisation - reducing inconsistencies arising out of data redundancy and anomalies arising out of update, delete and insert operations on databases.

Database monitoring tools take frequent snapshots of the performance indicators of a database, helping to:
- Track when and how a problem started to occur;
- Isolate and get to the root cause of the issue.

Application performance management tools measure and monitor the performance of applications and amount of resources utilised by each process by tracking request response times and error messages. . This helps in proactive allocatiion of resources to improve application performance.

Tools for monitoring query performance gather statistics about query throughput, execution, performance, resource utilisation patterns for better planning and allocation of resources.

Data pipelines typically have long running processes that take a significant amount of time to complete. This means that the cost of errors are higher when they occur at the end of such processes. Job lebel runtime monitoring breaks up a job into a series of logical steps which are monitored for completion and time to completion. 

Monitoring the amount of data being processed through a data pipeline helps to assess if size of the workload is slowing the system down. 

Maintenance routines help to operate systems at optimal levels by generating data that can be used to identify systems and procedures responsible for faults and low availability. These routines can be:
- Time based - planned as scheduled activities at pre-fixed time intervals.
- Condition based - performed when there is a specific issues or decrease in performance. 


### Governance and Compliance (!)

Data governance is a data management process that maintains the security, privacy and integrity of data in an organisation. 
Regulations seek to prevent the misuse of sentitive PII - which can be used to trace, identify or bring about harm to an individual. 

Compliance covers the process and procedures through which an organisation adheres to regulations and conducts its operations in a legal and ethical manner. Organisations need to:
- Establish controls and checks in order to comply with regulations;
- Maintain a verifiable audit trail to establish adherence to regulations.
Compliance is an ongoing, evolving process requiring a blend of people, process and technology.

Governance regulations require enterprises to know their purpose and maintain transparency in their actions at each step of the data lifecycle.
1. Data Aquisition stage
   - Identify data that needs to be collected and the legal basis for procuring that data;
   - Establish the intended use of the data published as a privacy policy - communicated internally and with those whose data is being collected.
   - Identify the amount of data needed to meet the defined purposes.
2. Data processing stage
   - Flesh out details of how exactly personal data will be processed;
   - Establish the legal basis e.g. contract or consent for the processing of the personal data.
3. Data storage stage
   - Define where to store the data;
   - Establish specific measures to prevent internal and external security breaches.
4. Data Sharing stage
   - Identify third party vendors in the supplu chain that will have access to the collected data;
   - Establish how to hold those vendors contractually accountable to the same regulations.
5. Data retention and disposal stage
   - Define policies and processes to follow for the retention and deletion of personal data after a designated time;
   - Define how to ensure deleted data is removed from all locations, including third party systems.
At each of these stages, an auditable trail of PII needs to be retained and maintained.

Today's tools and technologies provide several controls for ensuring organisations comply to covernance regulations.
- Authentication and Access Control
   - Authentication verifies a user is who they say they are.
   - Tools offer layered authentication processes such as combination of passwords, tokens and biometrics to prevent unauthorised access. 
   - Access control systems ensure only authorised users have access to resources based on their user group and role. Databases, for example, have the concept of roles and privileges so only authorized users ​and applications can access specific objects, such as tables or rows or columns, in a database.
- Encryption and data masking
   - Encryption converts data to an encoded format that can only be legible once it is decrypted via a secure key. Available for data at rest and in transit. 
   - Data masking provides anonymisation of data for downstream processing and pseudonymisation of data.
   - Anonymisation abstracts the presentation layer without changing the data in the database itself e.g. presenting characters with symbols when on the screen. 
   - Pseudonymisation of data replaces PII with artificial identifiers so that it cannot be traced back to an individual e.g. replacing a name with another random name. 
- Hosting - On prem and cloud based systems provide hosting options that comply with the requirements and restrictions for international data transfers.
- Monitoring and alerting 
   - Security monitoring proactively monitors, tracks and reacts to security violations across infrastructure, applications and platforms. 
   - Monitoring systems also provide detailed audit reports that track access and other operations on the data. 
   - Alerting functionalities flag security breaches so immediate remedial actions can be triggered. Alerts are based on the severity and urgency level of a breach.
-  Data erasure - a software based method of permanently clearing data from a system by overwriting. Data erasure prevents deleted data from being retrieved. 

### Overview of the DataOps Methodology

DataOps is a collaborative data management practice focused on improving communication, integration, and automation of data flows between data managers and data consumers across an organization. Gartner emphasizes that DataOps aims to create predictable delivery and change management for data, data models, and related artifacts, while enforcing appropriate security, quality, and metadata.

As organizations scale, data environments become more complex:
- More pipelines, tools, and platforms to manage.
- Larger and more diverse data teams and stakeholder groups.
- Greater risk of defects, delays, and inconsistent data quality.

DataOps addresses these problems by introducing disciplined collaboration and repeatable engineering processes across the full lifecycle, from ingestion and processing to analytics and reporting.

Key goals of DataOps:
- Reduce data defects and quality issues.
- Shorten cycle times for delivering analytics-ready data.
- Improve end-to-end visibility and traceability of data.
- Ensure dependable, secure, and governed data delivery for all stakeholders.

How DataOps is enabled:
- Metadata management and cataloging.
- Workflow automation and test automation.
- Version-controlled code repositories.
- Collaboration tooling across data producers and consumers.
- Orchestration to coordinate complex, dependent tasks.

DataOps helps ensure activities happen in the right sequence, with the right permissions and governance controls. This enables continual optimization: reducing waste, streamlining steps, automating repetitive work, increasing throughput, and improving outcomes sprint after sprint.

Popular DataOps platforms include IBM DataOps, Nexla, Switchboard, StreamSets, and Infoworks.

**DataOps Methodology (Three Phases)**

The purpose of the DataOps Methodology is to provide a repeatable process for building and deploying analytics and data pipelines so organizations can know, trust, and use data to drive business value.

It improves confidence in decision-making data by making it:
- Relevant
- Reliable
- Traceable

It also helps tackle inefficiencies in accessing, preparing, integrating, and delivering data.

The methodology consists of three major phases:

1. Establish DataOps
- Set data strategy and goals.
- Form cross-functional teams.
- Establish toolchain and delivery baseline.
- Align work with business priorities.

2. Iterate DataOps
- Deliver data outcomes in defined sprints.
- Typical activities include discover, classify, quality management, policy management, movement/integration, and self-service enablement.
- Use catalog-driven practices to standardize and scale delivery.

3. Improve DataOps
- Review each sprint.
- Refine process and operating model.
- Recommend improvements to continuously increase quality, speed, and reliability.

![alt text](img/01-10.png)

**Benefits of Using the DataOps Methodology**

Adopting DataOps helps organizations make data more trusted, secure, and usable. Benefits include:

- Automated metadata management and cataloging of data assets.
- Improved data lineage for credibility, compliance, and auditing.
- Automated jobs/workflows that improve integrity, relevance, and security.
- Streamlined delivery processes for faster and more predictable access.
- Business-ready pipelines that are consistently available to stakeholders.
- Stronger data-driven culture through governance, quality, and automation.

Benefits for data practitioners:
- Reduced development time.
- Less waste and duplicate effort.
- Higher productivity and throughput.
- Better consistency in producing high-quality data artifacts.

DataOps improves collaboration across data professionals, consumers, and business stakeholders by aligning teams around shared outcomes and reliable delivery.

Implementation note:
- DataOps adoption usually requires organizational change, investment, and time, but the long-term payoff is more efficient and reliable data and analytics operations.

Career relevance:
- DataOps also creates career growth opportunities. DataOps Engineers focus on optimizing the development and deployment lifecycle for data and analytics systems.
- With experience, practitioners can move into specialist roles that define data strategy, design business processes, establish performance metrics, and measure operational performance.


## Module 4 - Career Opportunities and Data Engineering in Action

### Career Opportunities in Data Engineering

Data engineering is recognized as one of the fastest-growing tech occupations, with significant demand across industries such as healthcare, technology, consulting, retail, and automotive.
Reports from LinkedIn, Dice, and Glassdoor emphasize the increasing need for data engineering talent, driven by expanding data infrastructure in companies.

Job titles vary and include Data Architect, Database Architect, ETL Engineer, Data Warehouse Engineer, Big Data Engineer, and Data Lake Engineer.
Roles may focus on specific areas like data architecture, pipelines, warehouses, or big data platforms, requiring knowledge of operating systems, programming languages, databases, and infrastructure.
Career Progression and Skills Development

Career paths typically start from Associate or Junior Data Engineer and advance to Senior, Lead, and Principal Data Engineer roles.
Growth involves expanding technical skills across the data engineering lifecycle, improving communication, collaboration, and project management abilities.
Lead roles include translating business requirements into technical solutions, selecting tools, and ensuring data quality, privacy, and compliance.

Big Data Engineers specialize in managing large-scale data processing using tools like Hadoop and Spark.
Machine Learning Engineers combine data engineering with AI and data science skills to design and implement machine learning algorithms.

Overall, success in data engineering requires continuous learning, adaptability, and teamwork to keep pace with evolving technologies and business needs.

### Data Warehousing Specialist

Data Warehousing Specialists focus on designing, modeling, implementing, and supporting enterprise data warehouse environments. This role is a specialization within Data Engineering, centered on warehousing architecture, ETL/ELT, governance, and analytics-ready data delivery.

#### Role Overview
- Designs and implements corporate data warehousing activities.
- Programs and configures warehouse databases and related data systems.
- Supports data warehouse users and downstream analytics teams.
- Owns a focused subset of the wider Data Engineering lifecycle, especially around structured enterprise data.

#### Market Outlook and Salary
- U.S. labor outlook (careeronestop.org): expected growth of about 8-10% over the next decade for related roles (Data Warehouse Specialists, Data Architects, DBAs).
- Estimated annual openings in the U.S.: approximately 13,900.
- U.S. median salary estimate (salary.com): $110,168 for Data Warehouse Specialist roles.

#### Common Alternative Job Titles
- Data Warehouse Specialist
- Data Warehouse Engineer
- Data Warehouse Solution Architect
- Data Warehousing/ETL Solution Specialist
- Data Warehouse Architect
- Data Architect, Data Warehousing & MPP
- Data Warehouse Analyst
- Data Warehouse Administrator
- Data Warehousing Development Specialist

#### Typical Responsibilities
- Build enterprise data management processes, procedures, and software workflows.
- Analyze and improve warehouse efficiency, data quality, usability, and security.
- Design and model warehouse structures, including schemas, dimensions, facts, and supporting marts.
- Define and maintain standards for architecture, naming, modeling, and tooling.
- Troubleshoot warehouse systems and coordinate issue resolution.
- Write or modify programs to meet business and customer requirements.
- Produce technical documentation (metadata, ER diagrams, process flow diagrams).
- Balance data access optimization with batch loading windows and resource usage.
- Perform system analysis, data analysis, and programming in multiple languages.
- Review code, design, tests, and documentation to maintain quality.
- Create and execute test plans for unit and integration testing.
- Implement business rules using stored procedures, middleware, or equivalent services.
- Provide ongoing support to business users and analytics consumers.

#### Soft Skills Required
- Critical thinking for comparing solution trade-offs.
- Complex problem-solving for diagnosing and fixing multi-system issues.
- Decision-making based on cost-benefit and long-term maintainability.
- Systems evaluation for performance monitoring and corrective action.
- Active learning to adapt to new technologies and methods.
- Clear communication with technical and non-technical stakeholders.

#### Technical Skills Required

##### Core Specialized Knowledge
- Programming and software development fundamentals.
- Systems analysis and requirements interpretation.
- Data architecture principles (models, standards, governance).
- Secure data management, transformation, and analysis.
- Data pipeline design and operations (ETL/ELT).
- Business intelligence and dimensional modeling practices.
- Database normalization and data integrity methods.
- Relational data storage and optimization patterns.
- Data migration and integration across platforms.
- Metadata standards and cataloging.
- Cloud-scale data infrastructure concepts.
- Big data administration awareness.
- Data acquisition and transformation workflows.
- Data lake, data mart, and data reservoir concepts.
- IoT and event-stream integration through pipelines.

##### Law and Governance Knowledge
- Regulatory and ethical handling of data, including PII and intellectual property.
- Compliance-aware access, retention, and sharing practices.

##### Software and Platform Skills
- Cloud platforms: AWS, Azure, GCS, Spring Cloud.
- Data warehouses: Snowflake, Databricks, BigQuery, Redshift, Db2.
- Pipeline/orchestration: Kafka, Airflow, Luigi.
- Big data stack: Hadoop, Spark, Hive.
- Operating systems: UNIX, Linux.
- Languages: SQL, Bash, Python, R, Java, C++.
- Databases: SQL Server, MySQL, PostgreSQL, Cassandra, DynamoDB, MongoDB, Neo4j, IBM Db2, Oracle PL/SQL, Solr.
- Metadata tools: Erwin, Talend Data Fabric, Alation, Azure Data Catalog, IBM Watson Knowledge Catalog, OEMM, Informatica EDC, and related catalog products.
- Engineering practices: Agile delivery and Git-based version control.
- BI/analytics tools: Power BI, Tableau, QlikView, Cognos, MicroStrategy, Sisense, Domo, SAS Analytics, and others.

#### Pathways Into the Role
- Typical foundation: bachelor's degree in computer science, computer engineering, mathematics, or related computational fields.
- Alternative foundation: technology/technical diploma in IT or computing disciplines.
- Strong preparation includes hands-on experience in application development, databases, metadata tools, and data integration workflows.

#### Career Progression
- Common progression path: Junior/Associate -> Specialist -> Senior Specialist -> Lead Specialist -> Principal Specialist.
- Progression is non-linear; many professionals shift between Data Engineering specializations based on team needs and personal strengths.
- Smaller teams often require end-to-end lifecycle participation.
- Larger teams tend to enable deeper specialization and faster role stratification.
- Continuous learning is essential for long-term growth due to rapid changes in tooling, platforms, and architectural patterns.

### Data Manager 

Data Managers oversee how an organization governs, secures, and uses data to meet business goals. They work across technical teams, analytics teams, governance/compliance teams, and leadership to ensure data is trusted, accessible, and used responsibly.

#### Technical Roles
Technical data roles focus on infrastructure, architecture, and machine learning systems. These roles typically require strong programming ability, database knowledge, and experience handling large datasets.

Common technical roles include:
- Data Engineer
- Machine Learning Engineer
- Database Administrator (DBA)

Entry pathway:
- A common starting point is an entry-level data engineering role.
- This builds familiarity with the data ecosystem, including pipelines, integration workflows, and platform maintenance under senior guidance.

Role highlights:
- Machine Learning Engineers build and evaluate machine learning models, selecting the best approach for a given dataset and use case.
- DBAs manage and maintain databases for performance, reliability, and security.

##### AI Impact on Technical Roles
- AI can automate repetitive technical tasks.
- AI-assisted tooling can help optimize code and workflows.
- Technical professionals can spend more time on higher-value work, such as architecture design and integration of AI components into production systems.

#### Analytical Roles
Analytical roles focus on exploring data, identifying insights, and communicating findings for decision-making.

Core roles include:
- Data Analyst
- Data Scientist

Typical responsibilities:
- Data Analysts often build visualizations, dashboards, and reports.
- Data Scientists usually lead analytical direction, apply statistical methods, and develop narratives from findings.
- Data Scientists are also responsible for advocating recommendations to stakeholders.

##### AI Impact on Analytical Roles
- AI will automate parts of analysis and reporting.
- Human value will increasingly center on judgment, framing business context, and storytelling.
- Analytical professionals will still need to craft clear, coherent, and compelling data narratives.

#### Governance and Privacy Roles
Governance and privacy roles ensure data collection, storage, sharing, and usage align with legal, ethical, and organizational requirements.

Common roles include:
- Data Governance Associate
- Data Steward
- Compliance Specialist
- Governance Manager
- Data Ethics Steward
- Data Privacy Officer

Entry pathway:
- An entry-level governance role often starts as a Data Governance Associate, supporting documentation, policy adherence, and data quality checks.

Role distinctions:
- Data governance defines and enforces policies for data quality, integrity, security, and compliant use.
- Data Stewards focus on quality, proper handling, and policy-aligned operational use of data.
- Data Ethics Stewards focus on responsible and ethical use beyond baseline compliance, emphasizing transparency and accountability.

##### AI Impact on Governance and Privacy Roles
- As AI adoption expands, governance needs are expected to grow rapidly.
- AI can assist with policy monitoring and issue detection.
- Human teams remain essential for strategy, ethics, legal interpretation, and alignment to business objectives.

#### Leadership Roles
Leadership roles set the organization-wide data vision, strategy, and policy direction.

Examples include:
- Data Architect
- Chief Data Officer (CDO)
- Data Ethics Officer

Leadership responsibilities:
- Define data and AI policies.
- Ensure enterprise-wide alignment with those policies.
- Decide where, why, and how AI should be used.
- Shape the long-term business impact of data and AI adoption.

##### AI Impact on Leadership Roles
- Data leaders govern enterprise AI direction and responsible adoption.
- They balance innovation, risk, compliance, and value creation.
- Their decisions strongly influence how AI transforms the organization.

![alt text](img/01-11.png)

### Viewpoints: Get into Data Engineering

Data professionals shared different real-world paths into data engineering, showing there is no single route into the field.

**Path 1: DBA to Data Engineer (platform expansion path)**
- One professional started as a DBA on IBM Db2 and focused on solving OLTP/OLAP performance issues.
- Through collaboration with web developers, ETL teams, BI teams, and business users, the role naturally expanded.
- Evolving business needs drove adoption of additional platforms:
   - MongoDB for document-oriented workloads
   - Cassandra for always-on, highly available 24x7 systems
   - Hadoop clusters for analytical proof-of-concept work
- Over time, this multi-platform work effectively transitioned the role from DBA to Data Engineer.

**Common Entry Routes Highlighted**
- Systems administration -> data engineering
- Software/application development -> data engineering
- Direct entry is increasingly possible for new graduates today, but cross-domain experience is still very valuable.

**Why both systems and development backgrounds help**
- Systems background helps with storage, networking, performance, reliability, and operations.
- Development background helps with application data needs, producer/consumer patterns, and collaboration with developers and data scientists.

**Can you start from scratch?**
- Yes. Speakers emphasized data engineering is a field you can start directly.
- Key foundations:
   - Basic IT understanding
   - Guidance from a mentor
- A mentor helps prioritize what to focus on and what to defer.

**How professionals built capability (before and now)**
- Earlier path: books, hands-on database app building, volunteer/freelance projects, internships, then learning on the job.
- Current path: online courses, YouTube, web resources, and online degree programs (undergraduate and graduate).
- Practical experience (building real things) was repeatedly described as the biggest career accelerator.

**Path 2: Nonlinear career transition into data engineering**
- One speaker moved across education, nonprofits, BI analysis, and then into a data engineering role.
- They initially applied for a data scientist role and were rejected, but were identified as a fit for a data engineering opening.
- This highlights transferability of adjacent experience and the value of being open to unexpected opportunities.

**Key Takeaways**
- Data engineering has many entry points: direct, adjacent, and career-switch pathways.
- Business needs often drive tool expansion, which in turn reshapes roles into broader data engineering responsibilities.
- Hands-on project work plus continuous learning is more important than a perfectly linear background.
- Mentorship and curiosity significantly shorten the learning curve.


### Data Engineering Learning Path

Academic degrees in computer science or engineering are common entry points, but many data engineers are also self-taught.
Online programs and multi-course specializations from platforms like Coursera provide hands-on assignments and real-world projects to build skills.

Learners can focus on sub-domains such as data pipelines, distributed systems, or data architecture based on their current skills and goals.
Professional certifications and learning resources help non-graduates or those switching careers to gain data engineering skills.

Basic skills include programming, query languages, operating systems, and databases.
Gaining real-world experience through projects or entry-level jobs is important to advance to more complex roles in data engineering.

### Viewpoints: What Do Employers Look for in a Data Engineer

Employers evaluate data engineering candidates across a blend of **technical breadth**, **role fit**, and **soft skills**. There is no single universal checklist.

**No One-Size-Fits-All Profile**
- Hiring expectations vary by company, team, and role.
- Some roles prioritize broad exposure across many tools; others require deep expertise in a specific stack.

**Technical Skills Commonly Expected**
- Strong fundamentals in SQL, data modeling, and ETL/ELT methodologies.
- Programming ability, especially Python.
- Experience with relational databases (RDBMS) and NoSQL systems.
- Understanding of schema design and data architecture basics.
- Ability to work with diverse data formats and file types.
- Exposure to APIs, web scraping, and data ingestion from external sources.
- Familiarity with streaming data pipelines.
- Basic analytical skills for validating and interpreting data behavior.

**Data Movement and Integration Focus**
- Many employers value engineers who can move data across heterogeneous systems.
- Typical scenarios include pulling from RDBMS, NoSQL stores, and social platforms via APIs, then loading into analytical platforms (for example, Hadoop).

**Problem-Solving and Troubleshooting Mindset**
- Employers look for candidates who investigate issues by asking clarifying questions, not jumping to one preset fix.
- Example interview scenario: “The database is slow.” Strong candidates explore possible causes (workload, queries, infrastructure, data growth, dependencies) before proposing actions.

**Soft Skills That Stand Out**
- Curiosity and inquisitiveness.
- Clear communication and ability to collaborate across teams.
- Strong ownership and work ethic.
- Team fit and professional attitude.
- Love of continuous learning.

**Role Scope Depends on Company Size**
- Large organizations may allow narrower specialization (for example, ETL pipeline ownership).
- Startups and smaller teams often expect full-stack data engineering capability and broader responsibilities.

**Junior vs Senior Hiring Expectations**
- Junior roles: general technical fluency, learning ability, and soft skills often matter more than niche expertise.
- Senior roles: employers usually need specific, proven technical depth aligned to immediate business needs.

**How Candidates Demonstrate Readiness**
- Credentials (degree/certificate) help with initial screening.
- Differentiation comes from evidence of applied skill:
   - Real projects and portfolio work
   - Technical write-ups, presentations, or videos
   - Clear explanation of decisions, trade-offs, and outcomes
   - Signs of ongoing learning (courses, blogs, labs, experimentation)

**Bottom Line**
- Employers hire data engineers who combine core technical competence with curiosity, communication, problem-solving, and the ability to keep learning as tools and business needs evolve.


### Viewpoints: The Many Paths to Data Engineering

Data professionals emphasized that there is no single route into data engineering. People enter the field through formal education, shorter training programs, or by transitioning from adjacent technical and data roles.

**Formal and Alternative Learning Paths**
- A computer science or software engineering degree is a common route into data engineering.
- Degrees provide a strong foundation, but they require significant time and cost, and graduates often still need job-specific upskilling.
- Shorter options such as diploma programs, bootcamps, online courses, and certificate programs can also prepare learners for entry into the field.
- When choosing a program, evaluate its cost, duration, reputation, how current the content is, learner reviews, and whether the format matches your learning style.

**Common Career Transition Paths**
- System administrators can transition into data engineering by building strength in operating systems, infrastructure, and databases.
- Database administrators (DBAs) are often a natural fit because they already understand data storage, performance, and database operations.
- Automation engineers can move into data engineering because pipeline work depends heavily on automating repeatable processes.
- Data analysts can transition well because they already work closely with data, SQL, and reporting needs.
- Programmers and software engineers can move into data engineering by applying their coding and systems knowledge to data pipelines and platforms.
- ETL developers are also well positioned because ETL work closely overlaps with core data engineering responsibilities.

**What Helps Across All Paths**
- Strong knowledge of databases, data sources, and data formats is essential.
- The core goal is to use that knowledge to build reliable data pipelines and make data available for downstream use.
- Backgrounds in computer science and mathematics can shorten the learning curve, but they are helpful rather than mandatory.

**Why There Are So Many Paths**
- Data engineering is still a relatively new field.
- Different companies define the role differently, so entry requirements vary across organizations.
- Some people enter directly after graduation, while others transition from software engineering, business intelligence, system administration, helpdesk, or other nontraditional roles.

**Real-World Insight**
- One speaker described moving from non-technical nonprofit roles into business intelligence, building skills in SQL, data modeling, and databases, and then transitioning into data engineering.
- This shows that a strong computer science background is useful, but not required if you can build practical skills over time.

**Bottom Line**
- The most common entry directions are from the systems side and the developer side, but many adjacent roles can lead into data engineering.
- There is no perfect starting point; practical skills, continuous learning, and familiarity with data systems matter more than following one fixed path.


### Viewpoints: Advice to Aspiring Data Engineers

D'/ata professionals shared practical guidance for getting into data engineering and standing out early in your career.

**1. Build a Strong Technical Foundation First**
- Start with core fundamentals before chasing every new tool.
- Prioritize SQL, Python, data modeling, and ETL methodologies.
- Learn database internals and underlying data structures; understanding how systems work under the hood makes troubleshooting much easier.

**2. Prioritize Hands-On Practice**
- Practical experience is one of the strongest differentiators for aspiring data engineers.
- If you do not yet have a job or internship, create your own practice opportunities using open-source tools and online learning resources.
- Build personal projects, simulate real failures, and practice fixing them (for example, intentionally breaking a local database setup and recovering it).
- Treat troubleshooting practice as a core skill, not a side activity.

**3. Learn Breadth in Manageable Steps**
- Data engineering requires broad skill coverage across tools and platforms, which can feel overwhelming.
- Use a staged approach:
   - Master one relational database first.
   - Then learn at least one NoSQL database (for example, MongoDB, Cassandra, or Neo4j).
   - Add adjacent skills such as API integration and web scraping.
- Combine language families over time: SQL + at least one scripting/procedural language + one general-purpose programming language.

**4. Demonstrate What You Know Publicly**
- Credentials and certifications can help, but visible proof of ability is often more persuasive.
- Share projects, code, demos, and write-ups in public spaces:
   - GitHub repositories
   - Blog posts (LinkedIn or personal blog)
   - Talks, screencasts, or short instructional videos
- You do not need to be an expert to share; beginner-friendly content is valuable and reinforces your own learning.

**5. Join the Community and Give Back**
- Participate in meetups, professional groups, and peer communities to learn faster and build a network.
- Share lessons learned with others as you progress.
- Teaching and knowledge-sharing accelerate mastery and improve career visibility.

**6. Stay Curious and Keep Learning Continuously**
- Data engineering evolves quickly; tools and architectures change constantly.
- Adopt a long-term learning mindset and continuously update your skill set.
- Curiosity, consistency, and persistence are repeatedly highlighted as career multipliers.

**Bottom Line**
- Start with strong fundamentals.
- Build real projects and troubleshooting depth.
- Grow your stack in phases.
- Share your work and engage with the community.
- Keep learning continuously.

Following this approach helps aspiring data engineers become interview-ready and better prepared for real-world roles in a high-demand field.



