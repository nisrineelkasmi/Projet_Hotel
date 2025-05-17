# Gestion Hôtelière - Projet Java

## Présentation

Ce projet est une application de gestion hôtelière développée en Java, permettant de gérer les chambres, les clients, les réservations, les séjours, les consommations et les employés d’un hôtel. L’interface utilisateur est réalisée avec Swing et l’architecture suit une séparation claire entre modèle, vue et contrôleurs.

## Objectifs

- Modéliser les entités principales via un diagramme UML.
- Implémenter les classes en Java avec une structure orientée objet.
- Intégrer une interface graphique pour faciliter l’utilisation.
- Automatiser certaines parties (getters/setters) via Eclipse.

## Fonctionnalités

### Gestion des chambres
- Ajout, modification et suppression.
- Suivi de l’état (disponibilité, nettoyage).
- Recherche par numéro, type ou nom.

### Gestion des clients
- Création de profils clients.
- Suivi des réservations associées.

### Réservations
- Création, modification et annulation.
- Recherche de chambres disponibles.

### Séjours
- Suivi des arrivées/départs.
- Calcul automatique du prix total.

### Consommations
- Enregistrement des produits consommés en supplément.

### Employés
- Classe mère `Employe` avec deux sous-classes :
  - `Receptionniste` : gestion des réservations.
  - `AgentEntretien` : suivi des chambres nettoyées.

## Structure du projet

- **Modèle** : classes métiers (`Client`, `Chambre`, `Reservation`, etc.)
- **Contrôleurs** : gestion des actions utilisateur (`ControlAjout`, `ControlRechercheClient`, etc.)
- **Vues** : composants graphiques (`Fenetre`, boutons personnalisés...)

## Technologies utilisées

- Java
- Swing
- Eclipse (IDE)

## Auteur(s)
Projet réalisé en groupe dans le cadre de la **L2 Droit et Informatique**.
