# Kubernetes-deployment-startegies
Kubernetes deployment startegies with examples

# 1. Rolling Update Deployment Strategy

#### A Rolling Update is a deployment strategy in which Kubernetes gradually replaces old application Pods with new Pods, instead of stopping all the existing Pods at once.
#### It helps achieve zero-downtime deployments, provided the application and deployment are configured correctly.


<img width="735" height="647" alt="image" src="https://github.com/user-attachments/assets/d3f5d4b0-4480-44a5-891c-0dfc27131812" />

#### For more information about the rolling update, checkout the below blog 

### https://medium.com/@ankithabg4/rolling-update-deployment-strategy-in-kubernetes-46f3cc5fdb9e


# 2. Canary Deployment Strategy in Kubernetes

#### Canary deployment is a deployment strategy in which we release a new version of an application to a small percentage of users first. We monitor its performance and gradually increase traffic to the new version if everything works as expected.

#### The main purpose of canary deployment is to reduce the risk of releasing a new application version to all users at once.

<img width="687" height="405" alt="image" src="https://github.com/user-attachments/assets/31012d4a-5a07-4320-9051-62c4c9a0d2fb" />

#### For more information about the rolling update, checkout the below blog 

### https://medium.com/@ankithabg4/canary-deployment-strategy-in-kubernetes-d1672036eab6
