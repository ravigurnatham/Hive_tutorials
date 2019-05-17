# Hive_tutorials
![alt text](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2017/09/data-processing-workflow-in-hive.jpg)

    Via[https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2017/09/data-processing-workflow-in-hive.jpg]

1. User submit the query to hive

2. driver creates a hive session and sends it to the compiler to create an execution plan

3. Compiler will check with the metastore whether required tables, columns exist or not. If exists creates an execution plan 
   and sends it to the driver.
   
4. Driver will sends the exuction plan to execution engine.

4. Task will be executed by respectrive data nodes and result will be sent to the driver at the end.
