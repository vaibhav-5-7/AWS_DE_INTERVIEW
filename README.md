# AWS_DE_INTERVIEW
aws data engineer interview questions
AWS DATA ENGINEER INTERVIEW MASTER CHECKLIST

========================================
1. PROJECT & ARCHITECTURE
========================================

1. Explain your project end-to-end.
2. Explain the complete data flow.
3. Why did you choose AWS services used in your project?
4. What problem was the pipeline solving?
5. How do business users consume the data?
6. How do you monitor the pipeline?
7. How do you handle failures?
8. How do you reprocess failed data?
9. What challenges did you face?
10. What would you improve in your architecture?

========================================
2. DATA INGESTION & MIGRATION
========================================

11. How do you move data from RDBMS to S3?
12. How do you move data from S3 to Redshift?
13. How do you move data from Redshift to S3?
14. How do you migrate on-premise data to AWS?
15. How do you migrate 10TB of data?
16. How do you validate migrated data?
17. What migration challenges can occur?
18. How do you handle schema conversion during migration?
19. Full Load vs Incremental Load?
20. How do you implement incremental loads?

========================================
3. CDC & DATA PROCESSING
========================================

21. What is CDC?
22. How do you implement CDC?
23. Timestamp CDC vs Log-based CDC?
24. How do you handle duplicate records?
25. How do you handle late arriving data?
26. How do you implement idempotency?
27. How do you perform backfills?
28. Batch vs Streaming?
29. How do you validate incoming files?
30. How do you perform reconciliation?

========================================
4. AMAZON S3
========================================

31. What is S3?
32. Why is S3 highly durable?
33. Why does S3 use global namespace?
34. What are S3 storage classes?
35. What is Versioning?
36. What are Lifecycle Policies?
37. What is Cross Region Replication?
38. What are S3 Event Notifications?
39. How do you partition data in S3?
40. How do you secure S3 buckets?
41. How do you optimize S3 for Athena?

========================================
5. IAM
========================================

42. What is IAM?
43. User vs Group vs Role?
44. What is IAM Policy?
45. What is Assume Role?
46. What is Cross Account Access?
47. What is Least Privilege Principle?
48. IAM usage in Glue?
49. IAM usage in Lambda?
50. IAM usage in Redshift?

========================================
6. LAMBDA
========================================

51. What is Lambda?
52. How does Lambda work?
53. What can trigger Lambda?
54. What are Lambda limitations?
55. What is Cold Start?
56. How do you monitor Lambda?
57. How do you retry failed Lambda executions?
58. How do you chain Lambdas?
59. What if processing takes longer than 15 minutes?
60. Lambda vs Glue?

========================================
7. AWS GLUE
========================================

61. What is AWS Glue?
62. What is Glue Catalog?
63. What is Glue Crawler?
64. How does schema discovery work?
65. What are Glue Jobs?
66. What are Dynamic Frames?
67. Glue vs Lambda?
68. Glue vs EMR?
69. Glue vs Databricks?
70. How does Glue handle schema evolution?
71. How do you detect schema changes?
72. How does Glue Catalog integrate with Athena?

========================================
8. ATHENA
========================================

73. What is Athena?
74. Athena vs Redshift?
75. How does Athena read data?
76. How is Athena priced?
77. What is Partitioning?
78. What is Bucketing?
79. What is MSCK REPAIR TABLE?
80. Does Athena detect partitions automatically?
81. How does Athena use Glue Catalog?
82. How do you optimize Athena queries?
83. How do you reduce Athena costs?

========================================
9. REDSHIFT
========================================

84. What is Redshift?
85. Explain Redshift Architecture.
86. What is MPP?
87. What is Columnar Storage?
88. What are Distribution Styles?
89. What are Sort Keys?
90. What is Spectrum?
91. What is COPY Command?
92. What is VACUUM?
93. What is ANALYZE?
94. How do you optimize Redshift?
95. Redshift vs Athena?

========================================
10. AIRFLOW
========================================

96. What is Airflow?
97. What is a DAG?
98. How does scheduling work?
99. What are Operators?
100. How does Retry Logic work?
101. How do you handle Airflow failures?
102. How do you monitor Airflow?
103. How do you trigger dependent jobs?
104. Airflow vs Step Functions?
105. Airflow vs EventBridge?

========================================
11. EMR (BASIC)
========================================

106. What is EMR?
107. When would you use EMR?
108. EMR vs Glue?
109. Spark on EMR?
110. Hive on EMR?
111. Hadoop on EMR?
112. How do you scale EMR clusters?

========================================
12. DATA MODELING
========================================

113. Fact Table vs Dimension Table?
114. Star Schema vs Snowflake Schema?
115. What is Surrogate Key?
116. What is Natural Key?
117. What is SCD Type 1?
118. What is SCD Type 2?
119. What is Table Grain?
120. Design an Ecommerce Data Model.
121. Design a Social Media Data Model.
122. Design a Stock Market Data Warehouse.

========================================
13. SECURITY
========================================

123. How do you secure PII data?
124. Encryption at Rest vs In Transit?
125. What is KMS?
126. What is SSE-S3?
127. What is SSE-KMS?
128. How do you audit data access?
129. What is CloudTrail?
130. How do you secure S3 buckets?
131. How do you implement data masking?
132. How do you implement RBAC?

========================================
14. SCENARIO QUESTIONS
========================================

133. Schema changes unexpectedly. What do you do?
134. Glue job fails in production. What do you do?
135. Redshift query becomes slow. How do you troubleshoot?
136. File arrives twice in S3. How do you prevent duplicates?
137. Pipeline partially loads data. How do you recover?
138. Migration validation fails. What do you do?
139. Missing Athena partition. How do you fix it?
140. Business users report incorrect numbers. How do you investigate?

========================================
MOST IMPORTANT QUESTIONS
========================================

Project Architecture
RDBMS → S3
S3 → Redshift
CDC
Incremental Loads
Reconciliation
Schema Evolution
Schema Drift
S3 Security
IAM Roles
Lambda Triggers
Lambda Limits
Glue Catalog
Glue Crawlers
Glue vs EMR
Athena vs Redshift
Athena Partitions
MSCK REPAIR TABLE
Redshift Distribution Keys
Redshift Sort Keys
Airflow DAG
Airflow Retry
Fact vs Dimension
Star vs Snowflake
SCD Type 2
PII Security
Migration Strategy
Batch vs Streaming
Monitoring Strategy
Failure Recovery
