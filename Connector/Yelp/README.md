# Yelp Custom Connector Test Project

## Description
Ce projet vise à tester l'utilisation d'un connecteur personnalisé pour intégrer les services de Yelp dans des applications et des flux créés sur la Power Platform. Ce connecteur permet d'exploiter les données de Yelp, comme les avis et les informations sur les entreprises, pour enrichir les solutions Power Apps et Power Automate.

## Technologies Utilisées
- **Power Apps** : Création d'applications interactives permettant d'afficher et de manipuler les données issues de Yelp.
- **Power Automate** : Automatisation des processus en utilisant les données fournies par le connecteur personnalisé Yelp.
- **Connecteur Personnalisé** : Permet de connecter la Power Platform à l'API de Yelp pour récupérer des informations spécifiques.

## Structure du Projet
Le projet est divisé en deux solutions :

1. **Solution Base Connector** :
   - Contient le connecteur personnalisé configuré pour interagir avec l'API de Yelp.
   - Inclut la documentation de configuration du connecteur.

2. **Solution App et Flow** :
   - Inclut une application Power Apps utilisant le connecteur pour afficher les données Yelp.
   - Contient des flux Power Automate pour automatiser des actions comme la recherche d'entreprises ou l'envoi d'alertes basées sur des critères spécifiques.

## Prérequis
- Un abonnement actif à la Power Platform.
- Une clé API Yelp valide (disponible sur [Yelp Developers](https://www.yelp.com/developers)).
- Droits suffisants pour créer et importer des solutions sur votre environnement Power Platform.

## Configuration
1. **Créer et Configurer le Connecteur Personnalisé** :
   - Importer la solution Base Connector dans votre environnement Power Platform.
   - Fournir la clé API Yelp dans les paramètres du connecteur.

2. **Importer les Solutions** :
   - Importer la solution App et Flow.
   - Publier toutes les personnalisations.

3. **Tester l'Intégration** :
   - Ouvrir l'application Power Apps et effectuer une recherche Yelp.
   - Exécuter les flux Power Automate pour valider les automatisations.

## Fonctionnalités
- Recherche d'entreprises sur Yelp par localisation et catégorie.
- Affichage des avis et notes des entreprises dans une application Power Apps.
- Automatisation d'alertes et de recherches via Power Automate.

## Étapes Futures
- Ajouter des fonctionnalités avancées comme des filtres personnalisés.
- Intégrer des visualisations Power BI pour analyser les données Yelp.
- Étendre les flux Power Automate avec des conditions complexes.

## Ressources
- [Documentation API Yelp](https://www.yelp.com/developers/documentation/v3)
- [Microsoft Power Platform](https://powerplatform.microsoft.com/)

## Contribution
Les contributions sont les bienvenues. Veuillez ouvrir un problème ou soumettre une pull request pour toute amélioration ou bug.

## Licence
Ce projet est sous licence MIT. Veuillez consulter le fichier LICENSE pour plus de détails.
