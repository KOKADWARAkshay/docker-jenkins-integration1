
## Prerequisites: 
Jenkins should be installed and configured on your machine or server.

The sample application code should be hosted on a Git repository.


## Step 1

Set up Jenkins Open Jenkins and log in with your credentials. Click on "New Item" from the left-hand menu to create a new job. Enter a name for your job and select "Freestyle project". Click "OK" to create the job.
## Step 2

Configure source code management Under the "Source Code Management" section, select Git as your repository type. Enter the URL of your Git repository and your credentials (if required). Choose the branch that you want to build from.
## Step 3

Configure the build step Under the "Build" section, click on "Add build step" and select "Execute shell". In the shell script section, enter the commands to build your code. Save the build step.


## Step 4

Configure the Docker build step Install the Docker plugin in Jenkins from the "Manage Plugins" section. Under the "Build" section, click on "Add build step" and select "Docker Build and Publish". Enter the Docker registry credentials (if required). Enter the Dockerfile path and the Docker image name. Save the Docker build step.
## Step 5

Save and run the job Click on "Save" to save the job configuration. Click on "Build Now" to run the job and test the pipeline. Check the build console output for any errors or issues.
## Step 6: 

Set up the pipeline Click on "Configure" for the job. Under the "Build Triggers" section, select "Build after other projects are built". Enter the name of the previous job in the "Projects to watch" section. Click on "Save" to save the pipeline configuration.

## 🔗 Links

![buildtrend](https://user-images.githubusercontent.com/70112790/228629448-67b56c3c-d591-4b72-bdb9-df85e42273e8.jpg)

![console output](https://user-images.githubusercontent.com/70112790/228629457-ec0da050-e2d5-489f-9ce2-edf42bee74c8.jpg)

![dockerimage](https://user-images.githubusercontent.com/70112790/228629464-f9806fb9-a2dd-47d8-84db-d2913bbf0146.jpg)

![workspaces](https://user-images.githubusercontent.com/70112790/228629468-eb23d909-ab40-4f61-b8f9-7b869e7789fa.jpg)

![1](https://user-images.githubusercontent.com/70112790/228629471-38b52abb-3035-43d3-a9b5-a009014cd999.jpg)




