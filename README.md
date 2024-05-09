## Preparing to Import FGA Data Model and Tuples
Sign-up for FGA Trial (https://dashboard.fga.dev )  <br>
‘Add New Store’ and save Store ID  <br>
Create Client Credentials (Settings -> Create Client)  <br>
-Assign all permissions <br>
-Record ClientID and Client Secret <br>

![Create Client](https://github.com/adamdrayer/fga-banking-sample/assets/48683398/9f79bf30-a064-48c1-a770-a8845e31abdf)
![Record Creds](https://github.com/adamdrayer/fga-banking-sample/assets/48683398/d5c918f3-31df-438e-b35d-bf6c9e05bf7d)

## Importing FGA Data Model and Tuples  <br>
Install FGA CLI (https://github.com/openfga/cli )  <br>
Set CLI config file (i.e, ~/.fga.yaml for Mac)  <br>

#### SAMPLE CLI CONFIG FILE  <br>
> Note: This example ~/.fga.yaml for Okta FGA <br>
> api-url: https://api.us1.fga.dev <br>
> client-id: --clientid-- <br>
> client-secret: --clientSecret-- <br>
> api-audience: https://api.us1.fga.dev/ <br>
> api-token-issuer: fga.us.auth0.com <br>
> store-id: --store-id-- <br>

### Run Import command
> fga store import --file ./fga-banking.yaml <br>

