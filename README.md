Optimisez Stremio en France : addons, débrideur et configuration prête à l’emploi.

---

## 📌 1. Créez un compte Stremio

Avant tout, vous devez créer un compte Stremio :  
- [Créer un compte Stremio](https://www.stremio.com/)
- Téléchargez et installez l'application sur votre plateforme : Windows, macOS, Linux, Android, iOS.  

---

## ⚡️ 2. S'inscrire chez un débrideur

Pour profiter pleinement des contenus, un débrideur est nécessaire. J'utilise Torbox et AllDebrid, les deux ont leurs avantages, les deux offrent un essai gratuit, à vous de tester :  
- [S’abonner à Torbox](https://www.torbox.app/) (Optionel mon code de parrainage **3f98b0bb-0ac6-4108-a932-54d1853f1f4b**)
- [S’abonner à AllDebrid](https://alldebrid.fr/)

Torbox ou AllDebrid vous permettront d’accéder aux fichiers en cache.

---

## 🧩 3. Installez les addons indispensables

Voici la liste des addons à installer **dans cet ordre**, pour une expérience optimale :

### 3.1 AIOMetadata

- Permet de récupérer automatiquement les métadonnées des films et séries.  
- Configurable ici : [AIOMetadata Config](https://aiometadata.elfhosted.com/configure/)  
- Vous aurez besoin de comptes et clés API :  
  - [TMDB](https://www.themoviedb.org/)
- Pour configurer votre addon :  
  1. Connectez-vous sur AIOMetadata Config  
  2. Dans la partie **Intégration**, saisissez vos clés API TMDB et TheTVDB  
  3. Dans **Général**, choisissez la langue **French (France)**  
  4. Dans **Catalog**, vous pouvez sélectionner vos favoris  
  5. Ou importez directement ma configuration JSON :  
     - `aiometadata-config-2026-05-20.json`  
     - Cliquez sur **Importer JSON** depuis l’onglet **Configuration**
  6. Si vous importez mon fichier JSON, vous devrez saisir de nouveau vos clé API
  7. Sauvegardez la configuration afin d'obtenir l'URL d'installation de l'addon
  8. Récupérez l'URL de votre configuration et ajoutez l'addon sur la [version web de Stremio](https://web.stremio.com/#/addons)

---

### 3.2 Top Streaming (Optionnel)

- Permet d’accéder au Top 10 des contenus par plateforme (Netflix, Amazon Prime…) et par pays.  
- Configurable ici : [Top Streaming Config](https://top-streaming.stream/configure)
- Récupérez l'URL de votre configuration et ajoutez l'addon sur la [version web de Stremio](https://web.stremio.com/#/addons)

---

### 3.3 Lumio

- Permet d'obtenir les meilleurs résultats de recherche pour du contenu français

1. Rendez-vous sur [Lumio](https://mylumio.tv/configure).
2. Choisissez un nom de profil, par exemple « Salon ».
3. Configurez votre débrideur dans Lumio.
4. Choisissez le style de visionnage souhaité pour les résultats qui s'afficheront dans Stremio.
5. Cliquez sur « Activer dans Stremio » afin d'ajouter l'addon à Stremio.
6. En théorie, l'addon s'ajoute automatiquement à Stremio. Si ce n'est pas le cas, vous pouvez copier l'URL à l'aide du bouton situé en bas à droite sur le site de Lumio.
  
---

## ⚙️ 4. Organisez vos addons

Une fois tous les addons installés, vous devez les mettre dans le bon ordre :  
- [Addon Manager](https://stremio-addon-manager.vercel.app)

**Ordre recommandé :**  
1. AIOMetadata | ElfHosted  
2. Top Streaming (**Optionnel**) 
3. Lumio  
4. Cinemata  
5. Les autres addons dans l’ordre que vous voulez  

---

🎉 Voilà, vous êtes prêt à profiter de Stremio avec une configuration optimisée pour la France !
