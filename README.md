# **TP 4 E-service microservices et Docker:**
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



# ** Exécution du projet :**

- Docker compose up