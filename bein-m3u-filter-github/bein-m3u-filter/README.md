# beIN SPORTS FR/AR — filtre M3U

Outil statique gratuit, sans dépendances, pour sélectionner les entrées **beIN SPORTS** françaises et arabes d'une playlist M3U que vous êtes autorisé à utiliser.

## Utilisation
1. Ouvrir `index.html` dans un navigateur, ou déployer avec GitHub Pages.
2. Importer un fichier `.m3u`/`.m3u8` ou coller son contenu.
3. Cliquer sur **Extraire les chaînes**, puis télécharger `beIN_SPORTS_FR_AR.m3u`.
4. Pour NexoTV : fournir une URL HTTPS de playlist accessible, si l'hébergement et les conditions d'accès le permettent. Ne jamais publier de playlist privée ou de liens comportant des identifiants.

## GitHub Pages
Dans les paramètres du dépôt : **Settings → Pages → Deploy from a branch → main / (root)**. L'adresse de la page sera `https://<utilisateur>.github.io/<depot>/`.

## Limites
- L'application ne génère ni ne répare de flux vidéo. Une playlist expirée reste inutilisable.
- Elle ne contourne pas les abonnements ni les protections DRM.
- Les indications HD, 1080p, 4K reposent sur les noms des chaînes ; elles ne vérifient pas la qualité réelle.
- Les fichiers sont traités localement dans le navigateur, sans envoi vers un serveur par cette page.
- Ne commitez jamais des fichiers M3U privés, des identifiants ou des tokens.

## Licence
Code distribué sous licence MIT ; voir `LICENSE`.
