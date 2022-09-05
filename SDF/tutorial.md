# Queue Basic - Terraform

## Setup

<walkthrough-author name="kinjalakhani@google.com" analyticsId="UA-125550242-1" tutorialName="SDF" repositoryUrl="https://github.com/kinjalGakhani/SDF_Cloud_Shell.git"></walkthrough-author>

Welcome to Smart Deployment Framework in Google Cloud Shell!

<!-- We need you to let us know what project you'd like to use with Smart Deployment Framework.

<walkthrough-project-billing-setup></walkthrough-project-billing-setup>

Terraform provisions real GCP resources, so anything you create in this session will be billed against this project. -->

## SDF Setup Steps!

Let's do Sanity check. Run the following to list the organizations.

```bash
gcloud organizations list
```

To lunch the SDF run the below command. Go ahead!

```bash
gsutil cp gs://atc-artifacts/SDF/docker-compose.yaml ./; sudo docker-compose up -d
```