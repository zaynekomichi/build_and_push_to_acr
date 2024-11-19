# Build Docker file and Push Image to Azure Container Registery

### First steps

Set the following secrets in your github repository, these are your authentication and server details for the registry

 - ACR_SERVER 
 - ACR_USERNAME
 - ACR_PASSWORD

 you can find your ACR authentication details and server under **Settings > Access Keys** in your container registry on Azure

Docker file is assumed to be located in the root folder of the project, you can change this in the action file under the working directory

````
working-directory: location of the docker file 
````

Edit where need be!!