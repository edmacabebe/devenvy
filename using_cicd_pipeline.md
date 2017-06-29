# The CICD Pipeline in Origin Kubernetes using Jenkins

The purpose and intention of this DEV setup
 1. Is to minimize the time spent by the Developer in Environment configurations, 
 2. To direct the focus and energies fo the Developer towards productive coding of the business requirements.
 3. To get a feel of the Production environment
 4. To attain consistency in terms of artifact generation during env stage promotion

## Assumptions:
- Origin Kubernetes is successfully installed.
- Docker service is installed and running
- MarkLogic is installed manually and separately. You opt to run it bare-metal, on the VM or as a Docker image

## Create the DEV Environment

+ Run sh ./init_devtest_stages.sh

# Congratulations, you have setup the CI/CD Pipeline!
