# Queue Basic - Terraform

## Setup

<!-- <walkthrough-author name="kinjalakhani@google.com" analyticsId="UA-125550242-1" tutorialName="SDF" repositoryUrl="https://github.com/kinjalGakhani/SDF_Cloud_Shell.git"></walkthrough-author> -->

Welcome to Smart Deployment Framework in Google Cloud Shell! The Smart Deployment Framework provides a wide variety of fully automated architectures powered by Terraform. SDF provides flexibility to leverage single click deployment, download terraform or export to repository.

<!-- We need you to let us know what project you'd like to use with Smart Deployment Framework.

<walkthrough-project-billing-setup></walkthrough-project-billing-setup>  -->


## SDF Setup Steps!

Let's do Sanity check. Run the following to list the organizations.

```bash
gcloud organizations list
```

To lunch the SDF run the below command.

```bash
gsutil cp gs://atc-artifacts/SDF/docker-compose.yaml ./; sudo docker-compose up -d
```

Let's open SDF page. Run the following to get web preview URL and click on the output URL to open SDF.

```bash
cloudshell get-web-preview-url -p 8080
```

