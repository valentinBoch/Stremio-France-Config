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
  - [TheTVDB](https://thetvdb.com/)  
- Pour configurer votre addon :  
  1. Connectez-vous sur AIOMetadata Config  
  2. Dans la partie **Intégration**, saisissez vos clés API TMDB et TheTVDB  
  3. Dans **Général**, choisissez la langue **French (France)**  
  4. Dans **Catalog**, vous pouvez sélectionner vos favoris  
  5. Ou importez directement ma configuration JSON :  
     - `aiometadata-config-2025-12-02.json`  
     - Cliquez sur **Importer JSON** depuis l’onglet **Configuration**
  6. Sauvegardez la configuration afin d'obtenir l'URL d'installation de l'addon
  7. Récupérez l'URL de votre configuration et ajoutez l'addon sur la [version web de Stremio](https://web.stremio.com/#/addons)

---

### 3.2 Top Streaming

- Permet d’accéder au Top 10 des contenus par plateforme (Netflix, Amazon Prime…) et par pays.  
- Configurable ici : [Top Streaming Config](https://top-streaming.stream/configure)
- Récupérez l'URL de votre configuration et ajoutez l'addon sur la [version web de Stremio](https://web.stremio.com/#/addons)

---

### 3.3 AIOStreams

- Permet de centraliser vos scrappers (services qui recherchent les fichiers via votre débrideur).
- Vous aurez besoin d'une clé API StreamFusion : https://streamfusion.stremio-epsilon.ca/api/register
- Pour importer ma configuration JSON :  
  1. Rendez-vous sur [AIOStreams](https://aiostreams.stremio.ru/stremio/configure)  (L'instance la plus stable que j'ai testée **aiostreams.stremio.ru**)
  2. Scroller vers le bas puis sélectionnez **Setup Mode → Advanced**  
  3. Cliquez sur **Use Template**  
  4. Scroller au maximum jusqu'en bas de la page. En bas à droite, utilisez le bouton pour importer le fichier JSON :  
     - `aiostreams-template.json`
  5. Ensuite vous pouvez enregistrer la configuration. (Attention si vous utilisez **AllDebrid**, il faut accepter la demande de connexion reçue par mail)
  6. Récupérez l'URL de votre configuration et ajoutez l'addon sur la [version web de Stremio](https://web.stremio.com/#/addons)
  
---

## ⚙️ 4. Organisez vos addons

Une fois tous les addons installés, vous devez les mettre dans le bon ordre :  
- [Addon Manager](https://stremio-addon-manager.vercel.app)

**Ordre recommandé :**  
1. AIOMetadata | ElfHosted  
2. Top Streaming  
3. AIOStreams  
4. Cinemata  
5. Les autres addons dans l’ordre que vous voulez  

---

🎉 Voilà, vous êtes prêt à profiter de Stremio avec une configuration optimisée pour la France !
