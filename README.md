<H1>🚀 JETPACK 🚀</H1> Jetpack est un projet Epitech inspiré du célèbre jeu *Jetpack Joyride*, revisité pour offrir une expérience multijoueur en réseau. Le but est de créer un client et un serveur capables d’interagir en temps réel à travers un protocole TCP entièrement conçu et documenté par les étudiants. <br> <H1>🎯 OBJECTIFS 🎯</H1> Développer un jeu jouable à deux joueurs (ou plus) via un serveur central. Le projet se divise en deux binaires principaux : - **jetpack_server** : gère le réseau, la synchronisation des joueurs et la logique du jeu. - **jetpack_client** : gère la communication et l’affichage graphique à l’aide d’une bibliothèque (SFML, SDL, etc.). <br>

Fonctionnalités clés :

🗺️ Chargement et envoi de cartes personnalisées par le serveur.

👥 Attente de deux joueurs minimum avant le lancement automatique ou manuel de la partie.

⚡ Gestion des collisions avec les pièces et les obstacles électriques.

🏁 Fin de partie déterminée par la mort d’un joueur ou l’arrivée au bout de la carte.

🔄 Synchronisation et réconciliation côté serveur pour éviter la triche.

🧠 Mode debug détaillé pour suivre tous les paquets réseau échangés.

<br>
<H1>📚 DOCUMENTATION 📚</H1> Un fichier **doc.txt** au format RFC décrit l’intégralité du protocole de communication et du format des cartes. Ce document est essentiel pour tester la compatibilité entre différents groupes et garantir la cohérence du protocole. <br> <H1>🤖 RÉSULTAT MOULINETTE 🤖</H1> Le projet est évalué sur : - La qualité du code C/C++. - Le respect des règles de compilation et de la structure Makefile. - La robustesse du protocole réseau. - La qualité et la clarté de la documentation technique. <br>

>[!IMPORTANT]
Le protocole doit être TCP-based et parfaitement documenté.
Le client ne décide jamais seul des événements critiques comme la mort ou la victoire.
Une documentation claire et complète est obligatoire pour la soutenance.

>[!CAUTION]
Le partage de code entre groupes est strictement interdit.
Seule la documentation du protocole peut être échangée.
Toute tricherie (moulitriche) peut entraîner une note de -42.
