# subjects
Hibernate
Duration: 1 weeks

Goal: Use Hibernate to create mapping for tables and to manage connections

Task:
1. Configure Hibernate connection
2. Create Domain mapping using Annotations
3. Generate DB schema from mappings
4. Implement Generic DAO (or Data Access Object)
5. Test CRUD using DAO and POJO mappings

Evaluation: Code review

Resources:
https://www.mkyong.com/tutorials/hibernate-tutorials/

Details: Think about domain, integrate with other parts

Spring
Duration: 2-3 weeks

Goal: Use Spring for IoC, using both XML and Annotations

Task:
1. Create Spring Application with XML config
2. Add DB connection
3. Configure Hibernate
4. Create Annotation based Spring App
(NEW) 5. Study AOP

https://www.youtube.com/watch?v=e8aSyQo0nHo
https://www.mkyong.com/tutorials/spring-tutorials/
https://docs.spring.io/spring-framework/reference/core/aop.html

Details: Think about domain, integrate with other parts

Spring Batch
Duration: ~1 week

Goal: Know concepts, Create Spring Batch job with custom processor and tasklet

Task:
1. Create Spring Batch Application with annotations/XML configutation, see resources
2. Create Job to import csv file to DB, same logic as in task 6 from document "Clean Code & Refactoring", but now with Spring Batch

Please select a csv file bigger than 5 MB from here: https://www.stats.govt.nz/large-datasets/csv-files-for-download/
3. Add validation processor
4. Add Tasklet to move csv file after importing, into another folder
5*. (optional) Create another Job to read data from two DB Tables, and write to flat csv file.

spring batch csv file to DB [XML CONFIG]
spring batch DB to csv file [ANNOTATIONS CONFIG]

Evaluation: Code review

Resources:
https://docs.spring.io/spring-batch/trunk/reference/html/spring-batch-intro.html
https://spring.io/guides/gs/batch-processing/
https://www.javacodegeeks.com/2015/03/spring-batch-tutorial.html
http://www.mkyong.com/tutorials/spring-batch-tutorial/

Details: Use existing Validator from JUnit project to validate rows in custom Processor.
