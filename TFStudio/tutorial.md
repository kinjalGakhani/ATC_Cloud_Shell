# TF Studio

## Setup

Welcome to TF Studio in Google Cloud Shell! 

<!-- TF Studio objectives -->

We need you to let us know what project you'd like to use with TFStudio.

<walkthrough-project-billing-setup></walkthrough-project-billing-setup> 

## SDF Setup Steps!

Let's use {{project-id}} with TFStudio! Click the Cloud Shell icon below to copy the command
to your shell, update the {{project-id}},and then run it from the shell by pressing Enter/Return. 

```bash
export GOOGLE_CLOUD_PROJECT={{project-id}}
```

To lunch the TFStudio run the below command.

```bash
docker run \
 -p 8080:9000 \
 -e GOOGLE_CLOUD_PROJECT=$GOOGLE_CLOUD_PROJECT \
gcr.io/new-project-340206/github.com/stenalpjolly/terraformstudio:latest
```

Let's open TFStudio page. Run the following to get web preview URL and click on the output URL to open SDF.

```bash
cloudshell get-web-preview-url -p 8080
```

