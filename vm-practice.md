# GCP CLI Practice – VM Creation

## 📅 Date Practiced: June 2025  
## 🎯 Objective:
Practice creating and deleting a virtual machine on Google Cloud using the gcloud CLI.

## 🧠 What I Did:
- Logged in using:
  ```bash
  gcloud auth login
  gcloud auth list


set my project 
gcloud config set project project-mishelle


created a vm
gcloud compute instances create my-vm \
  --zone=us-central1-a \
  --machine-type=e2-micro \
  --image-family=debian-11 \
  --image-project=debian-cloud

listed vms
gcloud compute instances list

Deleted vms
gcloud compute instances delete my-vm --zone=us-central1-a
