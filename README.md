Hi Student!

I have attached the code base for React JS deployed on Kubernetes that you will use in this chapter.  If you get stuck at any moment, please feel free to refer to this code.

Just in case, please see below an explanation of each folder:

config - different config files to have the server running

config_production - Directory for environment file(s) used for master/production environment

config_staging - Directory for environment file(s) used for staging environment

dashboard - Directory of your React JS app

.gitignore - list of files that you not be pushed to GitHub. (your local files & installed packages that won't be needed in production

Dockerfile - File that Docker is using in order to compile a server image

Readme.md - a file that has a friendly explanation of this image/repository

cloudbuild-production.yaml - File that google cloud is using in order to run a deployment, create an image and deploy it to Kubernetes in the master/production environment

cloudbuild-staging.yaml - File that google cloud is using in order to run a deployment, create an image and deploy it to Kubernetes in the staging environment

Make sure that these files are deployed on your GitHub repository.

Vadim
