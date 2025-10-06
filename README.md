# TodoList Pro

Une application de gestion de tâches moderne et complète développée en HTML, CSS et JavaScript vanilla. TodoList Pro offre une interface intuitive avec des fonctionnalités avancées de productivité et de collaboration.

## Table des matières

- [Aperçu](#aperçu)
- [Fonctionnalités](#fonctionnalités)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Structure du projet](#structure-du-projet)
- [Technologies utilisées](#technologies-utilisées)
- [Raccourcis clavier](#raccourcis-clavier)
- [Configuration](#configuration)
- [Contribution](#contribution)
- [Licence](#licence)

## Aperçu

TodoList Pro est une application web de gestion de tâches qui combine simplicité d'utilisation et fonctionnalités avancées. Elle permet de gérer vos tâches quotidiennes avec des options de tri, de filtrage, de catégorisation et de suivi du temps.

### Caractéristiques principales

- Interface utilisateur moderne et responsive
- Gestion complète des tâches avec horaires et priorités
- Système de catégories et de tags personnalisables
- Vues multiples (Liste, Kanban, Calendrier, Timeline)
- Timer Pomodoro intégré
- Mode focus pour la concentration
- Sauvegarde automatique locale
- Raccourcis clavier avancés
- Thèmes sombre et minimal
- Accessibilité optimisée

## Fonctionnalités

### Gestion des tâches

#### Création de tâches
- **Titre et description** : Définissez un titre clair et une description détaillée
- **Priorités** : 4 niveaux (Critique, Haute, Normale, Basse)
- **Catégories** : Organisez vos tâches par projets ou contextes
- **Dates d'échéance** : Planifiez vos deadlines
- **Horaires** : Définissez des créneaux horaires (heure de début et fin)
- **Tags** : Étiquetage libre pour une organisation flexible
- **Temps estimé** : Prévision du temps nécessaire
- **Récurrence** : Tâches quotidiennes, hebdomadaires ou mensuelles

#### Organisation avancée
- **Sous-tâches** : Décomposez vos tâches complexes
- **Dépendances** : Liez des tâches entre elles
- **Favoris** : Marquez vos tâches importantes
- **Drag & Drop** : Réorganisez facilement vos tâches

### Vues et affichage

#### Modes de visualisation
1. **Vue Liste** : Affichage traditionnel avec tri et filtres
2. **Vue Kanban** : Tableau avec colonnes (À faire, En cours, Bloquées, Terminées)
3. **Vue Calendrier** : Visualisation mensuelle des échéances
4. **Vue Timeline** : Chronologie des tâches avec horaires

#### Options de tri
- **Par défaut** : Priorité > Échéance > Date de création
- **Horaire croissant** : Tâches de la journée dans l'ordre chronologique (8h → 18h)
- **Horaire décroissant** : Tâches de la journée en ordre inverse (18h → 8h)
- **Par priorité** : Focus sur l'importance
- **Par échéance** : Focus sur les deadlines

#### Filtres rapides
- Toutes les tâches
- Aujourd'hui
- À venir (cette semaine)
- En retard
- Terminées
- Favoris
- Priorité haute

### Productivité

#### Timer Pomodoro
- Sessions de travail de 25 minutes
- Pauses courtes et longues automatiques
- Intégration avec les tâches en cours
- Notifications sonores et visuelles

#### Mode Focus
- Interface épurée pour se concentrer
- Masquage des éléments de distraction
- Raccourci clavier rapide (Z)

#### Statistiques et suivi
- Nombre de tâches complétées
- Temps passé sur les projets
- Tendances de productivité
- Graphiques de progression

### Interface et ergonomie

#### Design responsive
- **Desktop** : Interface complète avec sidebar rétractable
- **Tablet** : Adaptation pour écrans moyens
- **Mobile** : Interface optimisée avec navigation tactile

#### Accessibilité
- Navigation au clavier complète
- Support des lecteurs d'écran
- Contrastes élevés disponibles
- Préférences de mouvement réduit respectées

#### Thèmes
- **Clair** : Interface lumineuse par défaut
- **Sombre** : Confort visuel en environnement faiblement éclairé
- **Minimal** : Interface épurée pour une concentration maximale

## Installation

### Méthode 1 : Téléchargement direct

1. Téléchargez les fichiers du projet
2. Décompressez l'archive dans le dossier de votre choix
3. Ouvrez le fichier `index.html` dans votre navigateur web

### Méthode 2 : Serveur local (recommandé)

```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js (si vous avez http-server installé)
npx http-server

# Avec PHP
php -S localhost:8000
```

Puis accédez à `http://localhost:8000` dans votre navigateur.

### Configuration requise

- **Navigateur moderne** : Chrome 80+, Firefox 75+, Safari 13+, Edge 80+
- **JavaScript activé** : Obligatoire pour le fonctionnement
- **Stockage local** : Pour la sauvegarde des données

## Utilisation

### Premier démarrage

1. **Écran de chargement** : L'application se charge avec une animation d'accueil
2. **Interface principale** : Vous arrivez sur la vue Liste avec la sidebar ouverte
3. **Première tâche** : Cliquez dans le champ "Ajouter une nouvelle tâche..." pour commencer

### Workflow recommandé

#### Configuration initiale
1. **Créez vos catégories** : Utilisez le bouton "+ Nouvelle catégorie" dans la sidebar
2. **Configurez vos préférences** : Accédez aux paramètres via l'icône d'engrenage
3. **Choisissez votre thème** : Testez les différents thèmes avec le bouton lune/soleil

#### Utilisation quotidienne
1. **Planification matinale** :
   - Utilisez le filtre "Aujourd'hui" pour voir vos tâches du jour
   - Activez le tri "Horaire croissant" pour organiser votre planning
   - Ajoutez les nouvelles tâches avec leurs horaires

2. **Exécution** :
   - Activez le mode Focus (raccourci Z) pour vous concentrer
   - Utilisez le timer Pomodoro pour vos sessions de travail
   - Marquez les tâches comme terminées au fur et à mesure

3. **Suivi** :
   - Consultez vos statistiques en fin de journée
   - Reportez les tâches non terminées au lendemain
   - Analysez votre productivité via les graphiques

### Gestion avancée

#### Organisation par projets
1. Créez une catégorie par projet
2. Utilisez les tags pour les sous-thématiques
3. Créez des tâches principales avec sous-tâches
4. Définissez les dépendances entre tâches

#### Planification hebdomadaire
1. Utilisez la vue Calendrier pour visualiser la semaine
2. Répartissez vos tâches sur les différents jours
3. Utilisez la récurrence pour les tâches répétitives
4. Surveillez les tâches en retard avec le filtre approprié

## Structure du projet

```
TodoList/
├── index.html          # Fichier principal de l'application
├── style.css           # Styles CSS complets
├── script.js           # Fichier JavaScript (actuellement vide, code intégré dans index.html)
├── task-icon.png       # Icône de l'application
├── README.md           # Documentation (ce fichier)
├── CHANGELOG.md        # Historique des versions
├── ICON_FORM_IMPROVEMENTS.md  # Documentation des améliorations d'interface
└── prompt.md           # Documentation de développement
```

### Architecture du code

L'application suit une architecture modulaire avec une classe principale `TodoApp` qui gère :

- **État de l'application** : Gestion centralisée des données
- **Rendu des vues** : Système de vues multiples
- **Gestion des événements** : Interactions utilisateur
- **Persistance** : Sauvegarde automatique en localStorage
- **Modules spécialisés** : Timer, Statistiques, Accessibilité

## Technologies utilisées

### Frontend
- **HTML5** : Structure sémantique moderne
- **CSS3** : Styles avancés avec Grid et Flexbox
- **JavaScript ES6+** : Logique applicative moderne
- **Web APIs** : localStorage, Intersection Observer, matchMedia

### Bibliothèques externes
- **Font Awesome 6.4.0** : Icônes vectorielles
- **Google Fonts** : Polices Roboto et Montserrat

### Fonctionnalités web modernes
- **CSS Grid** : Mise en page responsive
- **CSS Custom Properties** : Système de thèmes
- **Intersection Observer** : Optimisations de performance
- **Service Worker** : (prévu pour les versions futures)

## Raccourcis clavier

### Navigation rapide
- **N** : Nouvelle tâche (focus sur le champ de saisie)
- **F** : Rechercher (focus sur la barre de recherche)
- **Échap** : Effacer la recherche / Sortir du mode focus

### Outils de productivité
- **T** : Activer/Désactiver le timer Pomodoro
- **Z** : Activer/Désactiver le mode Focus
- **D** : Changer de thème (Clair → Sombre → Minimal)

### Filtres rapides
- **1** : Toutes les tâches
- **2** : Aujourd'hui
- **3** : À venir
- **4** : En retard
- **5** : Terminées

### Aide
- **?** : Afficher l'aide complète des raccourcis
- **S** : Confirmer la sauvegarde (déjà automatique)

## Configuration

### Paramètres utilisateur

L'application sauvegarde automatiquement vos préférences :

- Position de la sidebar (ouverte/fermée)
- Thème sélectionné
- Vue active (Liste/Kanban/Calendrier/Timeline)
- Filtre et tri actuels
- Catégories personnalisées

### Données stockées

Toutes les données sont stockées localement dans votre navigateur :

- **Tâches** : Titre, description, priorité, catégorie, dates, horaires
- **Catégories** : Noms et couleurs personnalisées
- **Préférences** : Paramètres d'interface et d'affichage
- **Statistiques** : Historique de productivité

### Sauvegarde et restauration

#### Export manuel (recommandé)
Pour sauvegarder vos données :
1. Ouvrez les outils de développement (F12)
2. Console : `console.log(JSON.stringify(localStorage.getItem('todoapp-state')))`
3. Copiez et sauvegardez le résultat dans un fichier texte

#### Import manuel
Pour restaurer vos données :
1. Ouvrez les outils de développement (F12)
2. Console : `localStorage.setItem('todoapp-state', 'VOTRE_BACKUP')`
3. Rechargez la page

## Contribution

### Développement local

1. **Clonez ou téléchargez** le projet
2. **Serveur local** : Utilisez un serveur HTTP simple
3. **Modification** : Éditez les fichiers avec votre éditeur préféré
4. **Test** : Rechargez la page pour voir vos modifications

### Guidelines de contribution

- **Code** : Utilisez JavaScript ES6+ et CSS moderne
- **Documentation** : Commentez vos modifications importantes
- **Tests** : Vérifiez que toutes les fonctionnalités marchent
- **Accessibilité** : Respectez les standards WCAG
- **Performance** : Optimisez les animations et les requêtes

### Améliorations suggérées

- Synchronisation cloud (Google Drive, Dropbox)
- Export/Import en formats standards (JSON, CSV, ICS)
- Intégration avec calendriers externes
- Application mobile native
- Collaboration multi-utilisateurs
- API REST pour intégrations tierces

## Licence

Ce projet est sous licence MIT. Vous êtes libre de l'utiliser, le modifier et le distribuer selon les termes de cette licence.

### Crédits

- **Développeur principal** : Votre nom
- **Icônes** : Font Awesome
- **Polices** : Google Fonts (Roboto, Montserrat)
- **Inspiration** : Meilleures pratiques des applications de productivité modernes

---

**Version actuelle** : 2.1.0
**Dernière mise à jour** : Octobre 2025

Pour plus d'informations, consultez le fichier CHANGELOG.md ou ouvrez une issue sur le repository du projet.