# Cinéma - Exemple de Microservices en Go avec Docker, Kubernetes et MongoDB

## Aperçu

Cinéma est un projet exemple qui démontre l'utilisation de microservices pour un cinéma fictif.
Le backend de Cinéma est alimenté par 4 microservices, tous écrits en Go, utilisant MongoDB pour gérer la base de données et Docker pour isoler et déployer l'écosystème.

* Service de Films : Fournit des informations telles que les évaluations de films, le titre, etc.
* Service des Horaires : Fournit des informations sur les horaires de projection.
* Service de Réservation : Fournit des informations sur les réservations.
* Service des Utilisateurs : Fournit des suggestions de films pour les utilisateurs en communiquant avec d'autres services.

Le cas d'utilisation de Cinéma est basé sur le projet écrit en Python par [Umer Mansoor](https://github.com/umermansoor/microservices).

## Sommaire

* [Déploiement](#déploiement)
* [Comment Utiliser les Services Cinéma](#comment-utiliser-les-services-cinéma)
* [Articles Connexes](#articles-connexes)
* [Révisions Importantes](#révisions-importantes)
* [La Vue d'Ensemble](#captures-d'écran)

## Déploiement

L'application peut être déployée dans deux environnements : sur une **machine locale** ou dans un **cluster Kubernetes**. Vous pouvez trouver la documentation appropriée pour chaque cas aux liens suivants :

* [Machine locale (docker-compose)](./docs/localhost.md)
* [Kubernetes (Helm)](./docs/kubernetes-helm.md)
* [Kubernetes (Timoni)](./docs/kubernetes-timoni.md)

## Comment Utiliser les Services Cinéma

* [Points d'accès](./docs/endpoints.md)

## Articles Connexes

* [Traefik 2 - Configuration avancée avec Docker Compose](https://mmorejon.io/en/blog/traefik-2-advanced-configuration-docker-compose/)

### Architecture

![Vue d'ensemble](docs/images/overview.jpg)
