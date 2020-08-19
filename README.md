# airflow-helm

This repository will guide to install apache airlow using helm charts in eks





Details about Jenkins pipeline design:

This job is for pipeline script of airflow eks deployment. we trigger it manually when we need to update the docker image of airflow

Perquisites:
* static Jenkins agent should run on eks cluster so that it picks agent based on cluster/environment
* static Jenkins agent should have helm, kubectl, docker, Jenkins agent jar and swarm client 
