# Changelog

Les nouveautés et améliorations de Music Desktop.

## 2.0.5 — Paroles, thèmes et Last.fm — 11 octobre 2026

### Les paroles sur Remote

- Retrouvez les paroles du morceau depuis le bouton **Paroles**, au centre de la barre supérieure de Remote. Le bouton reste grisé lorsqu’elles ne sont pas disponibles.
- Les paroles de YouTube Music sont complétées par LRCLIB. Lorsqu’une synchronisation existe, la ligne en cours est surlignée et défile avec la lecture.
- Touchez une ligne pour avancer dans le morceau, reprenez le suivi après un défilement manuel et ajustez un éventuel décalage par pas de 50 ms.
- La source reste visible : synchronisation d’origine en gris, estimation **Synchronisé par MusicDesktop** en rouge.

### Paroles automatiques — EXPÉRIMENTALE

- Un moteur facultatif analyse localement une écoute complète lorsque les paroles existent sans temps de synchronisation. Les temps déjà fournis par YouTube Music ou LRCLIB restent prioritaires.
- Le moteur se télécharge séparément : suivi par fichier avec octets, pourcentage et vitesse, annulation, reprise et suppression depuis les paramètres.
- Consultez les morceaux analysés dans une fenêtre dédiée, essayez un résultat ou effacez-le. Les résultats conservés servent aux écoutes suivantes.
- L’état affiche la recherche des paroles, l’audio reçu et les étapes du calcul. Correction du plantage lors de l’arrêt de l’analyse et de l’isolation du chant.
- **Cette fonction reste expérimentale**, désactivée par défaut. Elle nécessite Windows 11 pour la capture audio, plusieurs Go de modèles et des ressources CPU/mémoire. La précision varie selon les morceaux ; aucune précision à la milliseconde n’est garantie. Aucun audio n’est envoyé à un service de reconnaissance.

### Votre file et vos playlists

- Réorganisez les prochains morceaux dans Remote par glisser-déposer ou avec les commandes de déplacement.
- Retrouvez les playlists du compte YouTube Music connecté sur le PC : création privée par défaut, renommage, suppression et retrait d’un morceau.
- Ajoutez le titre en cours à une playlist depuis le lecteur. Les confirmations et le rafraîchissement après création ou ajout ont été corrigés.

**Les fonctions mobiles ci-dessus nécessitent MusicDesktop Remote 1.0.5 ou une version compatible.** Remote reste distribué dans le programme de test fermé Android ; l’installateur PC n’inclut pas l’application mobile. [Rejoindre les tests](https://musicdesktop.net/fr/remote.html).

### Last.fm

- Connectez votre compte dans **Paramètres → Last.fm**, autorisez MusicDesktop dans le navigateur puis activez l’enregistrement de vos écoutes.
- Le titre en cours est annoncé sur votre profil. Les morceaux de plus de 30 secondes sont enregistrés après la moitié de leur durée réellement écoutée, ou quatre minutes pour les titres longs.
- Les envois partent du PC, même téléphone fermé. Les écoutes en attente sont conservées sous protection Windows et reprises lorsque Last.fm redevient accessible.
- Vous pouvez arrêter l’enregistrement ou déconnecter votre compte à tout moment. Aucun audio n’est envoyé à Last.fm.

### Thèmes et paramètres

- Trois thèmes : **MusicDesktop**, **Akyraïs** (blanc pur et lavande) et **Asashiin** (noir profond et violet électrique).
- Icônes alignées à gauche des rubriques, textes revus et pages Streamer/Paroles automatiques retravaillées.
- Mention **EXPÉRIMENTALE** bien visible en haut de la page Paroles automatiques.

### Mises à jour et Streamer

- Nouveau suivi du téléchargement dans l’application : fichier, taille, octets reçus, pourcentage et vitesse.
- Une mise à jour téléchargée reste prête jusqu’au redémarrage que vous choisissez. Sa signature est vérifiée avant l’installation.
- La notification de mise à jour apparaît après le chargement de l’application.
- Switch **ON/OFF** Streamer dans la barre supérieure. Streamer revient sur OFF à chaque lancement, en conservant vos réglages et liens OBS.
- Les overlays et extensions Deckboard/Stream Deck des versions précédentes restent compatibles.

Téléchargez **Music.Desktop_2.0.5_x64-setup.exe** pour Windows 10/11, 64 bits. Les modèles de paroles sont facultatifs et téléchargés séparément. Vos préférences, associations Remote et modèles installés sont conservés lors d’une mise à jour normale.

## 2.0.4 — Correction MusicDesktop Remote — 8 octobre 2026

- Rétablissement du morceau en cours, de la pochette, de la progression et de l'état de lecture dans Remote après la 2.0.3.
- Format de communication compatible avec l'application mobile et le relais existants.
- Conservation des appairages déjà enregistrés ; mise à jour à installer sur le PC.

## 2.0.3 — Streamer Update — 7 octobre 2026

- Mode Streamer et overlays OBS/Streamlabs, avec six présentations et six styles personnalisables.
- Nouveau Studio : aperçu en direct, réglages regroupés, commandes et guide, en français et anglais.
- Fonds dégradés, cadres, forme de pochette, typographie et progression personnalisables.
- Brouillons indépendants avant enregistrement dans OBS, avec reprise des configurations existantes.
- Extensions MusicDesktop pour Deckboard et Elgato Stream Deck, avec états des boutons en direct.
- Nouveaux raccourcis de lecture, volume, mini-lecteur et mode Streamer.
- Service local optionnel, accès d'affichage OBS séparé de la connexion de contrôle.

## 2.0.2 — Un mini-lecteur plus pratique et optimisé — 4 octobre 2026

- Quatre présentations du mini-lecteur : Classic, Carré, Compact et Mini.
- Aperçu sans morceau en cours, emplacements prédéfinis et mémorisation de la position.
- Fond animé et progression optimisés, avec des mises à jour suspendues lorsque le contenu est caché ou rétracté.
- Mode économie de mémoire activé à la minimisation de la fenêtre principale, en conservant la lecture.
- Suivi de lecture optimisé, avec des changements de morceau et des commandes réactifs.

## 2.0.1 — MusicDesktop Remote, plus complet — 3 octobre 2026

- L’onglet « Pour vous » de Remote affiche des recommandations issues de la session YouTube Music ouverte sur le PC.
- Depuis le téléphone, activez ou désactivez la répétition du titre et la lecture aléatoire sur le PC.
- L’installateur demande votre accord pour fermer MusicDesktop s’il est déjà ouvert pendant la mise à jour.

## 2.0.0 — MusicDesktop repensé — 30 septembre 2026

- Une nouvelle interface propre à MusicDesktop accueille YouTube Music dans une vue séparée. Les paramètres et les commandes restent accessibles pendant son chargement.
- L’écran de démarrage indique l’état de la connexion et permet de réessayer si YouTube Music est momentanément indisponible.
- Associez MusicDesktop Remote à votre PC avec un QR code ou un code temporaire, puis autorisez le téléphone depuis MusicDesktop.
- Depuis le téléphone associé, contrôlez la lecture, recherchez des titres et consultez la file d’attente de la session YouTube Music ouverte sur le PC.
- YouTube Music reste la seule plateforme musicale disponible dans cette version ; SoundCloud et Bandcamp sont prévus pour plus tard.

## 1.2.9 — Plus pratique au quotidien — 25 septembre 2026

- Music Desktop peut démarrer avec Windows, en ouvrant sa fenêtre ou en restant en arrière-plan.
- Vous choisissez si l’application se ferme ou reste active quand vous fermez sa fenêtre.
- Les raccourcis fonctionnent même quand vous utilisez une autre application.
- Le mini-lecteur se souvient de sa place et de l’option « Toujours au-dessus ».
- Si Music Desktop est déjà ouvert, le relancer affiche sa fenêtre au lieu d’en ouvrir une deuxième.
- Music Desktop apparaît maintenant dans le menu Démarrer.
- La barre de défilement de YouTube Music n’est plus visible.

## 1.2.8 — Les paramètres restent à leur place — 22 septembre 2026

- Correction d’un problème qui maintenait la fenêtre des paramètres au premier plan sans raison.
- Vous pouvez maintenant choisir les raccourcis de l’application.

## 1.2.7 — Vos réglages, plus simplement — 22 septembre 2026

Cette mise à jour rend les petites choses du quotidien plus naturelles : vos réglages, votre mini-lecteur et vos mises à jour sont exactement là où vous les attendez.

- Les paramètres ont été repensés avec une interface plus claire et mieux organisée, pour retrouver chaque option plus facilement.
- Le mini-lecteur est toujours à portée de clic depuis la barre du haut.
- Vous pouvez vérifier une nouvelle version, l’installer et découvrir ses nouveautés depuis un seul endroit.
- Votre activité Discord reste à votre image : les nombres de vues et de J’aime sont masqués par défaut, mais vous pouvez choisir de les afficher.
- Même dans une petite fenêtre, les paramètres restent simples à parcourir grâce à un défilement discret.

## 1.2.6 — Language Update — 21 septembre 2026

Music Desktop est maintenant disponible en français et en anglais.

- Choisissez la langue que vous préférez dans les paramètres.
- Après le redémarrage, les menus, le mini-lecteur, les notifications et les paramètres suivent votre choix.
- Choisissez la langue de Music Desktop pendant l’installation, puis changez-la à tout moment depuis les paramètres.

## 1.2.5 — Un mini-lecteur plus vivant — 21 septembre 2026

Cette mise à jour rend le mini-lecteur plus agréable à utiliser au quotidien, avec une présentation plus immersive et des commandes plus fiables.

> Si vous utilisez déjà la version 1.2.4, téléchargez et installez cette version une dernière fois depuis GitHub. Les mises à jour suivantes reprendront ensuite automatiquement.

- Une nouvelle ambiance visuelle : la pochette du morceau anime désormais le fond du mini-lecteur et accompagne les changements de titre.
- Une lecture plus claire : les commandes ont été revues, le volume reste accessible en un geste et l’accès à la fenêtre principale est plus simple.
- Une progression enfin fiable : le temps affiché, la barre de lecture et le volume suivent mieux ce qui se passe réellement dans YouTube Music, même à l’enchaînement des titres.
- Une présence Discord plus personnelle : lorsque l’option est activée, la pochette du morceau écouté peut s’afficher dans votre activité.
- Une notification de mise à jour plus discrète et mieux intégrée à l’application.

## 1.2.4 — Mises à jour intégrées — 21 septembre 2026

- Vérification des nouvelles versions directement depuis les paramètres de l’application.
- Téléchargement, progression et installation après confirmation de l’utilisateur.
- Chaque paquet de mise à jour est vérifié par signature cryptographique avant son installation.

## 1.2.3 — 20 septembre 2026

- Ajout d’une option décochée par défaut pour supprimer toutes les données locales lors de la désinstallation.
- La réparation vérifie désormais l’intégrité des fichiers essentiels et ne restaure que ceux qui sont manquants ou endommagés.

## 1.2.2 — 20 septembre 2026

- Nouvel écran de fin d’installation avec des choix cochés par défaut : lancer l’application, créer un raccourci sur le bureau et ajouter Music Desktop à la barre des tâches.

## 1.2.1 — 20 septembre 2026

- Ajout de l’identité visuelle Akyraïs Studio dans l’installateur.

## 1.2.0 — 20 septembre 2026

- Installation pour tous les utilisateurs de l’ordinateur avec demande d’autorisation Windows.
- Détection des installations existantes, avec options de mise à jour, maintenance et désinstallation.
- Intégration du logo Music Desktop dans l’application, l’installateur et les raccourcis Windows.

## 1.1.0 — 20 septembre 2026

- Refonte visuelle de l’installateur pour une présentation plus claire et plus soignée.
- Illustration d’accueil en haute définition.

## 1.0.0 — 20 septembre 2026

- Première version publique de Music Desktop.
- Fenêtre Windows dédiée à YouTube Music.
- Mini-lecteur toujours accessible, zone de notification et Discord Rich Presence facultative.
