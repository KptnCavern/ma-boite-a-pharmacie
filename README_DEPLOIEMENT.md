# Site officiel Ma boîte à pharmacie — V2

Publication : https://kptncavern.github.io/ma-boite-a-pharmacie/

## Déploiement GitHub Pages

Dézipper puis importer **le contenu du dossier**, directement à la racine du dépôt `ma-boite-a-pharmacie` (branch `main`, dossier `/root`). Remplacer les fichiers homonymes, et ajouter le dossier `assets/` en conservant sa structure. Le fichier `index.html` doit être à la racine.

**Méthode recommandée pour gérer les dossiers** : cloner le dépôt localement avec GitHub Desktop, copier tous les fichiers et faire `Commit` puis `Push`. L’interface Web GitHub permet aussi d'importer des fichiers contenus dans des sous-dossiers par glisser-déposer si le navigateur conserve la structure.

## Pages

- Accueil : `/`
- Confidentialité : `/confidentialite.html`
- Suppression : `/suppression.html`
- Conditions : `/conditions.html`
- Assistance : `/assistance.html`

## Images

- Icône de l'application : `assets/icone-application.png`
- Favicon : `favicon.ico` ; icônes Android et Apple associées
- Captures compressées : `assets/captures/*.jpg`, réutilisables dans Google Play

## À faire avant validation Play/OAuth

- Remplacer `[NOM DE L’ÉDITEUR À RENSEIGNER]` et `[E-MAIL DE CONTACT À RENSEIGNER]` sur les pages réglementaires par des informations réelles.
- Relire l'exactitude des déclarations confidentialité/suppression à la date de publication.
- Prévoir une capture supplémentaire de la synchronisation familiale sans montrer d'adresses e-mail réelles.
- Si un domaine personnalisé est configuré, ajuster la balise og:image en URL absolue.

## Note sur les captures

Captures fournies par l'éditeur : ne pas les interpréter comme des recommandations thérapeutiques. Elles montrent des dates de péremption historiques et une photo de boîte provenant d'un fournisseur tiers. Pour la fiche Play Store publique, il est préférable de préparer des captures avec produits de démonstration, sans mention personnelle et avec droit de réutilisation de toutes les photos.


### Mise à jour V2.1
- Galerie en défilement horizontal (captures intégrales, non rognées).
- Nouvelle capture `assets/captures/stock.jpg`.
- Contact : kptn.dev.contact@gmail.com ; éditeur affiché : Kptn Corp.
- Conditions §3 : avertissement sur l'usage de médicaments périmés.

**Attention :** « Kptn Corp » est un nom public fourni par l'auteur, non une identité juridique vérifiée. Avant la publication définitive, renseigner les mentions légales réelles éventuellement requises pour l'éditeur.


## V2.2 (AdMob / UMP)

- `confidentialite.html` : section publicite / consentement UMP, SDK AdMob, types de donnees techniques, absence de ciblage par l'inventaire.
- `conditions.html` : rappel publicite gratuite versus VIP.
- Les autres pages et les captures sont conservees de la V2.1.
- Deposer le contenu du ZIP a la racine du depot GitHub Pages.
- Mettre a jour Google Play « Contient des annonces » et la declaration « Securite des donnees » AVANT de distribuer une version integrant AdMob.
- Cette politique suppose que le code n'envoie aucune information de stock a AdMob et que les annonces sont affichees selon le resultat UMP : confirmer ces points pendant les tests.


## V2.3 (13 octobre 2026)
- Adresse générale et données personnelles : contact@kptncorp.fr.
- Assistance utilisateurs : support@kptncorp.fr.
- Vérifier les deux redirections OVH avec un envoi d’essai et une réponse.
- Les adresses sont des redirections ; un envoi depuis ces adresses nécessite une configuration SMTP/alias distincte.
- Publier les fichiers HTML et assets du ZIP à la racine du dépôt GitHub Pages.
