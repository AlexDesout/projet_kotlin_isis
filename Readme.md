# 🐸 MemeScraper 9000 🐸

Bienvenue sur MemeScraper 9000, l'application Android qui te livre les mèmes les plus frais directement depuis les profondeurs de Reddit. Fini de scroller sans fin, ici on va droit au but : le DANK !

## ✨ Le Concept

L'idée est simple : utiliser une API de scraping de mèmes (par exemple, la [Meme API](https://github.com/D3vd/Meme_Api)) pour afficher une collection de pépites visuelles, les sauvegarder et les admirer encore et encore.

Ce projet est développé nativement pour Android avec Kotlin et Jetpack Compose, parce qu'on aime les technos modernes.

## 🚀 Fonctionnalités Prévues

L'application s'articulera autour de quatre écrans principaux pour une expérience utilisateur simple et efficace.

### 1. 🏠 Page d'Accueil (`HomeScreen`)
*   **Le point de départ.** Un écran d'accueil chaleureux avec le logo de l'app et un gros bouton bien visible : "Découvrir les Mèmes".

### 2. 📜 Page de Liste des Mèmes (`MemeListScreen`)
*   **Le cœur du réacteur.** C'est ici que la magie opère.
*   Affiche une grille ou une liste de mèmes fraîchement récupérés depuis l'API.
*   Chaque mème est affiché sous forme de miniature avec son titre.
*   On pourra cliquer sur chaque mème pour en voir plus.

### 3. 👀 Page de Détail (`MemeDetailScreen`)
*   **Zoom sur la pépite.** Quand un mème de la liste est sélectionné, on atterrit ici.
*   Affiche le mème en grand format pour ne rater aucun détail.
*   Affiche des informations supplémentaires : titre, subreddit d'origine, score (upvotes), etc.
*   Un bouton "Ajouter aux favoris" (une petite étoile ⭐ ou un cœur ❤️) pour sauvegarder les meilleures trouvailles.

### 4. ⭐ Page des Favoris (`FavoritesScreen`)
*   **Ton jardin secret.** L'écran où sont regroupés tous les mèmes que tu as ajoutés à tes favoris.
*   Permet de revoir tes classiques à tout moment, même si l'API est en panne (persistance locale).
*   On pourra bien sûr retirer un mème des favoris si on s'en lasse.

