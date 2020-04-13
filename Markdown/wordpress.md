
# README

# [Projet-Kubernetes - Devops](https://github.com/Lilou444/Project-Kubernetes)
 

## Création des namespaces 

Nous avons choisi de créer deux namespaces afin de séparer la partie backend et frontend. 
    - wordpressfront : Ce namespace alloue donc le déploiement du wordpress
    - mysqlback : Ce namespace alloue le déploiement du wordpress 


## Déploiement du Wordpress et du Mysql


Dans un premier temps, nous avons testé de déployer le mysql sans la participation de KubeDB. 

Nous avons bien pu obtenir le déploiement des deux outils. 

1. Succès du déploiement du msql et wordpress  : ![enter image description here](https://github.com/Lilou444/devopsKubernetes/blob/master/Pictures/wordpress/deployment.png) 
![enter image description here](https://github.com/Lilou444/devopsKubernetes/blob/master/Pictures/wordpress/deployement1.png)
3.  Capture du wordpress avec l'adresse ip : ![enter image description here](https://github.com/Lilou444/devopsKubernetes/blob/master/Pictures/wordpress/wordpress1.png)
4. Dashboard du Kubernetes : ![enter image description here](https://github.com/Lilou444/devopsKubernetes/blob/master/Pictures/wordpress/dashboard.png)