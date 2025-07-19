# Minecraft Stats Viewer

Un mini‑projet web pour afficher et explorer facilement les statistiques d’un joueur Minecraft à partir d’un fichier JSON exporté.

## Fonctionnalités

- 📊 **Affichage des Statistiques**  
  • Liste des catégories (minage, monstres tués, objets utilisés…)  
  • Tableaux triés par fréquence  

- 🔍 **Recherche**  
  • Filtrage en temps réel des objets/événements par mot‑clé  

- ⏱️ **Playtime**  
  • Calcul du temps de jeu total à partir de la statistique `minecraft:play_time` (ticks → h/m/s)  

- 🚶 **Distances Parcourues**  
  • Extraction automatique de toutes les stats en centimètres (`_one_cm`)  
  • Conversion en mètres ou kilomètres, + colonne “Blocks” (1 m = 1 block)  
  • Bouton de tri ascendant/descendant  

- 🌗 **Thème Sombre / Clair**  
  • Basculer à volonté – persistance dans `localStorage`  

- 📌 **Navigation Sticky**  
  • Sidebar fixe pour accéder directement aux catégories  

## Installation & Usage

1. Clonez le dépôt  
   ```bash
   git clone https://github.com/votre‐utilisateur/mc-stats-viewer.git
   cd mc-stats-viewer
    ```

2. Ouvrez la page dans votre navigateur

   * Double‑clic sur `index.html`
   * Ou hébergez via un serveur local (ex. `npx http-server`)

3. Importez vos stats Minecraft

   * Exportez vos stats depuis le jeu
   * Sélectionnez le fichier `.json` via le bouton “Choisir un fichier”

4. Naviguez entre les vues

   * Onglets : Stats / Recherche / Playtime / Distances
   * Utilisez la barre de recherche et le bouton de tri

## Structure

```
├── index.html          ← Page principale (HTML, CSS & JS)
└── README.md           ← Ce fichier
```

## Tech Stack

* **Vanilla HTML/CSS/JS**
* Design responsive & mobile‑friendly
* Aucune dépendance externe

## Crédits

* Conçu et codé en "Vibe Coding" avec l’aide de **ChatGPT (modèle o4‑mini)**
* Inspirations : UI épuré, navigation fluide, ergonomie

---

*Enjoy your stats!*
