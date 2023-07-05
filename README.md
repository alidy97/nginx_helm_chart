# nginx_helm_chart

This repository contains a Helm chart for deploying the NGINX demo application in a Kubernetes cluster.

## Prerequisites

Before deploying the NGINX application, ensure the following prerequisites are met:

- Kubernetes cluster is up and running .
- Helm is installed on your local machine.

## Installation

To deploy the NGINX application, follow these steps:

1. Clone the repository:

git clone https://github.com/alidy97/nginx_helm_chart.git
cd nginx-helm-chart

2. Install the Helm chart:

helm install nginx_demo./nginx_chart

## Upgrading and Uninstalling

To upgrade the NGINX deployment to a new version of the Helm chart, use the following command:

helm upgrade nginx-demo./nginx-chart

To uninstall the NGINX application, run the following command:

helm uninstall nginx-demo

