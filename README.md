# Data-Science Cheatsheet

+ **Open-Source Software** - software source code is freely available to anyone for download, alteration, and republishing. Open source software code is generally supported by a mix of paid and volunteer professionals who contribute changes back to the community. Contrasts with proprietary software source code, which is owned by an individual or an organization and tightly restricted (usually for profit).

+ **Data warehouse/Data Mart/Data Store** - a centralized repository of integrated data, organized for easily accessibility in support of business intelligence and operational decision-making.

+ **Metadata** - data that provides information on other data. This could be data on the structure of a dataset or a description of the content of a particular dataset. 

+ **Machine readable data** - data in a format that allows it to be easily read by a computer program, either by being marked by explanatory tags (like HTML) or in a structured format that allows it to be easily parsed (XML, JSON)

+ **Relational database** - a data storage system consisting of multiple data tables linked together with index values. While relational databases are useful for reliably storing and processing data, they often require a good deal of design and planning to function properly.  

+ **SQL** - **S**tructured **Q**uery **L**anguage. A special programming language for adding, managing, and retrieving data in relational databases

+ **PostgreSQL** - an open-source relational database management system. Like most relational database systems, PostgreSQL uses a slightly varied version of standard SQL as the means to add, manage, process, and retrieve data stored in tables.

+ **NoSQL/non-relational databases** - a data storage system that doesn't store data in relational structure, often as a document store. NoSQL databases require far less design and planning than relational databases and can be more scalable but suffer from issues of data consistency and reliability. 

+ **MongoDB** - one of the most-used open-source NoSQL database systems. Instead of using tables, data is stored as a singular document with key-value pairs. Raw data can be easily loaded into the database and easily retrieved, but the data isn't as well indexed or easy to join with other data compared to relational database systems.

+ **Data Size: Petabyte, Terabyte, Gigabyte, Megabyte** (in relation to one another)
    + 1 Petabyte = 1,024 Terabytes (20 million four-drawer filing cabinets filled with text)
    + 1 Terabyte = 1,024 Gigabytes (1,500 CD-ROMs)
    + 1 Gigabyte = 1.024 Megabytes (7 minutes of HD-TV video)

+ **Algorithm** - A precise set of instructions required to accomplish a task. Roughly broken down into three components: inputs, operation, output. Each step in the operation must be clearly defined and work the same with any input.

+ **Data Model(ing)/Predictive Modeling** - using data collected about events or phenomena in the past to predict future outcomes. Predictive models can be constructed using any of a number of algorithms, either singularly or together, to achieve the desired outcome. A model's predictive power is assessed using various measures that help determine relative performance of one model over another.

+ **Machine learning** - similar to predictive modeling, but more specifically focused on the use of computer systems to create predictive models with data.

+ **Model Tuning** - Altering initial model parameters to achieve a better or more desirably result with the predictive model.

+ **Regression/Logistic Regression** - A predictive modeling technique that relies on the linear relationship between two variables to make predictions when the value for only one of the variables is known. For example, given a known relationship between height and weight in the general population, it's possible to predict an individual's weight given only his/her height.

+ **Classification** - Like regression, a supervised predictive modeling technique using a known relationship between attributes to predict the category of an unseen instance. For example, using information about a borrower, including their income, age, credit score, and other information, to predict whether they're at risk of defaulting on their loan. 

+ **Clustering** - an unsupervised machine learning technique for mathematically determining groups of objects that are similar to one another and different from the objects in other groups.

+ **Natural Language Processing** - a set of machine learning techniques to model the meaning contained in human language. This includes techniques to provide automatic translations, determine the sentiment of statements, and recognize handwriting.

+ **AdaBoost** - a machine learning technique combining the output of multiple machine learning algorithms to achieve a better result. 

+ **Random Forests** - a machine learning algorithm that uses a collection of various predictive models constructed on a random selection of features from the training data.

+ **R** - a freely available, open-source statistical programming language used for analyzing and visualizing data. It's very popular among academic and professional statisticians, who contribute packages that provide advanced statistical functionality to the language. It can be run via the commandline or via a graphic integrated development environment called RStudio.

+ **Python** - an open-source general purpose programming language with widely used packages for processing, analyzing, and visualizing data. It can be run in a variety of environments and in addition to working with data, can be used to perform a variety of other programming tasks.

+ **GitHub.com** - a web-based code storage and version control service. The website hosts a number of open-source projects and provides a graphic interface for managing projects and contributions from developers. As a "social coding" site, Github offers a number of tools for developers, designers, and users to collaborate and share around code, including bug tracking, feature requests, and wikis for each project. Users can also host webpages on Github.

+ **Big Data** - any sufficiently large data set requiring a fundamentally different approach to storing, processing, and analyzing for insights and understanding. For some, this is data too big to fit into Excel >1,048,576 rows. For others, it's data that can't be easily read into available memory and processed with programming languages such as R or Python, requiring distributed processing in order to analyze.

+ **MapReduce** - a distributed processing algorithm that divides large data sets across a number of different computing nodes (called mappers) for processing and then aggregates the results across another set of computing nodes (called reducers, which can be repurposed mappers) to arrive at a final result. Being distributed, the operation runs in parallel rather than sequentially (one step at a time). Decreasing the time to process a data set is done by increasing the number of computing nodes, which can be reasonably basic in terms of capabilities, rather than having one or a few very powerful computers to process the data.

+ **Hadoop** - a framework for running MapReduce jobs that manages the operation of computing nodes, including ensuring the mapping jobs complete, data from the mappers is properly sorted, sorted data is provided to the proper reducers, and the reducer jobs complete. The framework is written in Java but supports a variety of other languages. 

+ **API** - **A**pplication **P**rogramming **I**nterface. A set of protocols for how computer programs should interact. Through APIs, applications are able to easily share data regardless of what language they're using or how they're built so long as they conform to basic standards. APIs make computing systems more flexible and adaptable, allowing other systems to easily interact with them.

+ **ETL** - **E**xtract, **T**ransform, and **L**oad. The basic steps in processing raw data in order to make it usable for analysis and operational decision making in a data warehouse or other data storage application. This process often involves correcting data errors, normalizing data inputs, and ensuring the data is interoperable with other data sources.

+ **Cloud Computing** - on-demand computing using Internet-based resources. Cloud computing includes storage systems, data processing, and platform services that provide on-demand computing resources to users. These resources are managed (power, heating, cooling, updates, security, etc) by the cloud services providers rather than the user. While the resources are shared, within the software used, it's possible to guarantee privacy, security, and data integrity while consolidating overhead and maintenance. 

+ **Structured data** - is hierarchical data with a clear organization that can easily be read into a database or application for processing, storage, and retrieval.

+ **Semi-structured data** - is data with organization properties that can be used to easily parse and store the data into a structured format for database or application for processing, storage, and retrieval.

+ **Unstructured data** - is data with no hierarchical structure or organization that would allow it to be easily processed and stored by a database or application. This includes images, emails, audio files, and other text documents.

+ **Structured/Semi-Structured vs. Unstructured Data** - by far the most prevalent type of data is unstructured data, with only a very small percentage of data produced being truly structured. Even semi-structured data (ie data in CSV, JSON, or XML formats) accounts for a small percentage of the data that's produced. Unstructured data is difficult to easily parse, process, store, and retrieve.

