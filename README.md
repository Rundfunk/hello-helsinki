# hello-helsinki

Demo application for the _DevOps with Docker_ MOOC.

Application is built and deployed via GitHub Actions.

## Building

First, a Docker image containing the application is built via GitHub Actions and uploaded to Docker Hub at: https://hub.docker.com/r/rundfunkmeister/hello-helsinki .

## Deployment

After the Docker image has been built and is pushed to Docker Hub, a GitHub Action is used to trigger Render.com. This will let Render.com pull the latest image and deploy it. After deployment, it can be found at: https://hello-helsinki-latest.onrender.com/ .

