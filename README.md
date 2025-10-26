# 💕 Plan Your Date - Personalized Link System

A romantic website to ask someone out on a date, with a personalized link system for easy sharing!

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://alljustkim.github.io/plan-you-date/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🚀 Features

### ✨ Personalized Link System
- Create custom links by adding URL parameters
- Personalize your invitation with:
  - Your name
  - Their name
  - A custom message
  - A WhatsApp number (optional)

### 🎯 Liens Locaux
- Génère des liens locaux du type : `index.html?from=VotreNom&to=LeurNom&msg=Message&phone=Numero`
- Fonctionne entièrement en local, pas besoin de serveur
- Partage facile via SMS, WhatsApp, email, etc.

### 💌 Expérience Personnalisée
- La page principale s'adapte automatiquement aux paramètres URL
- Messages personnalisés selon les informations fournies
- Interface traduite en français

### 📱 Options de Partage Avancées
- **WhatsApp** : Envoi direct avec numéro pré-rempli
- **SMS** : Ouverture de l'app SMS avec message pré-rempli
- **Copie** : Copie du message dans le presse-papiers

## 🛠️ How to Use

### 1. Create a Personalized Link
Add URL parameters to your site URL:
- Format: `index.html?from=YourName&to=TheirName&msg=Message&phone=PhoneNumber`
- Example: `https://alljustkim.github.io/plan-you-date/index.html?from=John&to=Sarah&msg=I%20would%20love%20to%20go%20out%20with%20you&phone=%2B1234567890`

### 2. Share the Link
- **WhatsApp** : Le lien s'ouvrira directement dans WhatsApp
- **SMS** : Copiez le lien et envoyez-le par SMS
- **Email** : Copiez le lien et envoyez-le par email
- **Réseaux sociaux** : Partagez le lien sur vos réseaux préférés

### 3. Réception de l'Invitation
Quand la personne clique sur votre lien :
1. Elle voit votre message personnalisé
2. Elle peut répondre "Oui" ou "Non"
3. Si elle dit "Oui", elle peut choisir une date
4. Elle peut partager sa réponse via WhatsApp, SMS ou copie

## 📁 Structure des Fichiers

```
Plan-your-date-main/
├── index.html              # Main page
├── yes.html                # Confirmation page
├── script.js               # Main script
├── styles.css              # Main styles
├── yes.css                 # Yes page styles
└── README.md               # This file
```

## 🔧 Personnalisation

### Modifier les Messages
Éditez le fichier `script.js` pour changer les messages de persuasion :

```javascript
const messages = [
    "Tu es sûre ?",
    "Vraiment sûre ??",
    // ... ajoutez vos propres messages
];
```

### Modify Styles
- `styles.css` : Main page styles
- `yes.css` : Confirmation page styles

### Add Features
- Extend `yes.html` for more sharing options
- Add animations or effects in CSS files

## 🌐 Deployment

### Local
1. Download all files
2. Open `index.html` in your browser
3. Create your links manually by adding URL parameters

### GitHub Pages
1. Upload all files to your GitHub repository
2. Activate GitHub Pages in Settings
3. Your site will be available at `https://USERNAME.github.io/REPO-NAME/`

## 💡 Exemples d'Utilisation

### Lien Simple
```
index.html?from=Marie&to=Pierre
```

### Lien avec Message
```
index.html?from=Marie&to=Pierre&msg=J%27aimerais%20vraiment%20qu%27on%20passe%20du%20temps%20ensemble
```

### Lien Complet
```
index.html?from=Marie&to=Pierre&msg=J%27aimerais%20vraiment%20qu%27on%20passe%20du%20temps%20ensemble&phone=%2B33123456789
```

## 🎨 Personnalisation Avancée

### Couleurs
Modifiez les variables CSS dans les fichiers pour changer les couleurs :
- Couleur principale : `#d32f2f` (rouge romantique)
- Couleur de succès : `#4caf50` (vert)
- Couleur WhatsApp : `#25d366`

### Images GIF
Remplacez les URLs des GIFs dans :
- `index.html` : GIF principal
- `yes.html` : GIF de célébration

## 📱 Compatibilité

- ✅ Chrome, Firefox, Safari, Edge
- ✅ Mobile et Desktop
- ✅ iOS et Android
- ✅ Fonctionne hors ligne (une fois chargé)

## 🔒 Confidentialité

- Aucune donnée n'est envoyée à des serveurs externes
- Tout fonctionne localement dans le navigateur
- Les informations sont stockées temporairement dans `sessionStorage`
- Pas de cookies ou de tracking

---

**Amusez-vous bien et bonne chance pour votre rendez-vous ! 💕**