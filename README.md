<include
(https://app.circleci.com/pipelines/github/phat181999/uda-project4?branch=circleci-project-setup),
(https://app.circleci.com/pipelines/github/phat181999/uda-project4/3/workflows/f814507f-416f-414f-a345-5e87a15afede/jobs/3)>

Requirements
Python 3.10

you can running app using command line python3 app.py into ./devops

START

1. Install dependencies
   set up the environment by running make setup and stand from home go to .devops
   run make install

2. Run Docker container
   create script in run_docker.sh and run automation file using script ./run_docker.sh

create script to upload docker upload_docker.sh and run automation file using script ./upload_docker.sh

3.Upload to Docker Hub
create script in upload_docker.sh and run automation ./upload_docker.sh
and upload to dockerhub

3. Kubernetes
   create script in run_kubernetes.sh and run automation ./run_kubernetes.sh

you can check if the image already build using: curl localhost:{`yourport`} or using scrip ./make_prediction.sh

running CI/CD via file config.yml: CircleCI configuration file.

running CI on branch circleci-project-setup
