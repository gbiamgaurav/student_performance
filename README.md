
# End-to-End ML Project for Student Performance

## Steps

1. Create environment

`conda create -p stud python==3.8 -y`

2. Create setup.py and requirements.txt

`pip install -r requirements.txt`


## Deployed app: [find the app here](http://studperformance-env-1.eba-hj7jm6jt.us-east-1.elasticbeanstalk.com/predictdata)



AWS Steps

1. Create an IAM User
2. Setup the Policy Access - 
3. Download the access key

Create the repo :- 794696279387.dkr.ecr.us-east-1.amazonaws.com/stud-performance

## Docker setup in EC2

### Optional

sudo apt-get update -y

sudo apt-get upgrade


### Required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker
