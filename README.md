# VeluweProtoDT Virtual Lab on NaaVRE

Documents for initializing Veluwe Proto DT virtual labs on NaaVRE.
The virtual lab contains the following:

- [Source code in a Jupyter Notebook](./codebase/Veluwe-proto-DT-v2-GitHub.ipynb)
- [A Workflow](./workflows/Workflow_protoDT.naavrewf)


## Obtaining API keys

In order to run the notebook and workflow, you need to obtain keys for the KNMI EDR and the Dataverse APIs:

- For the KNMI EDR, got to the KNMI [API catalogue](https://developer.dataplatform.knmi.nl/apis) and click on "Request an API key" below "EDR API (ALPHA)" ([documentation](https://developer.dataplatform.knmi.nl/open-data-api#token)).
- For Dataverse, sign-up or login on <https://demo.dataverse.nl/dataverse/root/>, then click on your name, select "API Token", and select "Create Token". (More information on [account management](https://guides.dataverse.org/en/5.10.1/user/account.html) and [API tokens](https://guides.dataverse.org/en/5.10.1/api/auth.html).

To execute the notebook, add the keys to the first cell. To execute the workflow, fill-in the form before clicking "execute".
