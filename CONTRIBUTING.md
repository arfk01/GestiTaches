# Guide de contribution — GestiTaches

## 1. Objectif

Ce document présente les règles de collaboration pour le développement du projet GestiTaches.

## 2. Gestion des branches

La branche `main` contient la version stable du projet.

Chaque nouvelle fonctionnalité, correction ou modification de documentation doit être développée sur une branche distincte.

Conventions de nommage :

- `feature/nom-fonctionnalite` : nouvelle fonctionnalité.
- `fix/nom-correction` : correction de bogue.
- `docs/nom-documentation` : modification documentaire.

## 3. Conventions de commits

Les messages de commit doivent être clairs et descriptifs.

Exemples :

- `feat: ajout de la création des tâches`
- `fix: correction de la suppression des tâches`
- `docs: mise à jour de la documentation`

## 4. Pull Requests

Toute modification destinée à `main` doit passer par une Pull Request.

Chaque Pull Request doit :

- Présenter les modifications effectuées.
- Être associée à une issue lorsque cela est pertinent.
- Être relue par un autre membre de l'équipe.
- Recevoir une approbation avant la fusion.
- Respecter les règles de protection de la branche principale.

## 5. Revue de code

Le reviewer doit vérifier :

- La conformité avec les exigences du projet.
- La lisibilité et la qualité du code.
- L'absence de modifications inutiles.
- Les tests réalisés, lorsque cela s'applique.

Les commentaires doivent être constructifs et précis.

## 6. Gestion des issues

Les fonctionnalités et les bogues sont suivis à l'aide des GitHub Issues.

Chaque issue doit contenir une description claire et, pour les user stories, des critères d'acceptation vérifiables.

Les labels et les milestones permettent d'organiser et de prioriser le travail.

## 7. Fusion des modifications

Après approbation, la Pull Request peut être fusionnée dans `main`.

Les contributeurs doivent ensuite synchroniser leur dépôt local avant de commencer une nouvelle tâche.