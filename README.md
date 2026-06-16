# Del Player

Del Player est une application de streaming musical moderne et riche en fonctionnalités, développée avec Flutter. Elle offre une expérience d'écoute fluide avec streaming en ligne, lecture hors ligne et une interface Material You.

## Fonctionnalités

- Streaming musical – Recherchez et écoutez des millions de chansons en ligne
- Mode hors ligne – Téléchargez des playlists et des chansons pour une écoute sans connexion
- Égaliseur – Égaliseur 10 bandes intégré avec presets
- SponsorBlock – Ignorez les segments sponsorisés dans les pistes prises en charge
- Paroles – Affichez les paroles synchronisées de vos chansons préférées
- Playlists – Créez, gérez et partagez des playlists personnalisées
- Minuteur – Programmez l'arrêt automatique de la lecture
- Couleurs dynamiques – Thème Material You sur Android 12+
- Sauvegarde et restauration – Ne perdez jamais vos données
- 21 langues – Interface entièrement localisée
- Sans publicité – Expérience complètement sans pub
- Sans abonnement – Gratuit et open source

## Premiers pas

### Prérequis

- Flutter SDK >=3.12.0
- Dart SDK >=3.12.0

### Installation

```bash
git clone <repo-url>
cd del_player
flutter pub get
flutter run
```

### Construction pour Android

```bash
# Flavor GitHub
flutter build apk --flavor github

# Flavor FDroid
flutter build apk --flavor fdroid
```

## Technologies

- Framework : Flutter
- Gestion d'état : Hive + ValueNotifier
- Audio : audio_service + just_audio
- Routage : go_router
- Stockage local : Hive
- Localisation : Flutter i18n (fichiers ARB)

## Licence

Ce projet est sous licence GNU General Public License v3.0. Voir le fichier LICENSE.
