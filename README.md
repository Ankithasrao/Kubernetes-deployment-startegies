# Kubernetes-deployment-startegies
Kubernetes deployment startegies with examples

# 1. Rolling Update Deployment Strategy

#### A Rolling Update is a deployment strategy in which Kubernetes gradually replaces old application Pods with new Pods, instead of stopping all the existing Pods at once.
#### It helps achieve zero-downtime deployments, provided the application and deployment are configured correctly.


<img width="735" height="647" alt="image" src="https://github.com/user-attachments/assets/d3f5d4b0-4480-44a5-891c-0dfc27131812" />

<img width="350" height="435" alt="image" src="https://github.com/user-attachments/assets/e9f8b11d-0158-4f54-812a-00b4597c14b8" />


#### For more information about the rolling update, checkout the below blog 

### https://medium.com/@ankithabg4/rolling-update-deployment-strategy-in-kubernetes-46f3cc5fdb9e


# 2. Canary Deployment Strategy in Kubernetes

#### Canary deployment is a deployment strategy in which we release a new version of an application to a small percentage of users first. We monitor its performance and gradually increase traffic to the new version if everything works as expected.

#### The main purpose of canary deployment is to reduce the risk of releasing a new application version to all users at once.

<img width="687" height="405" alt="image" src="https://github.com/user-attachments/assets/31012d4a-5a07-4320-9051-62c4c9a0d2fb" />


<img width="527" height="402" alt="image" src="https://github.com/user-attachments/assets/bb6871f9-66dc-4e9f-80bd-1ae2a761030a" />


# 3. Blue-green Deployment Strategy in Kubernetes

#### Blue-Green Deployment is a deployment strategy in which we maintain two identical environments: Blue (the current production version) and Green (the new version)

#### Instead of gradually replacing existing Pods, we deploy the new version in a separate environment and test it before switching production traffic to it.

#### The main goal is to deploy a new application version with minimal downtime and enable quick rollback if something goes wrong.


<img width="770" height="487" alt="image" src="https://github.com/user-attachments/assets/0bbbc367-6df3-4609-84f4-387cd38d9e12" />


<img width="571" height="261" alt="image" src="https://github.com/user-attachments/assets/f8c6dcb5-a8fb-4800-954b-548eca98c886" />


<img width="962" height="187" alt="image" src="https://github.com/user-attachments/assets/c7bbc0e0-ce6b-4ed7-84b0-c045a3995b07" />


<img width="1072" height="397" alt="image" src="https://github.com/user-attachments/assets/73296029-833a-4f32-b9b9-21ebf62dc1b2" />


#### For more information about the rolling update, checkout the below blog 

### https://medium.com/@ankithabg4/canary-deployment-strategy-in-kubernetes-d1672036eab6
