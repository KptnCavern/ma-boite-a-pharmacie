# Ma boîte à pharmacie — mini-site statique

Pages : index.html, confidentialite.html, conditions.html, suppression.html, assistance.html.

## AVANT PUBLICATION — OBLIGATOIRE
1. Remplacer toutes les occurrences de `[NOM DE L’ÉDITEUR À RENSEIGNER]` et `[E-MAIL DE CONTACT À RENSEIGNER]` par des coordonnées réelles.
2. Vérifier les informations techniques et légales, notamment les SDK, les usages exacts de Google Drive et des recherches de photos, la procédure de suppression et la déclaration de sécurité des données Play Console.
3. Ajouter le lien vers cette politique **dans l'application** (actuellement la présence d'un tel lien n'a pas été vérifiée).
4. Si l'application ou le backend changent (AdMob, Cloud Run), mettre à jour les textes et les déclarations Play Console.
5. Pour la vérification OAuth, utiliser de préférence un domaine personnalisé que vous possédez et que vous pouvez vérifier dans Google Search Console (voir ci-dessous).

## GitHub Pages
- Créer un dépôt `ma-boite-a-pharmacie-site` sur GitHub.
- Déposer le contenu de ce dossier à la racine du dépôt.
- Settings > Pages > Build and deployment > Deploy from a branch > main / (root).
- URL sans domaine propre : `https://IDENTIFIANT.github.io/ma-boite-a-pharmacie-site/`.
- Pour vérifier le domaine OAuth, utiliser un domaine personnel dont vous gérez le DNS et le configurer en Custom Domain dans GitHub Pages. Vérifier ensuite ce domaine via Google Search Console.

## URL à reporter dans Google Play / OAuth
- Accueil : https://VOTRE-DOMAINE/
- Confidentialité : https://VOTRE-DOMAINE/confidentialite.html
- Suppression : https://VOTRE-DOMAINE/suppression.html
- Conditions : https://VOTRE-DOMAINE/conditions.html
- Assistance : https://VOTRE-DOMAINE/assistance.html
Si GitHub Pages utilise un sous-chemin, ajouter le préfixe correspondant après le domaine.

## À contrôler
- « Compte Organisation » et classification santé selon déclaration Google Play ; notice de non-dispositif médical sur fiche Store.
- L'URL de suppression ne doit pas prétendre supprimer les copies Google Drive automatiquement.
- Le site n'exige aucun Javascript et ne contient aucun formulaire collectant des données.
- Aucune police distante, aucun JavaScript tiers ni service de statistiques intégrés.
- Vérifier obligations légales françaises additionnelles (mentions légales d'éditeur, identification, contact, éventuelle activité commerciale et statut).
