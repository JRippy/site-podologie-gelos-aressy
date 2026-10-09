# Site du cabinet de podologie de Gelos et Aressy

Site statique : `index.html` + dossier `images/`. Aucune installation nécessaire.

## Publier avec GitHub Pages
1. Créer un dépôt vide sur GitHub (ex. `podologie-gelos-aressy`).
2. Dans ce dossier :
   ```
   git init
   git add .
   git commit -m "Site vitrine"
   git branch -M main
   git remote add origin https://github.com/TON-COMPTE/podologie-gelos-aressy.git
   git push -u origin main
   ```
3. GitHub : Settings > Pages > Source : branche `main`, dossier `/ (root)`.
4. Le site apparaît sur `https://TON-COMPTE.github.io/podologie-gelos-aressy/`.

## Nom de domaine
Ajouter un fichier `CNAME` contenant le domaine (ex. `podologie-gelos.fr`), puis configurer le DNS chez le registrar.

## À compléter
- Mentions légales (identité, RPPS, hébergeur : GitHub, Inc.)
- Vérifier l'e-mail du secrétariat et les textes des soins
