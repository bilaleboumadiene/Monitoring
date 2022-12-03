# Solution de monitoring avec Prometheus / Grafana / Loki  

Extrait d'une solution de monitoring réalisé en entreprise pour une solution de monitoring d'applications WEB, le cluster Docker représente içi le "coeur" de la solution et est mis à disposition pour un essai en local

# Prérequis

Docker 20.10.14
Docker-compose 2.13.0

# Installation
&nbsp;

1 . Clonez le répertoire sur votre machine en local avec git clone https://github.com/bilaleboumadiene/HomelabVM.git

2 . Lancez la commande 
```
docker compose up -d
```

# Utilisatio

Accessibles via interface WEB sur : 

Prometheus : 127.0.0.1:9090
Grafana : 127.0.0.1:3000 | Logins : Admin / toto
Loki : 127.0.0.1:3100

Agents : 

Node-exporter : 127.0.0.1:9100
Promtail : 127.0.0.1:9080
