# CDIStat Reborn
## Le meilleur logiciel de statistiques pour un CDI.

CDIStat Reborn est une application de gestion de statistiques conçue spécifiquement pour les Centres de Documentation et d'Information (CDI) des établissements scolaires. Cette application permet de suivre et d'analyser diverses données liées à la fréquentation et à l'utilisation du CDI par les élèves.

### Fonctionnalités principales :
- Enregistrement des élèves : Les élèves peuvent s'enregistrer dans le système en indiquant leur nom, prénom et classe.
- Suivi de la fréquentation : CDIStat Reborn permet de suivre la fréquentation du CDI en enregistrant les passages des élèves.
- Raisons de visite : Les élèves peuvent fournir une raison pour leur visite au CDI, ce qui permet de mieux comprendre les besoins des utilisateurs.
- Statistiques détaillées : L'application génère des statistiques détaillées sur la fréquentation, les raisons de visite, etc., pour aider le personnel du CDI à prendre des décisions informées.

### Installation et utilisation :
1. Cloner ce dépôt sur votre machine locale.
2. Assurez-vous d'avoir Node.js installé sur votre machine.
3. Exécutez `npm install` pour installer les dépendances nécessaires.
4. Assurez-vous d'avoir un fichier CSV contenant les informations des élèves (nom, prénom, classe) dans le répertoire du projet (students.csv).
5. Modifiez le fichier `config.json` pour configurer les paramètres de l'application selon vos besoins.
6. Lancez l'application en exécutant `npm start`.
7. Accédez à l'application via votre navigateur à l'adresse http://localhost:8080.

### Configuration :
Le fichier `config.json` contient les paramètres de configuration suivants :
- `port`: Le port sur lequel le serveur de l'application sera lancé.
- `adminPassword`: Le mot de passe requis pour accéder aux fonctionnalités d'administration de l'application.

### Technologies utilisées :
- Node.js
- Express.js
- EJS (Embedded JavaScript) pour les vues
- CSV Parser pour la manipulation des fichiers CSV

### Contributeurs :
- [DIDELOT Tim](https://github.com/CaraPloof)

### Licence :
Ce projet est sous licence [MIT](https://github.com/CaraPloof/CDIStatReborn/blob/main/LICENSE).
