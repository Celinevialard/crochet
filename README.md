# 📍 Mes Patterns de Crochet

Bienvenue dans ma collection de patterns de crochet ! Ce projet permet de documenter et de partager mes patterns de crochet de manière claire et lisible sur internet.

## 📁 Structure du Projet

### `index.html`
Page d'accueil qui liste tous les patterns disponibles. C'est le point d'entrée du site.

### `template.html` ⭐
**FICHIER DE RÉFÉRENCE** - Utilisez ce fichier comme modèle pour créer chaque nouveau pattern. Il contient la structure HTML et CSS complète et les styles optimisés.

**Comment ajouter un nouveau pattern :**
1. Copiez le fichier `template.html` et renommez-le avec le nom de votre pattern (ex: `mon_pattern.html`)
2. Modifiez le contenu dans le nouveau fichier :
   - Changez le titre dans les balises `<h1>`
   - Remplissez les informations du pattern (nom, auteur, notes)
   - Ajoutez vos lignes de pattern en copiant-collant ce bloc autant de fois que nécessaire :
   
   ```html
   <div class="pattern-line">
       <span class="line-number">Ligne X:</span>
       <span class="line-text">Description de l'étape</span>
   </div>
   ```

3. Mettez à jour le titre de la page dans la balise `<title>`
4. Ajoutez le nouveau pattern dans `index.html` en copiant-collant ce bloc dans la section `patterns-list` :

   ```html
   <a href="nom_du_fichier.html" class="pattern-card">
       <h2><span class="pattern-icon">🎨</span>Nom du pattern</h2>
       <p>Description courte du pattern</p>
   </a>
   ```

### `chatMocci.html`
Exemple de pattern complet basé sur le template.

## 🎨 Style et Design

Le projet utilise une palette de couleurs marron/orange cohérente :
- Fond principal : `#f5c58f`
- Conteneur : `white`
- Accents : `#d4a574`, `#a67c52`

Le design est responsive et fonctionne sur tous les appareils.

## 🔄 Navigation

- Chaque page de pattern a un lien "← Retour à l'accueil" pour revenir à l'index
- L'index affiche une carte pour chaque pattern

## 📝 Conseils

- Gardez les descriptions de ligne concises mais détaillées
- Utilisez des emojis pour les icônes des patterns (🐱 chat, 🧸 doudou, etc.)
- Les notes générales peuvent inclure : matériel nécessaire, niveau de difficulté, temps estimé, etc.

Bon crochet ! 🧶
