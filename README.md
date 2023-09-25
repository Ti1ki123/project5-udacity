[![CircleCI](https://dl.circleci.com/status-badge/img/gh/Ti1ki123/project5-udacity/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/Ti1ki123/project5-udacity/tree/main)
# DevOps_Project5

This project follows the following procedures:

1.Establish a cluster by executing the eks_create_cluster.sh script with configurations from the cluster.yml file.
2.Deploy the application using the config.yml file.
3.Specifics:
CircleCI conducts lint checks on multiple files.
Build and upload the Docker image to Docker Hub.
Deploy the initial "green" environment.
Await manual approval.
Deploy the updated "blue" environment.
Remove the previous "blue" environment.
