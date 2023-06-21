# oci-developer-incubator-AIML-Datascience

[![License: UPL](https://img.shields.io/badge/license-UPL-green)](https://img.shields.io/badge/license-UPL-green) [![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=oracle-devrel_oci-developer-incubator)](https://sonarcloud.io/dashboard?id=oracle-devrel_oci-developer-incubator)

## Introduction
This repository provides AI&ML use case with 6 different deployment paths for you to choose from based on your preference and requirements. As each path comes with its own benefits, refer to the table below to guide you in making an informed decision.

| Benefits | DIY | Mix & Match | Managed |
| :--- | :---: | :---: | :---: |
| Use a GPU shape for deep-learning model training and inference or CPU-based compute for machine learning, according to your needs | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Integrates with the rest of the Oracle Cloud Infrastructure stack, including Functions, Data Flow, Autonomous Data Warehouse, and Object Storage | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Automating the Continuous Integration and Continuous Deployment (CI/CD) pipelines for workloads in Oracle Cloud | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Helps data scientists concentrate on methodology and domain expertise to deliver models to production | :x: | :white_check_mark: | :white_check_mark: |
| Pipelines enable you to execute end-to-end machine learning workflows | :x: | :white_check_mark: | :white_check_mark: |
| Enables self-service, serverless access to infrastructure for data science workloads | :x: | :white_check_mark: | :white_check_mark: |
| Simple drag-and-drop interface to build a complete Machine learning Model | :x: | :x: | :white_check_mark: |
| Pretrained models that can be custom trained with an organization’s own data to improve model quality, making it easier for developers to adopt and use AI technology | :x: | :x: | :white_check_mark: |

:white_check_mark: = Supported

:x: = Not supported

:heavy_minus_sign: = Not applicable

Continuous Integration and Continuous Delivery **(CI/CD)** accelerates app development by introducing automation into the stages of app development including build, test and deploy. Choose this option to adopt agile app development principles.

## Getting Started
Click on the deployment path of your choice for more details and deployment instructions. You may also click on the ![Deploy to Oracle Cloud](https://oci-resourcemanager-plugin.plugins.oci.oraclecloud.com/latest/deploy-to-oracle-cloud.svg) button below and follow the instructions to automate the deployment using OCI Resource Manager.

* [**1a. DIY**](1a_diy)

    Leverage Marketplace Data Science VM for Machine Learning

    [![Deploy to Oracle Cloud](https://oci-resourcemanager-plugin.plugins.oci.oraclecloud.com/latest/deploy-to-oracle-cloud.svg)](1a_diy/terraform/README.md)     

* [**1b. DIY with CI/CD**](1b_diy_cicd)

    Leverage Marketplace Data Science VM for Machine Learning with CI CD pipeline

    [![Deploy to Oracle Cloud](https://oci-resourcemanager-plugin.plugins.oci.oraclecloud.com/latest/deploy-to-oracle-cloud.svg)](1b_diy_cicd/terraform/README.md)

* [**2a. Mix and Match**](2a_mixmatch)

    Leveraging OCI Data Science for Machine Learning

    [![Deploy to Oracle Cloud](https://oci-resourcemanager-plugin.plugins.oci.oraclecloud.com/latest/deploy-to-oracle-cloud.svg)](2a_mixmatch/terraform/README.md)

* [**2b. Mix and Match with CI/CD**](2b_mixmatch_cicd)

    Leveraging OCI Data Science for Machine Learning with CI CD pipeline

    [![Deploy to Oracle Cloud](https://oci-resourcemanager-plugin.plugins.oci.oraclecloud.com/latest/deploy-to-oracle-cloud.svg)](2b_mixmatch_cicd/terraform/README.md)

* [**3a. Managed**](3a_managed)

    MLOps using Managed OML4Py with AutoML

    [![Deploy to Oracle Cloud](https://oci-resourcemanager-plugin.plugins.oci.oraclecloud.com/latest/deploy-to-oracle-cloud.svg)](3a_managed/terraform/README.md)

* [**3b. Managed with CI/CD**](3b_managed_cicd)

    MLOps using Managed OML4Py with AutoML with CI CD pipeline

    [![Deploy to Oracle Cloud](https://oci-resourcemanager-plugin.plugins.oci.oraclecloud.com/latest/deploy-to-oracle-cloud.svg)](3b_managed_cicd/terraform/README.md)


### Prerequisites
`<prerequisites of going through this lab>`

## Notes/Issues
Architectures shown are not meant for production deployment. Please refer to [Oracle Reference Architecture](https://docs.oracle.com/en/solutions/ha-web-app/index.html) for best practices.

## URLs
* [Reference Architecture](https://docs.oracle.com/en/solutions/ha-web-app/index.html)

* [MAD Framwork](https://docs.oracle.com/en/solutions/mad-web-mobile/index.html)

## Contributing
This project is open source.  Please submit your contributions by forking this repository and submitting a pull request!  Oracle appreciates any contributions that are made by the open source community.

## License
Copyright (c) 2022 Oracle and/or its affiliates.

Licensed under the Universal Permissive License (UPL), Version 1.0.

See [LICENSE](LICENSE) for more details.

ORACLE AND ITS AFFILIATES DO NOT PROVIDE ANY WARRANTY WHATSOEVER, EXPRESS OR IMPLIED, FOR ANY SOFTWARE, MATERIAL OR CONTENT OF ANY KIND CONTAINED OR PRODUCED WITHIN THIS REPOSITORY, AND IN PARTICULAR SPECIFICALLY DISCLAIM ANY AND ALL IMPLIED WARRANTIES OF TITLE, NON-INFRINGEMENT, MERCHANTABILITY, AND FITNESS FOR A PARTICULAR PURPOSE.  FURTHERMORE, ORACLE AND ITS AFFILIATES DO NOT REPRESENT THAT ANY CUSTOMARY SECURITY REVIEW HAS BEEN PERFORMED WITH RESPECT TO ANY SOFTWARE, MATERIAL OR CONTENT CONTAINED OR PRODUCED WITHIN THIS REPOSITORY. IN ADDITION, AND WITHOUT LIMITING THE FOREGOING, THIRD PARTIES MAY HAVE POSTED SOFTWARE, MATERIAL OR CONTENT TO THIS REPOSITORY WITHOUT ANY REVIEW. USE AT YOUR OWN RISK. 