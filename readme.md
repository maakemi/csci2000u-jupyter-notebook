# CSCI2000U Jupyter Notebook Image - Fall 2021

This repository contains a Jupyter Notebook environment with all the required packages for the **Scientific Data Analysis** course.

## Getting Started

On Ubuntu

1.	Install **Docker** on Ubuntu: https://docs.docker.com/engine/install/ubuntu/ 
  - 	Make sure you can run: `$ sudo docker run hello-world`
    - 	You might need to start docker first with: `$ sudo dockerd`
    - 	And then use another Ubuntu terminal to run the hello-world
2.	Install Docker compose: https://docs.docker.com/compose/install/ 
3.	Download, clone, or start a repository from the jupyter course repo template (recommended)
    - https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template.
5.	Go into your local repo of this project
6.	Start the container with your jupyter environment: `$ sudo docker-compose up`
7.	Access the jupyter notebook from your browser using any of the given URLs from the previous Step.


**Note:** You should **not** make changes to the `Dockerfile` or the `docker-compose.yml` file.

If you are using a different OS, you would still need to install docker from Step 1 and 2 for your platform. 
You should be responsible for searching the equivalent OS commands for your setup.
