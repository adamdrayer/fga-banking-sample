## Preparing to Import FGA Data Model and Tuples
### Sign-up for FGA Trial (https://dashboard.fga.dev )
### ‘Add New Store’ and save Store ID
### Create Client Credentials (Settings -> Create Client)
#### Assign all permissions
#### Record ClientID and Client Secret

![Create Client](https://github.com/adamdrayer/fga-banking-sample/assets/48683398/9f79bf30-a064-48c1-a770-a8845e31abdf)
![Record Creds](https://github.com/adamdrayer/fga-banking-sample/assets/48683398/d5c918f3-31df-438e-b35d-bf6c9e05bf7d)

## Importing FGA Data Model and Tuples
### Install FGA CLI (https://github.com/openfga/cli )
### Set CLI config file (i.e, ~/.fga.yaml for Mac)
#### SAMPLE CLI CONFIG FILE
#### Note: This example ~/.fga.yaml for Okta FGA
#### api-url: https://api.us1.fga.dev
#### client-id: <clientid>
#### client-secret: <clientSecret>
#### api-audience: https://api.us1.fga.dev/
#### api-token-issuer: fga.us.auth0.com
##### store-id: <store-id>

### Run Import command
#### fga store import --file ./fga-banking.yaml

