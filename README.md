# Demonstrations Deploying WordPress on Google Cloud Platform using Infrastructure as Code
Code used in the Cloud Academy course "Managing Infrastructure as Code on Google Cloud Platform"

## Special Notice
This repo is provided as a courtesy to advanced learners who want access to the full code.  It is neither required nor expected for the student to attempt to build and deploy these solutions as part of the course.

No step-by-step instructions are included.  You need to know how to build and deploy Docker containers on GCP, as well as how to create Cloud Build triggers.

## This repository includes code for:
* Building a custom WordPress Docker container image using Google Cloud Build
* Building a WordPress virtual machine image for Google Compute Engine using Packer with Google Cloud Build
* Creating a GKE cluster with Deployment Manager, then deploying WordPress on the cluster using Helm
* Deploying infrastructure for a WordPress server on GCP using Terraform and the Terraform Registry

*This repository and its demonstrations utilize the following Google Cloud services and APIs:*
* [Google Compute Engine](https://console.cloud.google.com/apis/library/compute.googleapis.com)
* [Google Kubernetes Engine](https://console.cloud.google.com/apis/library/container.googleapis.com)
* [Google Cloud SQL](https://console.cloud.google.com/apis/library/sql-component.googleapis.com)
* [Google Cloud Source Repositories](https://console.cloud.google.com/apis/library/sourcerepo.googleapis.com)
* [Google Artifact Registry](https://console.cloud.google.com/apis/library/artifactregistry.googleapis.com)
* [Google Cloud Build](https://console.cloud.google.com/apis/library/cloudbuild.googleapis.com) with [community build steps](https://github.com/GoogleCloudPlatform/cloud-builders-community)
* [Google Deployment Manager](https://console.cloud.google.com/apis/library/deploymentmanager.googleapis.com)
* [Google Resource Manager](https://console.cloud.google.com/apis/library/cloudresourcemanager.googleapis.com)
* [Google Secret Manager](https://console.cloud.google.com/apis/library/secretmanager.googleapis.com)
