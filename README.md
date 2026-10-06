Gestion des Tickets Support

Application web front-end pour faciliter le suivi et la gestion des tickets de support et des réclamations. Elle aide les utilisateurs et les équipes de support à organiser les problèmes, à suivre l'état de chaque ticket (En attente, En cours, Résolu) et à les filtrer rapidement.

Fonctionnalités
Création de tickets : formulaire avec titre, description, priorité (Haute / Moyenne / Basse) et catégorie
Tableau de bord : vue d'ensemble avec des statistiques (tickets ouverts, résolus, urgents)
Recherche et filtrage : recherche d'un ticket, filtrage par état ou par priorité
Gestion des états : passage d'un ticket de En attente à En cours puis Résolu
Stockage local (LocalStorage) : sans backend, les données restent enregistrées dans le navigateur et ne sont pas perdues au rechargement de la page
Technologies
React.js / JavaScript (gestion de l'état des tickets)
Tailwind CSS / CSS (interface moderne et responsive)
Lucide Icons / FontAwesome (icônes des priorités et des statuts)
LocalStorage API (persistance des données côté navigateur)
Git et GitHub
Installation
bash
git clone https://github.com/abkourdouaa-glitch/Gestion-des-Tickets-Support.git
cd Gestion-des-Tickets-Support
npm install
npm run dev
