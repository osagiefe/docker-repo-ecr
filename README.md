# docker-repo-ecr
A docker jenkins project. An attempt to build a docker image and push it to Elestic Container Registry using jenkins pipeline. However, the jenkins software will be deployed using terraform infrastructure as code
# Error and challenges on project
+ aws ecr get-login-password --region us-east-1
/var/lib/jenkins/workspace/docker-repo-ecr@tmp/durable-895770f1/script.sh.copy: 1: aws: not found
+ docker login --username AWS --password-stdin ***********.dkr.ecr.us-east-1.amazonaws.com
/var/lib/jenkins/workspace/docker-repo-ecr@tmp/durable-895770f1/script.sh.copy: 1: docker: not found
# Solution
![Image](https://github.com/user-attachments/assets/f0cc72dc-376c-4e4a-9c8a-530d5e8e6aa6)