##  How does it work?  ##

  

<h3><b><u>Repository</u></b></h3>

  

<FONT SIZE=4>A Git repository is a place where source code and its change history are stored and managed using the distributed version control system Git.</font>

  
<h3>Folder structure:</h3>

-  <FONT SIZE=4><b>.github/workflows</b> - Folder that contains the pipelines.</font>

-  <FONT SIZE=4><b>force-app/main/default</b> - Folder that contains the Salesforce environment code divided into their respective folders.</font>

-  <FONT SIZE=4><b>vlocity</b> - Folder that contains the Vlocity code divided into their respective folders.</font>

![image.png](.imgs/repository.png)

<h3><b><u>Creating encrypted secrets for a repository  </u></b></h3>


<FONT SIZE=4>To create secrets or variables for a personal account repository, you must be the repository owner. To create secrets or variables for an organization repository,<b> you must have administrator access.</b></font>

![image.png](.imgs/secrets.png)


1. <FONT SIZE=4>On GitHub.com, navigate to the main page of the repository.</font>
2. <FONT SIZE=4>Under your repository name, click  Settings. If you cannot see the "Settings" tab, select the  dropdown menu, then click Settings.</font>
3. <FONT SIZE=4>In the "Security" section of the sidebar, select  Secrets and variables, then click Actions.</font>
4. <FONT SIZE=4>Click the Secrets tab.</font>
5. <FONT SIZE=4>Click New repository secret.</font>
6. <FONT SIZE=4>In the Name field, type a name for your secret.</font>
7. <FONT SIZE=4>In the Secret field, enter the value for your secret.</font>
8. <FONT SIZE=4>Click Add secret.</font>

<h3>Git Clone:</h3>

To clone a repository from GitHub, you can follow these steps:

1. Go to the repository's GitHub page and copy the URL of the repository.

2. Open a terminal or command prompt on your computer and navigate to the directory where you want to clone the repository.

3. Type the command git clone followed by the URL of the repository. For example, if the URL of the repository is https://github.com/username/repo.git, you would type:

*git clone https://github.com/username/repo.git* Press Enter to execute the command.

Git will start downloading the repository to your local machine.

Once the cloning process is complete, you can navigate to the cloned directory and start working with the code.
