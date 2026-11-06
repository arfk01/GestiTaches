GestiTâches

GestiTâches est une application web simple de gestion de tâches personnelles. Elle permet de créer une tâche (titre, description, date d'échéance), de la marquer comme complétée et de la supprimer. Le projet vise à aider chacun à mieux organiser son quotidien, tout en nous servant de terrain d'apprentissage pour le travail collaboratif avec Git et GitHub.

Structure du projet :

/frontend : interface utilisateur
/backend : API et stockage des tâches
Équipe
Membre	Nom d'utilisateur GitHub	Rôle
Riad Benzorai	@benzo12-dev	Responsable technique (backend, API) et propriétaire du dépôt
Khadidja Arfaoui Amira	@arfk01	Responsable frontend et documentation (backlog, README)

Les deux membres se relisent mutuellement : chaque Pull Request est revue par l'autre personne.

Stratégie de branchement

Stratégie choisie : GitHub Flow.

Pourquoi : c'est la stratégie la plus simple pour un petit projet scolaire de courte durée. Il n'y a qu'une branche principale (main) toujours stable, et chaque changement passe par une branche courte et une Pull Request revue par l'autre membre de l'équipe.

Convention de nommage des branches

Format : type/numéro-issue-nom-court (en minuscules, mots séparés par des tirets).

Préfixe	Usage	Exemple
feature/	Nouvelle fonctionnalité	feature/12-ajout-tache
fix/	Correction de bogue	fix/15-date-invalide
docs/	Documentation	docs/20-readme-equipe
test/	Branche d'essai (à supprimer)	test/riad, test/khadidja
Règles de travail
Ne jamais pousser directement sur main (la branche est protégée).
Partir de main à jour : git checkout main && git pull.
Créer une branche selon la convention ci-dessus.
Un seul petit changement par branche et par PR.
Ouvrir une PR avec le modèle, écrire Closes #numéro, assigner l'autre membre comme réviseur.
Après approbation, fusionner, supprimer la branche, puis mettre main à jour localement.
