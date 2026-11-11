# Votre cours. Votre outil. En deux jours.

Formation de deux jours pour les enseignants de mathématiques et de sciences du secondaire. Chaque participant y crée avec Claude un outil pédagogique interactif à partir de son propre cours, puis le teste et l'améliore. Aucune compétence en programmation n'est demandée et rien n'est à installer.

Ce dépôt contient le site web que les participants suivent pendant la formation, en ligne à l'adresse **https://xavierledent.github.io/formation/**.

## La méthode

La formation repose sur un cycle en quatre temps, que l'on parcourt plusieurs fois :

1. **Préparer** : expliquer à l'IA ce que l'on veut, avec son cours.
2. **Construire** : l'IA fabrique l'outil.
3. **Tester** : on l'essaie comme le ferait un élève.
4. **Améliorer** : on corrige et on demande de nouvelles choses.

## Déroulé

| Jour | Objectif | Contenu |
|------|----------|---------|
| 1 | Un premier outil | Connexion à Claude, choix de la cible, premier tour complet du cycle. |
| 2 | Un outil prêt pour la classe | Rédaction de la fiche de contexte, extension de l'outil, test en binôme, partage. |

À la fin des deux jours, chaque participant repart avec :

- **un outil** construit sur son cours, dans un seul fichier HTML qui s'ouvre dans n'importe quel navigateur ;
- **une fiche de contexte**, pour que les outils suivants restent cohérents avec le premier ;
- **une méthode** pour recommencer seul.

## Contenu du dépôt

| Fichier | Rôle |
|---------|------|
| [index.html](index.html) | Page d'accueil de la formation : la méthode, les liens vers les carnets, les consignes de départ. |
| [carnet-jour1.html](carnet-jour1.html) | Carnet interactif du jour 1 (étapes, demandes à copier, cases à cocher, zones de notes). |
| [carnet-jour2.html](carnet-jour2.html) | Carnet interactif du jour 2. |
| favicon.svg, favicon.png | Icônes du site. |

## Utilisation

Le site est entièrement statique : chaque page est un fichier HTML autonome (polices et styles intégrés), sans dépendance ni étape de compilation.

- **En local** : ouvrir `index.html` dans un navigateur.
- **En ligne** : le site est publié avec GitHub Pages à l'adresse https://xavierledent.github.io/formation/. Chaque envoi sur la branche `main` met le site à jour en une ou deux minutes.

Les notes des participants sont enregistrées dans le stockage local de leur navigateur. Elles ne quittent pas leur appareil ; le bouton « Exporter mes notes », en bas de chaque carnet, permet de les sauvegarder ou de les transférer vers un autre appareil.

## Public

- **Public** : enseignants de mathématiques et de sciences, tout le secondaire
- **Durée** : 2 jours consécutifs, en présentiel
- **Groupe** : 15 participants
- **Prérequis** : aucun

## Auteur

Xavier Ledent, enseignant de mathématiques et de sciences.
