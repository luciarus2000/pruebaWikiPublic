# Creation

<FONT SIZE=4>To create a scratch org, follow the [following instructions](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_scratch_orgs_create.htm).

# Sync between development environment and local repository

<FONT SIZE=4>The download of metadata from the development environment to the local repository can be done in the following ways:

1. [Performing a pull](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_pull_md_from_scratch_org.htm), which will download all the changes that have been made in the environment since the last sync.
    - [Using the command bar](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference_force_source.htm#cli_reference_force_source_pull)
1. Performing a retrieve, which will only download selected changes.
    - [Using the command bar](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference_force_source.htm#cli_reference_force_source_retrieve)

The upload of metadata from the local repository to the development environment can be done in the following ways:

1. [Performing a push](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_push_md_to_scratch_org.htm), which will upload all the local changes to the development environment.
    - [Using the command bar](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference_force_source.htm#cli_reference_force_source_push)
1. Performing a deploy, which will only upload selected changes.
    - [Using the command bar](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference_force_source.htm#cli_reference_force_source_deploy)
</font>
