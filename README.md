# 💕 Plan Your Date - Personalized Link System

A romantic website to ask someone out on a date, with a personalized link system for easy sharing!

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://alljustkim.github.io/plan-you-date/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🚀 Fonctionnalités

### ✨ Générateur de Liens Personnalisés
- **Page de génération** : `generate-link.html`
- Personnalisez votre invitation avec :
  - Votre nom
  - Le nom de la personne
  - Un message personnalisé
  - Un numéro WhatsApp (optionnel)

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

## 🛠️ Comment Utiliser

### 1. Créer un Lien Personnalisé
1. Ouvrez `generate-link.html` dans votre navigateur
2. Remplissez les informations :
   - Votre nom
   - Le nom de la personne
   - Message personnalisé (optionnel)
   - Numéro WhatsApp (optionnel)
3. Cliquez sur "Générer mon lien personnalisé"
4. Copiez ou partagez le lien généré

### 2. Partager le Lien
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
├── index.html              # Page principale (modifiée)
├── yes.html                # Page de confirmation (modifiée)
├── generate-link.html      # Générateur de liens (nouveau)
├── script.js              # Script principal (modifié)
├── styles.css             # Styles principaux
├── yes.css                # Styles de la page yes
└── README.md              # Ce fichier
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

### Modifier les Styles
- `styles.css` : Styles de la page principale
- `yes.css` : Styles de la page de confirmation
- Styles inline dans `generate-link.html` pour le générateur

### Ajouter des Fonctionnalités
- Modifiez `generate-link.html` pour ajouter plus d'options
- Étendez `yes.html` pour plus d'options de partage
- Ajoutez des animations ou effets dans les fichiers CSS

## 🌐 Déploiement

### Local
1. Téléchargez tous les fichiers
2. Ouvrez `generate-link.html` dans votre navigateur
3. Créez vos liens et partagez-les !

### Serveur Web
1. Uploadez tous les fichiers sur votre serveur web
2. Accédez à votre site via `https://votresite.com/generate-link.html`
3. Les liens générés fonctionneront avec votre domaine

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