# Hadoop Word Count

## Instalación de hadoop 

- https://hadoop.apache.org/docs/current/hadoop-project-dist/hadoop-common/SingleCluster.html
- https://mirrors.ucr.ac.cr/apache/hadoop/common/hadoop-3.2.1/hadoop-3.2.1.tar.gz

## Código del ejemplo

- https://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html#Example:_WordCount_v1.0

## Ejecución

Una vez compilado el proyecto y generado el `.jar`:

```bash
	$ [PATH_TO_HADOOP_FOLDER]/bin/hadoop jar target/wordCount-1.0.jar wordCount.WordCount input output
	$ [PATH_TO_HADOOP_FOLDER]/bin/hadoop fs -cat
```