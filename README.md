# quakeworx_workshop_2025
Open Science and Research Computing Workshop Notebook for the Quakeworx and Cybertraining workshop.

The most direct way to run the notebooks in this repo is to use a conda environment. The required computing environment is defined in a environment.yml file and notebook environments will load the required libraries. For full images, this repo includes a Dockerfile that includes the required compilers and python libraries.


== Installation ==
This repo contains jupyter notebooks that can run in a conda environment.

On systems with conda and git installed, the steps for running the notebooks are:
1) git clone https://github.com/sceccode/quakeworx_workshop_2025.git
2) cd quakework_workshop_2025
3) ./build.sh
4) ./runit.sh

The build script will invoke a conda command to use the environment.yml
file to create a conda virtual environment called quakeworx-workshop-env.
This environment contains all the libraries required to run the exercises.

If changes to the environment.yml file are made, then the user can run
the update.sh script which will update the conda environment using the
contents of the environment.yml file.

