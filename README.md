# Cinéma - Microservices en Go avec MongoDB, Docker et Kubernetes

## Aperçu

Cinéma est un projet exemple qui démontre l'utilisation de microservices pour un cinéma fictif.
Le backend de Cinéma est alimenté par 4 microservices, tous écrits en Go, utilisant MongoDB pour gérer la base de données et Docker pour isoler et déployer l'écosystème.

* Service de Films : Fournit des informations telles que les évaluations de films, le titre, etc.
* Service des Horaires : Fournit des informations sur les horaires de projection.
* Service de Réservation : Fournit des informations sur les réservations.
* Service des Utilisateurs : Fournit des suggestions de films pour les utilisateurs en communiquant avec d'autres services.

### Architecture

![Vue d'ensemble](docs/images/overview.jpg)
