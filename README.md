# Joël TCHINDA TAPA

**Élève ingénieur en informatique, 5e année à l'ENSIM (Le Mans)**
Développement logiciel, data et IA, avec un goût pour les projets qui touchent au réel : capteurs, réalité virtuelle, applications mobiles.

| | |
|---|---|
| Recherche | Stage de fin d'études de 6 mois, à partir de mars 2027 |
| Domaines visés | Développement fullstack, data (analyse, BI, data engineering), IA, DevOps |
| Mobilité | Toute la France, de préférence Le Mans, Paris et alentours |
| Contact | [LinkedIn](https://www.linkedin.com/in/joel-tchinda-tapa/) · tapajoel16@gmail.com |

---

## En quelques mots

J'aime construire des outils complets, de la donnée brute jusqu'à l'interface que quelqu'un va réellement utiliser. Selon les projets, j'ai développé une application Android seul de la maquette Figma jusqu'au code, mis en place des pipelines de données automatisés avec GitHub Actions, entraîné des modèles de prédiction, traité des signaux physiologiques et participé à des expériences en réalité virtuelle.

Ce qui m'intéresse le plus aujourd'hui : la data et l'IA appliquées à des besoins concrets, sans perdre de vue la qualité logicielle (architecture, tests, déploiement).

---

## Parcours

| Période | Formation |
|---|---|
| 2024 - 2027 | **Diplôme d'ingénieur en informatique, ENSIM (Le Mans)**, option IPS. En 5e année : projet de fin d'études en data science, business intelligence, initiation à la recherche, design d'interaction, jeu vidéo. En 4e année : interopérabilité (REST, MOM, OAuth2, JWT), DevOps, visualisation des données, réalité virtuelle, interfaces cerveau-machine, facteurs humains |
| 2022 - 2024 | **Classes préparatoires scientifiques**, SUP'PREPA (Yaoundé, Cameroun) |
| 2020 - 2022 | **BTS Informatique industrielle et automatisme**, ISSAM (Yaoundé, Cameroun) |

Langues : français (langue maternelle), anglais B1 (B2 en cours d'obtention).

---

## Compétences

| Domaine | Outils et notions |
|---|---|
| Langages | Java, Kotlin, Python, SQL, JavaScript, TypeScript, C#, HTML/CSS |
| Data et IA | pandas, scikit-learn, PyTorch (MLP, Bi-LSTM, CNN), Jupyter, Plotly, Streamlit, Power BI, Chart.js, web scraping, LLM en local (Ollama), traitement du signal (EEG, capteurs physiologiques) |
| Développement | Spring Boot, API REST, OpenAPI / Swagger, Angular, Node.js / Express, React |
| Mobile | Android, Jetpack Compose, Material 3, architecture MVVM, Firebase (Auth, Firestore) |
| Bases de données | MySQL, PostgreSQL / Supabase, MongoDB, Firestore |
| DevOps et méthodes | Git, GitHub Actions, GitHub Pages, Docker, Docker Compose, Maven, Gradle, tests unitaires (JUnit), Agile / Scrum |
| 3D et VR | Unity (C#), Meta Quest 3, Unreal Engine 5 (Blueprint) |
| Conception | Figma, maquettes et prototypes interactifs, parcours utilisateur |

---

## Projets

Les projets sont classés par domaine. Cliquez sur un projet pour voir le détail.

### Data, BI et IA

<details>
<summary><b>FirmFactor</b> : analyse d'avis clients en ligne (projet de fin d'études, en cours) · Python, SQL, scraping, Kotlin</summary>

- Projet de fin d'études en équipe de 3, encadré par un enseignant-chercheur, sur toute l'année 2026-2027.
- Collecte d'avis clients publics par web scraping (cadre légal validé par l'encadrant), sur plusieurs secteurs : commerce, voyages, livraison.
- Stockage et traitement des données en SQL, puis analyse des avis.
- Une version mobile Android (Kotlin) de la plateforme est prévue.
- Dépôt privé : les données collectées ne peuvent pas être publiées.
</details>

<details>
<summary><b>Portfolio Business Intelligence</b> : pipelines de données automatisés et dashboards publiés en ligne · Python, GitHub Actions, Chart.js</summary>

Tous mes travaux de BI sont regroupés dans l'organisation [joel-tchinda-business-intelligence](https://github.com/joel-tchinda-business-intelligence). Chaque projet suit le même principe : un script Python collecte les données, un workflow GitHub Actions le relance automatiquement, et un dashboard est publié sur GitHub Pages.

- [**Smart Mobility Le Mans**](https://github.com/joel-tchinda-business-intelligence/smart-mobility-lemans) ([dashboard](https://joel-tchinda-business-intelligence.github.io/smart-mobility-lemans/)) : suivi des retards du réseau de bus du Mans à partir des données temps réel et des horaires théoriques (GTFS), relevés toutes les 15 minutes, historique mensuel et offre de transport par commune.
- [**EU Capitals Dashboard**](https://github.com/joel-tchinda-business-intelligence/eu-capitals-dashboard) ([dashboard](https://joeldt.github.io/eu-capitals-dashboard/)) : classement hebdomadaire des capitales européennes pour un voyage, en combinant un score météo et un score d'empreinte CO2 du trajet.
</details>

<details>
<summary><b>Smart Internship Match</b> : collecte et analyse d'offres de stage avec un LLM local (en cours) · Python, API Adzuna, Ollama, GitHub Actions</summary>

- Collecte d'offres de stage via l'API Adzuna, avec un workflow GitHub Actions et des clés stockées en secrets.
- Extraction automatique des compétences demandées dans chaque offre avec un modèle de langage local (qwen3 via Ollama).
- Évaluation critique des résultats : relecture humaine des erreurs du modèle, amélioration des requêtes (recherches ciblées, suppression des doublons) et suivi d'indicateurs de qualité du pipeline.
- Dépôt : [smart-internship-match](https://github.com/joeldt/smart-internship-match)
</details>

<details>
<summary><b>Scoring client en assurance</b> : prédiction de souscription et dashboard d'aide à la décision · Python, scikit-learn, Streamlit</summary>

- Analyse exploratoire de 381 000 clients, feature engineering et modèle Random Forest optimisé par GridSearch pour un jeu de données très déséquilibré.
- Résultats : rappel de 0,80 sur les clients intéressés, AUC de 0,84, et 51 647 clients prioritaires identifiés (environ 59 % d'appels en moins).
- Dashboard Streamlit en 5 pages, avec un simulateur de prédiction et l'export de la liste des clients à contacter.
- Dépôt : [assurance-scoring-dashboard](https://github.com/joeldt/assurance-scoring-dashboard)
</details>

<details>
<summary><b>OpenHealth</b> : pollution et santé publique en France (projet d'équipe) · Python, pandas, Power BI</summary>

- Nettoyage de données ouvertes de santé et de pollution, puis jointure avec les données géographiques (région, département, commune).
- Tableau de bord Power BI : carte spatio-temporelle des pathologies et analyse par zone.
</details>

<details>
<summary><b>Estimation de la charge cognitive des conducteurs</b> : interface cerveau-machine · Python, EEG, scikit-learn</summary>

- Projet de cours en équipe de 3, à partir du jeu de données CL-Drive.
- Prétraitement des signaux EEG (filtrage, gestion des valeurs manquantes), extraction de caractéristiques (puissance par bande de fréquence, entropie spectrale, paramètres de Hjorth, complexité).
- Comparaison de plusieurs modèles de classification, avec une évaluation en validation croisée et en « leave-one-subject-out ».
</details>

<details>
<summary><b>IA d'aide à la décision pour Othello</b> : prédire le coup d'un joueur expert · Python, PyTorch</summary>

- Prédiction du coup joué par un expert parmi les 64 cases du plateau.
- Comparaison de trois architectures de réseaux de neurones : MLP, Bi-LSTM et CNN.
- Réglage de l'optimiseur, du learning rate et de la taille des batchs.
- Résultats en validation : 14,8 % avec le MLP, 22,2 % avec le LSTM, puis 43 % avec un CNN à 3 couches, contre 1,6 % pour un choix au hasard.
</details>

<details>
<summary><b>Autres travaux data en cours</b> · Python, SQL</summary>

- **BRAIN2SPEECH** (initiation à la recherche) : état de l'art sur le décodage de la parole à partir de signaux cérébraux par IA.
- **Moteur d'indicateurs sur un forum pédagogique** : calcul d'indicateurs en SQL pour repérer les étudiants isolés ou en train de décrocher.
- **Prédiction de filière** : conception d'un questionnaire et d'un modèle pour prédire la filière d'un étudiant à partir de ses habitudes.
</details>

### Développement logiciel et mobile

<details>
<summary><b>CrewUp</b> : application Android pour organiser des sorties entre amis (projet personnel) · Kotlin, Jetpack Compose, Firebase</summary>

- Application réalisée seul, de la maquette Figma jusqu'au code : 21 écrans et 8 ViewModels.
- Création d'un événement en 3 étapes avec choix du lieu sur une carte (OpenStreetMap) et autocomplétion d'adresse.
- Hub de l'événement : vote pour la date, répartition des tâches, chat en temps réel, liste des participants.
- Système d'amis, notifications dans l'application, connexion par email ou Google.
- Architecture MVVM avec un ViewModel par fonctionnalité, Firestore en temps réel, analyse statique avec detekt.
- Dépôt : [CrewUp](https://github.com/joeldt/CrewUp)
</details>

<details>
<summary><b>Chatbot Telegram</b> : API REST et bot météo et blagues · Java, Spring Boot, OpenAPI</summary>

- API conçue à partir d'un contrat OpenAPI, avec génération des interfaces et documentation Swagger.
- Bot Telegram qui répond aux messages (météo actuelle et prévisions, blagues) en appelant des API externes.
- Authentification par token, gestion centralisée des erreurs, CRUD complet sur les blagues.
- Dépôt : [chatbot-telegram-spring-boot](https://github.com/joeldt/chatbot-telegram-spring-boot)
</details>

<details>
<summary><b>24 Heures du Code</b> : hackathon de 24 h, défi proposé par Covéa (équipe) · Node.js, Express, RabbitMQ, Supabase, React</summary>

- Application développée en équipe en 24 heures, connectée à l'API du jeu du défi.
- Back-end Node.js / Express qui communique avec un broker de messages (RabbitMQ) et stocke l'état du jeu dans Supabase.
- Ma partie : centralisation de l'état du jeu côté serveur, sauvegarde en JSON et synchronisation des données du joueur.
- Dashboard React pour suivre la partie en direct.
- Dépôt : [24HduCode_3026_covea](https://github.com/joeldt/24HduCode_3026_covea)
</details>

<details>
<summary><b>Portfolio DevOps</b> : site personnel avec intégration continue · Node.js, Docker, GitHub Actions</summary>

- Portfolio avec formulaire de contact (envoi d'emails côté serveur avec Nodemailer).
- Tests automatisés, image Docker et Docker Compose, pipeline GitHub Actions à chaque modification.
- Dépôt : [projet_DevOps](https://github.com/joeldt/projet_DevOps)
</details>

<details>
<summary><b>Gestion de conciergerie</b> : application de gestion des clients et des commandes · Python, Streamlit, MySQL</summary>

- Base de données MySQL conçue de A à Z.
- Interface Streamlit : recherche et modification des clients, création de commandes, historique, export et génération de factures.
- Dépôt : [projet_conciergerie_si](https://github.com/joeldt/projet_conciergerie_si)
</details>

<details>
<summary><b>PCFinder</b> : site de recommandation d'ordinateurs (projet d'équipe, 2025) · Angular 19, TypeScript</summary>

- Site qui aide à choisir un ordinateur selon trois parcours : guidé, simplifié et configuration technique.
- Ma partie : le parcours simplifié, avec un filtrage dynamique du catalogue de PC selon les critères transmis dans l'URL.
- Composants réutilisables et routage Angular ; prototype front-end fonctionnel.
</details>

### Capteurs, objets connectés et signal

<details>
<summary><b>FeatherMind</b> : biofeedback en temps réel inspiré de la sieste de Salvador Dalí (équipe de 3) · Python, BITalino</summary>

- Application qui mesure la relaxation à partir de capteurs physiologiques (respiration, rythme cardiaque, accéléromètre) : une plume descend à l'écran quand l'utilisateur se détend, et une alarme le réveille au seuil d'endormissement.
- Ma partie : traitement du signal et scripts d'enregistrement des données brutes.
- Dépôt : [FeatherMind](https://github.com/joeldt/-2026_4ATechFacHum_TCHINDA_BETCHEM_TALOM)
</details>

<details>
<summary><b>Réseau d'objets communicants</b> : réseau sans fil XBee et Arduino (projet d'équipe) · Arduino, XBee</summary>

- Réseau composé d'un émetteur, d'un relais, d'un hub et d'actionneurs.
- Ma partie : le nœud actionneurs (LED RGB et servomoteur) qui réagit aux messages reçus.
</details>

### Réalité virtuelle et jeu vidéo

<details>
<summary><b>ImmerScience, « Le Musée de l'Oubli »</b> : expérience VR sur la maladie d'Alzheimer (équipe) · Unity, C#, Meta Quest 3</summary>

- Visite d'un musée virtuel qui fait vivre de l'intérieur la progression de la maladie d'Alzheimer, testée sur casque Meta Quest 3.
- Participation au développement Unity en C# et à la préparation de la soutenance.
- Dépôt de l'équipe : [Immerscience](https://github.com/Lodesthard/Immerscience)
</details>

<details>
<summary><b>VR Music Explorer</b> : exploration d'une salle de musique en réalité virtuelle (équipe) · Unity, C#</summary>

- Galerie où chaque porte fait découvrir un style musical, avec des hologrammes d'albums et des animations déclenchées à l'approche.
- Ma partie : configuration du casque VR, scripts d'interaction, animations des portes et hologrammes, interface.
- Dépôt : [Projet_VR-musique](https://github.com/joeldt/Projet_VR-musique)
</details>

<details>
<summary><b>Exister sous les regards</b> : jeu vidéo narratif (projet personnel de cours, en cours) · Unreal Engine 5, Blueprint</summary>

- Jeu en plusieurs niveaux autour d'un personnage qui n'existe que lorsqu'il est regardé.
- Recherche d'une mécanique de jeu originale, au-delà du clavier et de la souris.
</details>

### Conception et expérience utilisateur

<details>
<summary><b>Projets de design d'interaction</b> · Figma</summary>

- **Gestion d'une flotte de livraison** : maquettes d'une application de suivi en temps réel de livreurs de pizzas (équipe de 3).
- **Dark patterns** : prototype interactif Figma intégrant des pièges d'interface camouflés, testé par d'autres étudiants, puis analyse critique du prototype d'une autre équipe.
- **Design graphique et sonore** : refonte des icônes, des interactions et des retours sonores de l'application CrewUp.
</details>

---

## Expériences et engagement

- **Stagiaire développeur web, CAMTEL (Cameroun Télécommunications)**, juin à août 2023 : temps de chargement du site réduit de 35 % (mesure GTmetrix) en optimisant les images et les requêtes à la base de données, mise en place de tests unitaires automatisés, participation aux rituels agiles (daily, sprint planning, review) dans une équipe de 6 développeurs.
- **Bureau exécutif de l'AECM**, association des élèves de l'ENSIM : organisation d'événements et accueil des nouveaux étudiants.
- **24 Heures du Code, Le Mans** (mars 2026) : hackathon en équipe sur le défi proposé par Covéa.
- **Emplois étudiants en parallèle des études** : préparateur de commandes en intérim, agent d'accueil et agent d'entretien lors des événements de l'Automobile Club de l'Ouest (24 Heures du Mans).

---

## Contact

- LinkedIn : [joel-tchinda-tapa](https://www.linkedin.com/in/joel-tchinda-tapa/)
- Email : tapajoel16@gmail.com
- GitHub : [joeldt](https://github.com/joeldt) · [Portfolio BI](https://github.com/joel-tchinda-business-intelligence)
