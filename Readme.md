# Autogen Data Engineer Interview

Create a powerful semantic search engine from scratch in under 40 minutes!

### Guide

## VS Code

- Preferably the host would start a Live Share session in VS Code and send the link to the participant to be able to pair on the project.
- Tight time limits are set for each part of the assigment to make sure the participant gets a chance at answering all sections.

## Docker

Differences in versions between machines can sometimes cause issues, so you may wish to run the notebook in a docker image. If so,
follow the steps below:

- From the root of this directory, run the command `docker-compose up --build`
- Once the docker image has built, a jupyter notebook session will be available in your browser by navigating to `localhost:8888`
- This image will have all the dependencies defined in `./requirements.txt` installed
- If needing to install further dependencies, this can be done using the notebook by running this command in a cell: `! pip install <dependency>` 