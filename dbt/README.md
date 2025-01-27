### Goal: Transforming the raw data into more Analytical ready data by using dbt and BigQuery


What is dbt? 
- dbt stands for data build tool. It's a transformation tool which allows us to process raw data in our Data Warehouse into transformed data which can be later used by Business Intelligence tools and any other data consumers.

dbt also allows us to introduce good software engineering practices by defining a deployment workflow:
- Develop models
- Test and document models
- ploy models with version control and CI/CD.

In this project, I have done all the above three steps mentioned.

#### How are we going to use dbt?
- Using the raw data present in BigQuery, we are going to set these as source tables and create stage tables and finally loading fact and dimensional tables into BigQuery. The flow of the transformation is shown in the below lineage graph.

![dbt_lineage](https://user-images.githubusercontent.com/41874704/233732606-7ea74aaf-5c47-405a-bd8d-41bf9d1c7d4d.png)

### After deploying and running in production, the schema and tables look like below

![dbt_production](https://user-images.githubusercontent.com/41874704/233494094-9c4977c0-8865-4bfa-bf88-a17228f5dbc9.png)

