Documentation d'Installation et de Déploiement
Ce guide vous explique comment installer et déployer ce site web localement ou sur un serveur.
Prérequis
Avant de commencer, assurez-vous d'avoir installé :
•	Node.js (version X.X ou supérieure)
•	npm ou Yarn (inclus avec Node.js)
•	Git (pour cloner le dépôt)
•	Un serveur web (Apache, Nginx, etc.) si déploiement en production
Installation
1.	Cloner le dépôt
git clone https://github.com/votre-utilisateur/votre-repo.git
cd votre-repo
Déploiement
Option 1 : Déploiement sur un serveur web
1.	Transférez les fichiers construits (dist/) sur votre serveur via FTP/SFTP ou SCP.
2.	Configurez votre serveur web (Apache/Nginx) pour pointer vers le dossier contenant les fichiers.
Option 2 : Déploiement sur un service d'hébergement
Ce projet peut être déployé sur :
•	Vercel
•	Netlify
•	GitHub Pages
Consultez la documentation de chaque service pour les instructions spécifiques.
Variables d'environnement
Les variables suivantes doivent être configurées (dans .env ou dans l'interface de votre plateforme d'hébergement) :
•	API_URL : L'URL de base de votre API
•	BASE_URL : L'URL de base de votre application
•	NODE_ENV : development ou production
Dépannage
•	Problèmes d'installation : Supprimez node_modules et package-lock.json puis réinstallez
•	Erreurs de construction : Vérifiez les logs et assurez-vous que toutes les variables d'environnement sont définies
Support
Pour toute question ou problème, veuillez ouvrir une issue sur GitHub.

