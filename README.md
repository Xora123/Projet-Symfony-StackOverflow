# Projet-Symfony-StackOverflow

Contexte du projet
Vous êtes développeur PHP au sein de l'agence web SymfoLab.

​

Votre client un jeune entrepreneur sorti d'école de développement souhaite créer un réseaux social pour professionnel du développement qui permet de poser des questions et des réponses à d'autres développeurs pour trouver de l'aide en ligne.

​

Il vous a communiqué les éléments suivant :

​

La page principale devra afficher tous les messages précédents par ordre décroissant d'envoi
La page principale contient un formulaire permettant d'ajouter une question
Au click sur une question, une page s'ouvre affichant le contenu du post ainsi que ses commentaires
Sur la page d'un post, un formulaire permet d'ajouter un commentaire sur un post
sur la page d'un post, on peut voter pour une réponse, une seule fois par question
L'application contient une page de connexion / inscription
​

Les rôles suivant sont prévus dans l'application :

Utilisateur déconnecté : il peut consulter la liste des derniers posts et afficher un post ainsi que ses commentaires. Il ne peut pas publier de post ou de commentaire
Utilisateur connecté : il peut effectuer les actions de l'utilisateur connecté et peut en plus créer des posts et des commentaires et modifier son compte (avatar, nom, prénom, poste et mot de passe). Il peut aussi supprimer ses posts précédant, il peut aussi voter pour une réponse
Administrateur: en plus de toutes les actions précédentes, l'administrateur peut modérer une question ou une réponse (elle reste en base de donnée mais n'est plus affichée), clore un thread (il n'est plus possible d'ajouter de réponse à un therad clôt) et supprimer un post ou une réponse et un utilisateur
​

Bonus :

Votre client aimerai qu'il soit possible de se connecter à l'aide de son compte github
Le vote sur une réponse est géré à partir d'une requête ajax pour éviter le rechargement de la page
