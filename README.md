# TP 4 E-service microservices et Docker:**
---
Une fois que tous nos services seront parfaitement prêts et opérationnels sur la machine locale, nous créerons un conteneur individuel pour chaque service, comme le montre le diagramme de l'architecture microservice.  
<br/> 
![First Image](/img1.png?raw=true "Application Architecture") 

la liste des conteneurs pour notre projet :

1. Config Service
2. Discovery Service
3. Product Service
4. Proxy Service

Nous utiliserons Docker pour construire une image  de chacun de nos microservices . Par la suite, nous pouvons facilement orchestrer le cluster microservice complet sur notre propre machine en utilisant Docker compose.



# Exécution du projet :


- Dans chaque service 
  mvn clean install && docker build - t {service name} .

- Dans le repertoire parent
  docker-compose up


# capture ecran :

![Second Image](/1.png?raw=true "Eureka") 
![Third Image](/2.png?raw=true "Dockers") 
![Fourth Image](/3.png?raw=true "logs") 