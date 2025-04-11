# Clounaq Evaluation

This is the accompanying repository to the paper **Evaluating Cloud-native Software Architectures with Clounaq**.
It contains the modeled software architectures of three applications used as case studies to investigate the applicability of the Clounaq approach.
The models (in the folder `models`) can be imported in the [Clounaq tool](https://www.clounaq.de).

## TeaStore

The [TeaStore](https://github.com/DescartesResearch/TeaStore) application has been modeled according to a Kubernetes-based deployment with a managed Kubernetes cluster (as also done [here](https://github.com/frankakn/cloud-native-deployment)).

## LakesideMutual

The [LakeSide Mutual](https://github.com/Microservice-API-Patterns/LakesideMutual) application has been modeled according to a Kubernetes-based deployment as described [here](https://github.com/Microservice-API-Patterns/LakesideMutual/tree/master/kubernetes).

## Petclinic Cloud

The [Petclinic](https://github.com/spring-petclinic/spring-petclinic-cloud) application has been considered in the distributed version adapted for a cloud deployment. The model included here is based on the [Docker compose version](https://github.com/spring-petclinic/spring-petclinic-cloud/blob/master/docker-compose.yml), because addional services like Zipkin and Prometheus are included and to have a contrast to the other applications. A Kubernetes-based deployment would be possible here as well.
