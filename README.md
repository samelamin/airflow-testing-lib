# Airflow Testing
This library is aimed at testing airflow dags

The orignal goal was to run a DAG inmemory and assert on the results. Ideally we want to read in a file with a schema, run the dag then assert that the output schema is as expected. Also would be good to assert on counts 
