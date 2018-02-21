1. Define “Data mining”. Enumerate five example application that can benifit by using the Data Mining.

Definition: In simple words, data mining is defined as a process used to extract usable data from a larger set of any raw data. It implies analysing data patterns in large batches of data using one or more software. Data mining has applications in multiple fields, like science and research. As an application of data mining, businesses can learn more about their customers and develop more effective strategies related to various business functions and in turn leverage resources in a more optimal and insightful manner. This helps businesses be closer to their objective and make better decisions. Data mining involves effective data collection and warehousing as well as computer processing. For segmenting the data and evaluating the probability of future events, data mining uses sophisticated mathematical algorithms. Data mining is also known as Knowledge Discovery in Data (KDD). 

Description: Key features of data mining: 

• Automatic pattern predictions based on trend and behaviour analysis. 

• Prediction based on likely outcomes. 

• Creation of decision-oriented information. 

• Focus on large data sets and databases for analysis. 

• Clustering based on finding and visually documented groups of facts not previously known. 



2. Explain Data Mining as a step of KDD ( Knowledge Discovery ). Give architecture of typical Dataming System.

What is Knowledge Discovery?
Some people don’t differentiate data mining from knowledge discovery while others view data mining as an essential step in the process of knowledge discovery. Here is the list of steps involved in the knowledge discovery process −

Data Cleaning − In this step, the noise and inconsistent data is removed.

Data Integration − In this step, multiple data sources are combined.

Data Selection − In this step, data relevant to the analysis task are retrieved from the database.

Data Transformation − In this step, data is transformed or consolidated into forms appropriate for mining by performing summary or aggregation operations.

Data Mining − In this step, intelligent methods are applied in order to extract data patterns.

Pattern Evaluation − In this step, data patterns are evaluated.

Knowledge Presentation − In this step, knowledge is represented.

The following diagram shows the process of knowledge discovery −



3. Explain Major issues in Data Mining. 

Mining Methodology and User Interaction Issues
It refers to the following kinds of issues −

Mining different kinds of knowledge in databases − Different users may be interested in different kinds of knowledge. Therefore it is necessary for data mining to cover a broad range of knowledge discovery task.

Interactive mining of knowledge at multiple levels of abstraction − The data mining process needs to be interactive because it allows users to focus the search for patterns, providing and refining data mining requests based on the returned results.

Incorporation of background knowledge − To guide discovery process and to express the discovered patterns, the background knowledge can be used. Background knowledge may be used to express the discovered patterns not only in concise terms but at multiple levels of abstraction.

Data mining query languages and ad hoc data mining − Data Mining Query language that allows the user to describe ad hoc mining tasks, should be integrated with a data warehouse query language and optimized for efficient and flexible data mining.

Presentation and visualization of data mining results − Once the patterns are discovered it needs to be expressed in high level languages, and visual representations. These representations should be easily understandable.

Handling noisy or incomplete data − The data cleaning methods are required to handle the noise and incomplete objects while mining the data regularities. If the data cleaning methods are not there then the accuracy of the discovered patterns will be poor.

Pattern evaluation − The patterns discovered should be interesting because either they represent common knowledge or lack novelty.

Performance Issues
There can be performance-related issues such as follows −

Efficiency and scalability of data mining algorithms − In order to effectively extract the information from huge amount of data in databases, data mining algorithm must be efficient and scalable.

Parallel, distributed, and incremental mining algorithms − The factors such as huge size of databases, wide distribution of data, and complexity of data mining methods motivate the development of parallel and distributed data mining algorithms. These algorithms divide the data into partitions which is further processed in a parallel fashion. Then the results from the partitions is merged. The incremental algorithms, update databases without mining the data again from scratch.

Diverse Data Types Issues
Handling of relational and complex types of data − The database may contain complex data objects, multimedia data objects, spatial data, temporal data etc. It is not possible for one system to mine all these kind of data.

Mining information from heterogeneous databases and global information systems − The data is available at different data sources on LAN or WAN. These data source may be structured, semi structured or unstructured. Therefore mining the knowledge from them adds challenges to data mining.
