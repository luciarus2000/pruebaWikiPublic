<FONT SIZE=4>You can perform the deployment of metadata in different ways depending on whether it is a single file or a folder or set of folders.
The first thing is to check which environment you are connected to. This can be seen in the bottom blue bar in Visual Studio Code.</font>

![image.png](/Utilities/VSCode-for-Salesforce/.imgs/image10.jpg)

<FONT SIZE=4>To deploy metadata from an open file, right-click inside the file and select SFDX: Deploy this source to Org.</font>

![image.png](/Utilities/VSCode-for-Salesforce/.imgs/image11.jpg)

<FONT SIZE=4>Or by selecting the file from Visual Studio Code's file browser, right-click and select SFDX: Deploy this source to Org.</font>

![image.png](/Utilities/VSCode-for-Salesforce/.imgs/image12.jpg)

<FONT SIZE=4>In the latter case, deployment of metadata can also be performed when you have an entire folder that you want to upload to the org. Right-click on the desired folder and select SFDX: Deploy Source to Org.</font>

<FONT SIZE=4>Another option is when you have a package.xml that lists all the names and types of metadata that you want to deploy to the org. In this case, it can be done in two ways. Inside the file, right-click and select SFDX: Deploy Source in Manifest to Org. Or, from the browser, select the package.xml file, right-click, and select SFDX: Deploy Source in Manifest to Org.</font>

![image.png](/Utilities/VSCode-for-Salesforce/.imgs/image13.jpg)