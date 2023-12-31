# YT-data-analysis-pipeline
Project: YouTube Data Analysis Pipeline

In the YouTube Data Analysis Pipeline project, I designed and implemented a robust architecture to analyze YouTube video data for a data-driven campaign. The key tasks accomplished in this project include:

--> User Management and AWS CLI: Created an IAM user for administrative access and installed the AWS CLI for seamless management of AWS services.

--> Data Storage and Management: Set up an S3 bucket to store and manage YouTube video data, ensuring secure and scalable storage.

--> Data Cataloging with Glue: Utilized AWS Glue to build a data catalog, enabling efficient organization and query capabilities for the YouTube video data.

--> Data Analysis with Athena: Leveraged Athena, an interactive query service, to analyze YouTube data using SQL queries. This allowed for the categorization of videos based on comments and statistics.

--> Factors Affecting Video Popularity: Conducted in-depth analysis using Athena to identify the factors influencing the popularity of YouTube videos, aiding in campaign strategy planning.

--> Data Preprocessing and Cleaning: Implemented an ETL (Extract, Transform, Load) job using Lambda functions to preprocess and clean the data, ensuring data quality and reliability.

--> Reporting and Visualization with QuickSight: Built a reporting version of the data and utilized AWS QuickSight for creating insightful visualizations. These visualizations showcased meaningful patterns and trends in the YouTube video data.

--> The primary objective of the YouTube Data Analysis Pipeline project was to provide the necessary infrastructure and tools to analyze YouTube video data and answer key questions related to video categorization and factors impacting video popularity.

The Architecture diagram for the above project is given below : (Note: not all the landing technologies were used, some are just for showing the capability of the pipeline which can be built)

![image](https://github.com/tdsingh9/Yt-data-analysis-pipeline-/assets/86833210/ec43eed0-d2c9-46c4-a264-1a336189ae4a)



Also, find the architecture diagram for the cleansing process below.

![image](https://github.com/tdsingh9/Yt-data-analysis-pipeline-/assets/86833210/3055586c-f04f-448f-b079-b6d85c423d05)


