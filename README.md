This repo was forked from https://github.com/GoogleCloudPlatform/microservices-demo

This was a project for me to learn more about microservices container networking and istio service mesh.

Instead of Google Cloud Kubernetes, I tried deploying it on Openshift. These were the steps I followed to configure a service mesh between
the microservices in the repository

Prerequisites:
1. Have a openshift sandbox environment
2. Brief knowledge of containers and Kubernetes
   
Firstly we will be installing a few crucial operators on the openshift cluster

