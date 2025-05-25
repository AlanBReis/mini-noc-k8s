## Mini-NOC com Kubernetes

Este projeto configura uma stack de monitoramento com Prometheus, Grafana e Alertmanager em um cluster Kubernetes local (Minikube). A coleta de métricas é feita através do kube-state-metrics e Node Exporter, com visualizações via Grafana e envio de alertas para o Discord via Webhook.

###  Arquitetura do Sistema
O diagrama abaixo representa como o sistema é organizado
![diagrama](images/diagrama.png)

### Tecnologias utilizadas
- Kubernetes
- Prometheus
- Grafana
- Alertmanager
- kube-state-metrics
- Node Exporter
- Discord Webhook

### Objetivo
Criar uma estrutura funcional de NOC para fins de aprendizado com foco em infraestrutura baseada em Kubernetes.
