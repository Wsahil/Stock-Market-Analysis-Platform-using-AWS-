# Stock Market Analysis Platform using AWS
This project aims to leverage the power of Amazon Web Services (AWS) for comprehensive stock market data analysis. By integrating various AWS services, we establish a robust and scalable infrastructure for data storage, preprocessing, querying, and visualization, enabling informed decision-making and strategic insights in the finance sector.

## Project Overview

- **Data Source**: Stock market data obtained from prominent companies, including Apple Inc., Microsoft Inc., Qualcomm Incorporated, and Advanced Micro Devices Inc (AMD).
- **AWS Services Utilized**: Amazon S3, AWS Glue, AWS Glue Data Catalog, AWS Crawler, Amazon Athena, Amazon QuickSight
- **Key Objectives**:
  - Store and manage stock market data using Amazon S3
  - Automate data preprocessing and schema inference with AWS Glue Crawlers
  - Query and analyze data using Amazon Athena's serverless SQL querying capabilities
  - Visualize insights and generate interactive dashboards with Amazon QuickSight

## Project Implementation

1. **Data Preprocessing**: The raw stock market data undergoes a meticulous cleaning process, involving data merging, formatting transformations, and extraction of time-based features, ensuring consistency and analysis-readiness.

2. **AWS Services Configuration**:
   - **Amazon S3**: Set up an S3 bucket for storing raw and processed data, with defined access controls and permissions.
   - **AWS Glue Crawlers**: Configured AWS Glue Crawlers to automatically scan data sources, infer schema, and populate the Glue Data Catalog with metadata.
   - **Amazon Athena**: Created a database and tables within Athena, enabling seamless SQL querying and analysis of the cataloged data.
   - **Amazon QuickSight**: Established a connection to the Glue Data Catalog, defined datasets, and designed interactive dashboards for data visualization.

3. **System Architecture**:
![image](https://github.com/Wsahil/Stock-Market-Analysis-Platform-using-AWS-/assets/71370836/e539d1d4-fefb-4349-8506-1f2437432bec)


4. **Key Findings and Lessons Learned**:
   - Mastered the integration of various AWS tools for end-to-end data processing
   - Gained insights into data preprocessing and the importance of clean, well-structured data
   - Experienced the scalability and economic efficiency of cloud resources
   - Streamlined workflows through seamless integration of AWS services

**Quicksight Visualizations**:

![image](https://github.com/Wsahil/Stock-Market-Analysis-Platform-using-AWS-/assets/71370836/d6035ae1-b7f3-4d49-a62c-89facdca44f1)
![image](https://github.com/Wsahil/Stock-Market-Analysis-Platform-using-AWS-/assets/71370836/d2548aa4-4bda-41c7-9eff-3547c3d724a6)
![image](https://github.com/Wsahil/Stock-Market-Analysis-Platform-using-AWS-/assets/71370836/394436eb-8b35-4306-989e-f7d9c4b0aa86)


5. **Future Enhancements**:
   - Integrate AWS SageMaker for machine learning and predictive analytics
   - Adopt real-time data processing with AWS Lambda and Kinesis
   - Expand visualization tools for more interactive and dynamic data exploration

## Getting Started

To get started with this project, follow the instructions in the project report for configuring the required AWS services, preprocessing the data, and executing the analysis and visualization workflows.
