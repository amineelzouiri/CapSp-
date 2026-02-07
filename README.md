# Présentation du Projet : CapSpé

## 1 - Présentation globale du projet
### Naissance de l’idée
En tant que délégué de classe, Amine EL ZOUIRI a constaté le désarroi des élèves face à la complexité de Parcoursup et l'impact irréversible d'un mauvais choix de spécialités en Seconde.

### Problématique initiale
Comment rendre les données d'orientation accessibles et compréhensibles pour permettre aux élèves de faire des choix de spécialités éclairés et stratégiques ?

### Objectifs
- Simuler les chances d'admission selon le profil (type de bac, mention).
- Fournir une assistance IA 24h/24 pour expliquer les programmes officiels.
- Centraliser les informations pour lutter contre le décrochage scolaire.

## 2 - Organisation du travail
### Présentation de l’équipe
- **Amine EL ZOUIRI :** Architecture logicielle, développement Backend (Flask), traitement de données (Pandas) et intégration de l'IA.
- **Jarod & Mouheb :** Recueil des besoins utilisateurs, tests de l'interface et préparation des modules V2 (sélecteur de lycée).

### Temps passé sur le projet
Le projet représente 7 mois de développement constant, de la phase de conception à la mise en ligne.

## 3 - Présentation des étapes du projet
1. **Analyse des besoins (Mai 2025) :** Observation du terrain et définition des fonctionnalités clés.
2. **Développement du moteur (Juin-Août 2025) :** Création du simulateur basé sur le CSV Parcoursup avec Pandas.
3. **Intelligence Artificielle (Septembre 2025) :** Intégration de l'API Mistral pour créer un conseiller d'orientation interactif.
4. **Communication (Hiver 2025) :** Présentation du projet à la direction de l'établissement et à des élus (Députée Céline Calvez).

## 4 - Validation de l’opérationnalité
### État d’avancement
Le projet est en version 1.0 stable. Le simulateur de probabilités et le chatbot sont totalement fonctionnels.

### Approches de vérification
- **Tests unitaires :** Validation des fonctions de filtrage `probas()` et `mentions_probas()` pour éviter les erreurs de calcul sur les données manquantes.
- **UX Testing :** Simulation de parcours élèves pour s'assurer que les listes déroulantes se mettent à jour correctement via les routes `/change_liste`.

### Difficultés rencontrées
La gestion du fichier CSV volumineux et l'encodage (`cp1252`) ont nécessité une attention particulière pour assurer la rapidité des réponses du serveur Flask.

## 5 - Ouverture
### Améliorations futures
Une mise à jour est prévue pour inclure un sélecteur de lycée pour les collégiens et un flux d'actualités éducatives en temps réel.

### Analyse critique
Le projet a prouvé son utilité sociale. La principale compétence développée est la capacité à transformer une donnée brute (CSV) en une information utile et visuelle pour l'utilisateur.

### Démarche d'inclusion
L'outil est gratuit, utilise un langage clair et une interface responsive adaptée aux smartphones, l'outil principal des lycéens aujourd'hui.
