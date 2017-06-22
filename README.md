## docker.uwsgi-nginx-flask-cassandra-spark-emperor ##

Base on  **[tiangolo/uwsgi-nginx:python2.7](https://github.com/tiangolo/uwsgi-nginx-docker)**, we also installed following software into container for use.

- uwsgi
- nginx
- flask
- spark
- pandas
- cassandra

### Usage ###

To run it:

> docker run -d -p 8899:80 --name api -v {folder}:/app cutejaneii/docker.uwsgi-nginx-flask-cassandra-spark-emperor
