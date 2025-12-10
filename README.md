Optimisez Stremio en France : addons, débrideur et configuration prête à l’emploi.

---

## 📌 1. Créez un compte Stremio

Avant tout, vous devez créer un compte Stremio :  
- [Créer un compte Stremio](https://www.stremio.com/)  
- Téléchargez et installez l'application sur votre plateforme : Windows, macOS, Linux, Android, iOS.  

---

## 🔑 2. S'inscrire chez un débrideur

Pour profiter pleinement des contenus, un débrideur est nécessaire. J'utilise personnellement Torbox, vous pouvez utiliser AllDebrid si vous préférez :  
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
  5. Ou importer directement ma configuration JSON :  
     - `aiometadata-config-2025-12-02.json`  
     - Cliquez sur **Importer JSON** depuis l’onglet **Configuration**  

---

### 3.2 Top Streaming

- Permet d’accéder au Top 10 des contenus par plateforme (Netflix, Amazon Prime…) et par pays.  
- Configurable ici : [Top Streaming Config](https://top-streaming.stream/configure)  

---

### 3.3 AIOStreams

- Permet de centraliser vos scrappers (services qui recherchent les fichiers via votre débrideur).
- Vous aurez besoin d'une clé API StreamFusion :
  1. Ajoutez le Bot Telegram : [t.me/Stremiofr_bot](https://t.me/Stremiofr_bot)
  2. Envoyez la commande /generate
- Pour importer ma configuration JSON :  
  1. Rendez-vous sur [AIOStreams](https://aiostreams.stremio.ru/stremio/configure)  (L'instance la plus stable que j'ai testé **aiostreams.stremio.ru**)
  2. Sélectionnez **Setup Mode → Advanced**  
  3. Cliquez sur **Start Setup**  
  4. Cliquez sur **Use Template**  
  5. En bas à droite, utilisez le bouton pour importer le fichier JSON :  
     - `aiostreams-template.json`  

---

## ⚙️ 4. Organisez vos addons

Une fois tous les addons installés, vous devez les mettre dans le bon ordre :  
- [Addon Manager](https://addon-manager.stremiofr.com/)  

**Ordre recommandé :**  
1. AIOMetadata | ElfHosted  
2. Top Streaming  
3. AIOStreams  
4. Cinemata  
5. Les autres addons dans l’ordre que vous voulez  

---

🎉 Voilà, vous êtes prêt à profiter de Stremio avec une configuration optimisée pour la France !
