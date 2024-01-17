This project is an integration of my previous weather monitoring project into Airflow, and so is largely constructed the same, so this readme will not be too in-depth. The major differences are that the weather information gathering process is now a function, as this is how airflow selects tasks to be carried out, and it now points to a MySQL docker container running as part of the airflow space.

Also worth noting that the dag function and the ETL function would normally be separated. They were bundled together in this instance for convenience.
