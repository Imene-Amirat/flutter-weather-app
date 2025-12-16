# 🌦️ Weather App – Flutter

Application mobile Flutter permettant de consulter la météo actuelle et les prévisions météorologiques sur plusieurs jours à partir d’une ville saisie par l’utilisateur.

---

## 📸 Screenshots de l’application
![WhatsApp Image 2025-12-16 at 11 16 45 PM (1)](https://github.com/user-attachments/assets/adcdfaaa-b224-4825-a0fc-776e7a3c6ff6)
![WhatsApp Image 2025-12-16 at 11 16 45 PM (2)](https://github.com/user-attachments/assets/99035320-66d2-4637-92cd-fa636569dc1a)
![WhatsApp Image 2025-12-16 at 11 16 45 PM (3)](https://github.com/user-attachments/assets/09331c82-ddb9-4b95-96f1-6d177b3e8ec5)



---

## 📱 Fonctionnalités

- 🔍 Recherche de la météo par **nom de ville**
- 🌡️ Affichage de la météo actuelle :
  - température
  - humidité
  - précipitations (pluie/neige)
  - description météo + icône
  - date et heure (en français)
- 📆 Prévisions météo sur **3 à 4 jours**
- 🎨 Interface moderne avec **thème bleu–vert**
- 🖌️ Cartes colorées dynamiquement selon les conditions météo
- ⚠️ Gestion des erreurs (ville introuvable, erreur API)
- ⏳ Indicateur de chargement lors des appels réseau

---

## 🛠️ Technologies utilisées

- **Flutter** (Dart)
- **OpenWeatherMap API**
- Packages Flutter :
  - `http`
  - `intl`
  - `font_awesome_flutter`

---


## 🔑 Configuration de l’API

Cette application utilise l’API **OpenWeatherMap**.

### Étapes :
1. Créer un compte sur https://openweathermap.org
2. Récupérer une clé API gratuite
3. Ajouter la clé dans le fichier suivant :

```dart
// lib/data/config/api_config.dart
class ApiConfig {
  static const String apiKey = "VOTRE_CLE_API_ICI";
  static const String baseUrl = "https://api.openweathermap.org/data/2.5";
  static const String units = "metric";
  static const String lang = "fr";
}


