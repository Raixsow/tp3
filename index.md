Nom : Anthony Flem / Clément Kulpa / Alexis Constantin

Groupe : B - B2

Année : 1ère année (2024 - 2025)

IUT Le Havre - Cours GIT

Compte-rendu TP3 Introduction GIT
	# Exercices:
Porthos: Clément Kulpa Porthos: Alexis Constantin Athos : Anthony Flem

	# 1) 
On utilise la suite de commande ci-dessous: 'git add .' 'git commit -m "Ajout des fichiers du tp2"' 'git push'

Ensuite, on synchronise les dépôts locaux et distants: 'git remote -v' (Cependant, les remotes sont déjà créés)

Puis on utilise la commande 'cp -r tp2/* tp3/' pour copier les fichiers du tp2 dans le répertoire du tp3.

	# 2)
On exécute la commande 'git pull' pour récupérer les fichiers via github.

ATTENTION: il faut bien mettre à jour tous les fichiers avant de pull.

	# 3)
(Nos fichiers sont bien synchronisés)

# 2) Développement d'un projet java en équipe
(Voir fichiers .java)

"Nous avont maintenant crée une nouvelle branche test"

3) Gérer des nouvelles fonctionnalités à l’aide des branches
# 3.2) Fusionner la branche de test dans la branche principale
Lors de l'exécution de la commande 'ls', nous pouvons remarquer que le fichier test.txt est présent sur notre branche.

	# Exercices
	# 3)
On crée d'abord la branche AthosCoin / PortosCoin avec la commande 'git checkout -b [Nom]' On crée le fichier [NOM].java On add à la branche choisie le fichier créé avec la commande 'git add [fichier.java] On commit avec la commande 'git commit -m "[message]" On retourne sur la branche "main" avec la commande 'git checkout main' On regarde le graphe des branches avec la commande 'git log --graph --oneline --all --decorate --topo-order' On fusionne les deux branches avec la commande 'git merge [Nom]'
