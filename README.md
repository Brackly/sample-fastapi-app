# sample-fastapi-app

A simple Continuous integration pipeline using GitHub actions that checks out the code committed to a github repo,
does a simple test using Pytest, builds a docker image and uses role based access control (rbac) to dump the image to a private container registry (Amazon Web Services (AWS) ECR).

#next step is to configure a continuous delivery tool Argo CD, to deploy the image onto a Kubernetes cluster (AWS EKS), embracing the concept of infrastructure as code.
