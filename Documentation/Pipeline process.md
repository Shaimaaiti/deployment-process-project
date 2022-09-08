The Pipeline Process consists of Three Main Parts:
1. Orbs
2. Jobs
3. Workflows 

1st one is the orbs, in this point, the Required tools and packages will be installed 
before starting in actually pipeline implementation like node, eb, AWS CLI.

2nd thing is jobs, in this part, the building process will happen, where starting by checking if the node is not installed in the previous step to install it, then installing  Dependencies in both the front-end and in the back-end 
then checking if there are errors by running the lint command, 
then starting in building the front end project and after that building the back end project.

3rd part will start with approval by the user to start it.
After approval happened, the deployment starts in execution for the front-end first then the back-end.


