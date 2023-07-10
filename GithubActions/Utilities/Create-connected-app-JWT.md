<FONT SIZE=4>The recommended method for connecting pipelines with Salesforce is the [flujo JWT](https://help.salesforce.com/s/articleView?language=es&id=remoteaccess_oauth_jwt_flow.htm).

To connect via this flow, it is necessary to create a connected app in the environment with the following characteristics:

- OAuth Settings: enabled
- Use digital signatures: enabled
    - Include the public key of the generated certificate. [Help](/Utilities/Create-Certificates-SSL).
- OAuth Scopes: at least `Full access (full)` and `Perform requests at any time (refresh_token, offline_access)` are required.

In the management tab:

- OAuth Policies: select `Admin approved users are pre-authorized`.
- Permission Set: add the permission set assigned to the upload user.</font>
