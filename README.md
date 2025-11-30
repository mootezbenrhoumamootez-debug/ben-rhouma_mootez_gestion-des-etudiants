Nom et description du projet
Nom : Gestion des Étudiants
Description : Une application web permettant de gérer une liste d'étudiants avec leurs informations personnelles (nom, prénom, email, téléphone, date de naissance, niveau d'études). L'application offre des fonctionnalités complètes de CRUD (Create, Read, Update, Delete) ainsi que des options de recherche, filtrage et tri.

Technologies utilisées
HTML5 : Structure de l'application
CSS3 : Styles et design responsive avec variables CSS, flexbox et grid
JavaScript Vanilla : Logique métier et interactions
LocalStorage : Persistance des données côté client
CSS Animations : Effets visuels pour améliorer l'expérience utilisateur

Fonctionnalités principales
Ajout de nouveaux étudiants avec validation des champs
Modification des informations existantes
Suppression d'étudiants avec animation de sortie
Recherche en temps réel par nom ou email
Filtrage par niveau d'études
Tri par nom, prénom ou niveau
Persistance des données via localStorage
Interface responsive et moderne

Lien vers la page GitHub Pages (rendu final)

Nouveautés explorées
Utilisation avancée des variables CSS : Création d'un système de design cohérent avec des couleurs définies
Animations CSS complexes : Implémentation de keyframes pour fadeIn, slideOut et highlight
Debouncing : Optimisation des performances pour la recherche en temps réel
Gestion d'état : Gestion de l'édition en cours sans framework
Design moderne : Utilisation de gradients, ombres portées et effets de verre (backdrop-filter)

Difficultés rencontrées
Gestion des animations asynchrones : Synchroniser l'animation de suppression avec la mise à jour du DOM
Persistance des données : Maintenir la cohérence entre l'interface et le localStorage
Expérience utilisateur : Créer des transitions fluides lors des opérations CRUD
Responsive design : Adapter l'interface pour différents écrans tout en conservant la fonctionnalité

Solutions apportées
Animation asynchrone : Utilisation de setTimeout pour synchroniser l'animation de suppression avec la mise à jour des données
Architecture modulaire : Séparation claire entre la logique métier (JavaScript) et la présentation (CSS/HTML)
Optimisation des performances : Implémentation de debouncing pour les recherches en temps réel
Tests itératifs : Développement progressif avec tests manuels à chaque étape

Documentation en ligne : Consultation de MDN Web Docs pour les API JavaScript et CSS modernes
