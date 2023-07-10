<FONT SIZE=4>A pull request from the develop branch to release, or from hotfix to the main branches, triggers this pipeline to validate the changes.</font>

![image.png](Pipelines/.imgs/pipeline.jpg)

<FONT SIZE=4>The pipeline starts by cloning the repository and configuring the necessary tools, such as Python scripts and SFDX CLI. In the next step, authentication against the target organization is performed, and a record (describe log) with available metadata is generated.</font>


<FONT SIZE=4>Using this information, a package is generated with the metadata differences between the source and target branches. Then, an analysis is executed to check if the changes comply with the established naming conventions. In addition, permission sets and profiles are scanned to report if any invalid permissions have been included. It is also verified that Apex classes have the appropriate sharing declaration. This report is saved as an artifact linked to the pipeline build so that it can be reviewed at any time.</font>

<FONT SIZE=4>Finally, SFDX CLI is used to validate the package against the target environment. If Apex code is included and no test classes have been added to the pull request description, the execution is blocked. Otherwise, a validation is performed by executing the selected tests. The validation results are saved as an artifact.</font>

![image.png](/Pipelines/.imgs/artifacts.png)

