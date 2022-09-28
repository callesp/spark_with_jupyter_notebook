# spark_with_jupyter_notebook
Jupyter Notebook Python with pyspark environments, Spark cluster

## Usage

1. Start spark cluster with three workers.

   `docker-compose up --scale spark-worker=3`

2. Find the container name of jupyter notebook.

    `docker ps`

3. Get access url of jupyter notebook from container logs.

    `docker logs --tail 10 {notebook}`

    {notebook} represents contaienr name of pyspark jupyter notebook.

4. Open notebook url with your web browser.