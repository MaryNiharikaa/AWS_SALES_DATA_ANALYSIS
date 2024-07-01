# AWS_SALES_DATA_ANALYSIS
ARCHITETURE OF AWS DATA ANALYSIS:
![image](https://github.com/MaryNiharikaa/AWS_SALES_DATA_ANALYSIS/assets/167513419/b8ab45d7-9bca-48c7-bacf-16e986e42076)

## STEPS PERFORMED FOR SALES DATA ANALYSIS:
1.CREATING IAM USER AND LOGIN
 -Created I AM User Data-Analysis
 -Login as I AM User to perform Data Analysis

2.UPLOADING DATA TO AMAZON S3
 -Created Bucket S3-data-analysis- sales
 -Created folder as sales-data
 -Uploaded Objects Sales.CSV

3.DATA CRAWLING WITH AWS GLUE
  * Creating Crawler
  * Adding source to the crawler
  * Creating Database add to the crawler
  * Creating I am Role
  * Crawler Running
  * Schema Information in Aws Data Catalog
  * Partitions on Aws Data Catalog

4.QUERYING DATA WITH AMAZON ATHENA 
  * Querry Setup in Athena
  * Querry Result in Athena
  * Filtering with partitions
  * Querry Logs saved in S3

5.VISLAIZING DATA WITH AMAZON QUICKSIGHT
 -Importing Data from Athena
 -Reporting the sales visualization

# CONCLUSION
The seamless integration of AWS Athena and AWS Glue enables organizations to leverage schema and crawled data for efficient and optimized database queries. By combining the power of metadata-driven analysis and query execution, businesses can uncover valuable insights, make informed decisions, and drive success in the data-driven era.


OUTPUT FROM QUICKSIGHT FROM SALES DATA_ANALYSIS:
![image](https://github.com/MaryNiharikaa/AWS_SALES_DATA_ANALYSIS/assets/167513419/bf1e9544-5688-43a9-8b8e-274246953cd8)
