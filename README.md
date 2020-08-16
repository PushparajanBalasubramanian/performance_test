Simple Travel Agency - Performance Testing 

# Running JMeter Tests in Azure Pipelines using Docker
This project shows an example of how to run a JMeter load test using a Docker container. 
(https://github.com/justb4/docker-jmeter) 

#Steps to follow
################
0) Download from Github and Create a local repository (performance_test). Commit it using GitGUI

1) Push your local repository into your Azure devops repository

2) Create a pipeline using "Azure Repos Git" - YAML 

3) Select the azure-pipeline.yml (present in your repository master)

4) Run the Pipeline

5) Happy Load testing !

# Troubleshooting
##################
If your scripts are not running, 

* git update-index --chmod=+x run.sh
* git update-index --chmod=+x test.sh

And Push the updated scripts and rerun the pipeline.

# Test Reports
###################
In Azure DevOps, Under Run JMeter tests -> 1 artifact produced

Please download and see all the reports
