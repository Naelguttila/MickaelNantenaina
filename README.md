
## Fonctionnalités
Créer, lire, mettre à jour et supprimer des publications
Aimer et ne plus aimer des publications
Créer, répondre à, lire, mettre à jour et supprimer des commentaires imbriqués
Markdown pour les publications et les commentaires
S'inscrire et se connecter en utilisant JWT pour l'authentification
Envoyer des messages privés aux utilisateurs en temps réel en utilisant socket.io
Voir les profils des utilisateurs et parcourir leurs publications, leurs publications aimées et leurs commentaires
Défilement infini
Trier les publications par attributs tels que le nombre de likes, le nombre de commentaires et la date de création
Filtrage des blasphèmes et délais de publication/commentaire
Mettre à jour la biographie qui peut être vue par les autres utilisateurs
Rechercher des publications par leur titre
Voir les utilisateurs qui ont aimé une publication particulière
Mise en page entièrement réactive

## Installation 
1) Cloner le répertoire
```
git clone https://github.com/ihtasham42/social-media-app.git
```
2) Installation des paquets
```
cd social-media-app  
npm install
cd client
npm install
```
3) Creation .env i
```
cd ..
touch .env
```
4) Configurez les variables d'environnement dans votre nouveau fichier .env. Pour obtenir votre MONGO_URI, créez un cluster gratuitement sur https://www.mongodb.com/. La TOKEN_KEY est une clé secrète de votre choix, vous pouvez en générer une sur ce site : https://randomkeygen.com/.

MONGO_URI=<YOUR_MONGO_URI> 
TOKEN_KEY=<YOUR_TOKEN_KEY>
PORT=4000
```
5) Lancez le serveur server
```
npm run server
```
6) Ouvrir un nouveau terminal et lancé le coté client
```
cd social-media-app
cd client
npm start
```

