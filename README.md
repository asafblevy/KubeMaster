# KubeMaster
- Kubernetes project built on a Minikube cluster
- Cluster is built from Jenkins , Nexus and SonarQube pods
- Pipeline uses maven to compile a git project, tests it on SonarQube, uploads the war file to Nexus, creates a Docker image and pushes it to nexus.
- Make sure the check the YAML files and configure them to your own needs. 
