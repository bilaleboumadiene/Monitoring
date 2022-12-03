# Solution de monitoring avec Prometheus / Grafana / Loki  
****************
Extrait d'un projet réalisé en entreprise ayant pour objectif le monitoring d'applications WEB, le cluster Docker représente içi le "coeur" de la solution et est mis à disposition pour un essai en local  

&nbsp;

**Prérequis**

Docker 20.10.14  

Docker-compose 2.13.0  

&nbsp;

**Installation**
&nbsp;

1 . Clonez le répertoire sur votre machine en local avec git clone https://github.com/bilaleboumadiene/Monitoring.git

2 . Lancez la commande 
```
docker compose up -d
```  

&nbsp;

**Utilisation**

Accessibles via interface WEB sur : 

Prometheus : 127.0.0.1:9090  

Grafana : 127.0.0.1:3000 | Logins : Admin / toto  

Loki : 127.0.0.1:3100  

&nbsp;  

Agents : 

Node-exporter : 127.0.0.1:9100  

Promtail : 127.0.0.1:9080
