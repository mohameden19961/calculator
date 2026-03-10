# 🧮 Calculator App — Flutter

![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?style=flat&logo=flutter)
![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?style=flat&logo=dart)
![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat&logo=android)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

Une calculatrice moderne développée avec **Flutter & Dart**, avec une interface élégante en thème sombre.

---

## 📲 Télécharger l'APK

> Installer directement sur votre téléphone Android :

**👉 [Télécharger Calculator App v1.0.0](https://github.com/mohameden19961/calculator/raw/main/app-release.apk)**

> ⚠️ **Note :** Activez *"Sources inconnues"* dans **Paramètres → Sécurité** avant l'installation.

---

## 📸 Aperçu

| Écran principal |
|:-:|
| ![Calculator Screenshot](screenshot.png) |

---

## ✨ Fonctionnalités

| Fonctionnalité | Description |
|---|---|
| ➕ ➖ ✖️ ➗ | Les 4 opérations de base |
| 🔢 Chaînage | Enchaîner plusieurs opérations sans `=` |
| ⌫ Retour arrière | Supprimer le dernier chiffre saisi |
| % Pourcentage | Convertir en pourcentage instantanément |
| +/- Négation | Changer le signe du nombre affiché |
| 📜 Historique | Afficher l'expression en cours au-dessus du résultat |
| 🔄 Opérateur actif | L'opérateur sélectionné est mis en surbrillance |
| 🎨 Thème sombre | Interface moderne et lisible |
| 📱 Responsive | S'adapte à toutes les tailles d'écran Android |

---

## 🛠️ Technologies utilisées

- **Flutter 3.x**
- **Dart 3.x**
- `MaterialApp` avec thème sombre personnalisé
- `StatefulWidget` pour la gestion d'état
- `AnimatedDefaultTextStyle` pour les transitions fluides
- `AnimatedSwitcher` pour l'historique animé

---

## 📦 Générer l'APK toi-même

Si tu veux recompiler depuis le code source :

```bash
# 1. Cloner le code source Flutter (séparé)
git clone https://github.com/mohameden19961/calculator.git

# 2. Installer les dépendances
flutter pub get

# 3. Builder l'APK
flutter build apk --release

# L'APK se trouve ici :
# build/app/outputs/flutter-apk/app-release.apk
```

---

## 📁 Structure du projet

```
calculator/
├── app-release.apk    # Application Android
└── README.md          # Ce fichier
```

---

## 🎨 Design

| Élément | Couleur |
|---|---|
| Fond principal | `#1A1A2E` |
| Fond clavier | `#16213E` |
| Boutons chiffres | `#0F3460` |
| Boutons opérateurs | `#533483` |
| Boutons fonctions | `#2D2D4E` |
| Bouton égal | `#4CAF50` ✅ |

---

## 👨‍💻 Auteur

**Mohamed Eden**
- GitHub : [@mohameden19961](https://github.com/mohameden19961)

---

## 📄 Licence

Ce projet est sous licence **MIT** — libre d'utilisation et de modification.

---

<p align="center">
  Fait avec ❤️ et Flutter
</p>
