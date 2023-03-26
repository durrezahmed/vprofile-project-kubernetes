# DevOps Project - Vprofile Project Deployment on Kubernetes Cluster using AWS and kOps

This is a DevOps project for Vprofile Project Deployment on _Kubernetes Cluster_ using AWS and kOps.

[Link](https://github.com/durrezahmed/vprofile-project-devops) for vprofile app repository.

## Scenario - Current Situation:

- Multi Tier Web Application Stack

- Containerized

- Tested it

- Want to Host for Production

## Requirement:

- High Availability

- Fault Tolerance

- Easily Scalable

- Platform Independent

- Portable and Flexible

## Tools used in the Project:

- [**Kubernetes**](https://kubernetes.io/) - Container Orchestration Tool

- [**AWS Cloud Platform**](https://aws.amazon.com/) - Cloud Computing Resources

- [**kOps**](https://kubernetes.io/docs/setup/production-environment/tools/kops/) - Automated Kubernetes Cluster Provisioning System

- **Java Stack** - Vprofile Application Services

## Steps:

1. Kubernetes Cluster

2. Containerized Apps (vprofile)

3. Create EBS Volume for DB Pod

4. Label Node with Zone Names

5. Write Kubernetes Definition Files for:

   - Deployment

   - Service

   - Secret

   - Volume

## Usage:

#### Clone Repository:

```bash
git clone https://github.com/durrezahmed/vprofile-project-kubernetes.git
cd vprofile-project-kubernetes
```

#### Deploy Vprofile App on Kubernetes Cluster:

```bash
kubectl create -f .
```

#### Validate the Deployment:

```bash
kubectl get all
```

#### To Delete the Vprofile App Deployment:

```bash
kubectl delete -f .
```
