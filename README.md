# ✅ TodoList Mobile – Ionic + Angular

Cette application mobile est une **Todo List** développée avec le framework **Ionic** basé sur **Angular**. Elle permet à l'utilisateur de créer, modifier et supprimer des tâches depuis une interface mobile moderne.

## 📱 Fonctionnalités

- Ajout, modification et suppression de tâches
- Interface mobile responsive
- Sauvegarde locale ou via API (à adapter)
- Structure modulaire Angular
- Prêt pour une compilation Android/iOS via Capacitor

## 🧰 Technologies utilisées

- **Ionic Framework**
- **Angular**
- **Capacitor** (pour la publication mobile)
- **TypeScript / SCSS**

## 🚀 Installation locale

### Prérequis

- Node.js
- Ionic CLI (`npm install -g @ionic/cli`)
- Android Studio ou Xcode (si build natif)
- Capacitor

### Étapes

```bash
git clone https://github.com/ton-utilisateur/Todolist_application_mobile_IONIC_ANGULAR.git
cd Todolist_application_mobile_IONIC_ANGULAR
npm install
ionic serve
```

L'application s'ouvrira dans le navigateur pour développement rapide.

## ⚙️ Build Mobile

### Android

```bash
ionic build
npx cap add android
npx cap open android
```

### iOS

```bash
ionic build
npx cap add ios
npx cap open ios
```

## 📁 Structure du projet

```
src/
├── app/                # Composants et pages Angular
├── assets/             # Images et styles
├── global.scss         # Feuille de style globale
├── main.ts             # Point d’entrée Angular
```

## 🙌 Remerciements

Merci d’avoir jeté un œil à ce projet !  

<div align="center">
⭐ N’hésite pas à forker, améliorer ou t’en inspirer ! ⭐  
Bon code à toi 🚀

⭐ Un petit like sur le repo fait toujours plaisir ! ⭐  
</div>
