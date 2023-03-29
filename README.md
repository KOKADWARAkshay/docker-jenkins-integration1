
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
[![Ci/Cd with GithubAction](https://github.com/KOKADWARAkshay/workflow-github)]


[![Ci/Cd with AWS EC2 Virtual Instance using Jenking Node Js Project](https://github.com/KOKADWARAkshay/todo-akshay-app)]





