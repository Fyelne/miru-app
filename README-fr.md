<p align="center">
<img width="300" src="./assets/icon/logo.png" alt="Miru 看板娘"/>
</p>

<h1 align="center">
Application Miru
</h1>

<p align="center">Application multi-fonctionnelle gratuite et open source prenant en charge la vidéo, les bandes dessinées, les novels, avec des sources étendues pour Android, Windows, Web.</p>

<h1 align="center">

[![GitHub release (with filter)](https://img.shields.io/github/v/release/miru-project/miru-app)](https://github.com/miru-project/miru-app/releases/latest)
[![License](https://img.shields.io/github/license/miru-project/miru-app)](https://github.com/miru-project/miru-app/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/miru-project/miru-app)](https://github.com/miru-project/miru-app/stargazers)
[![GitHub all releases](https://img.shields.io/github/downloads/miru-project/miru-app/total)](https://github.com/miru-project/miru-app/releases/latest)

</h1>

![screenshot](assets/screenshot/screenshot.webp)

## Fonctionnalités

- Prise en charge de `windows`,`android`
- Prise en charge de l'écriture simple d'extensions, journal de débogage
- Les extensions utilisent le langage JavaScript, et le développement est simple
- Prise en charge d'un dépot d'extensions personnalisé
- Le dépot d'extensions officiel fournit des sources vidéo, qui peuvent être utilisées sans écrire d'extensions
- Prise en charge de la visualisation en ligne de plusieurs sources de vidéos, bandes dessinées et romans, réalisant l'unification de plusieurs plateformes
- Unifier le langage de conception de l'interface utilisateur du système
- Récupération automatique des informations de métadonnées TMDB

## À faire

- [x] BT torrent
- [ ] Meilleurs outils de débogage
- [ ] Synchronisation des données
- [ ] Recherche automatique des sous-titres

## Installation

Vous pouvez aller sur [Release](https://github.com/miru-project/miru-app/releases/latest) pour télécharger la dernière version du package d'installation depuis la page, ou le construire vous-même avec la méthode suivante

## Construction

### Installer Flutter

Veuillez vous référer à la [documentation officielle de Flutter](https://flutter.dev/docs/get-started/install).

### Installer les dépendances

```bash
flutter pub get
```

### Exécuter

```bash
flutter run
```

### Construire pour la plateforme appropriée

Android

```bash
flutter build apk
```

Windows

```bash
flutter build windows
```

## À propos de Linux

Actuellement, Linux ne peut pas démarrer quickjs en raison de problèmes de dépendances, donc il n'est pas pris en charge pour le moment

## Contribution

Tous types de contributions sont les bienvenues, y compris mais sans s'y limiter :

- Faire une suggestion
- Retour d'erreur
- Contribution de code
- Rédaction de documents

## Liens supplémentaires

Telegram : https://t.me/MiruChat

Chaîne Telegram : https://t.me/MiruChannel
