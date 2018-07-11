# SAP HANA Deployment

## Steps to deploy the SAP HANA

* Take clone of the repository with the command
    ```
    git clone git clone https://github.com/harshapatel-tudip/sap-hana-deployment.git
    ```
* Move into the sap-hana-deployment directory
    ```
    cd sap-hana-deployment
    ```
* Now create the deployment manager using command
    ```
    gcloud deployment-manager deployments create test-sap-hana --config=test_config.yaml
    ```
