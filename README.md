**Nginx Kubernetes Deployment**

Configurações Kubernetes para implantar um servidor Nginx usando Deployment, ReplicaSet e Service.


Arquivos:

**nginx-deployment.yaml**

Define um Deployment que gerencia 3 réplicas do contêiner Nginx.

**nginx-replicaset.yaml**

Define um ReplicaSet que garante que 3 réplicas do pod Nginx estejam sempre rodando.

**nginx-service.yaml**

Define um Service que expõe o Deployment ou ReplicaSet do Nginx na porta 80.

Como Usar
Clone este repositório:

**git clone https://github.com/nilton128/nginx-kubernetes-deployment.git**

**cd nginx-kubernetes-deployment**

-Aplique as configurações no seu cluster Kubernetes:

**kubectl apply -f nginx-deployment.yaml**
**kubectl apply -f nginx-replicaset.yaml**
**kubectl apply -f nginx-service.yaml**

-Verifique os pods e services:

**kubectl get pods**
**kubectl get services**
