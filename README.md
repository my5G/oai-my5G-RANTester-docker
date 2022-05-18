# oai-my5G-RANTester-docker
This repository contains the instructions to running OAI-CN in version v1.3.0 and my5G-RANTester(a gNB/UE simulator)

### Instructions 

## Build the image 
- git clone https://github.com/my5G/oai-my5G-RANTester-docker.git
- cd oai-my5G-RANTester-docker
- docker build -f nf_tester/Dockerfile --tag my5grantester:latest .

## Execute the tester
- docker-compose up -d 

