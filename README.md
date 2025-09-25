# 📚 Lecteur de Livre Numérique

Un lecteur de livre élégant et moderne qui transforme vos fichiers Markdown en une expérience de lecture immersive. Parfaitement optimisé pour tous les appareils, du smartphone au desktop.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Fonctionnalités

### 📖 **Expérience de lecture optimale**
- **Design responsive** adaptatif sur tous les appareils
- **Typographie soignée** avec polices premium (Merriweather, Inter)
- **Navigation fluide** avec animations de transition
- **Barre de progression** et numérotation des pages

### 🎨 **Personnalisation avancée**
- **Mode jour/nuit** avec thèmes adaptatifs
- **3 tailles de police** ajustables (Petit, Moyen, Grand)
- **3 familles de polices** (Serif, Sans-serif, Monospace)
- **Contrôle de luminosité** intégré

### 🧭 **Navigation intuitive**
- **Menu des chapitres** avec accès rapide
- **Navigation tactile** par gestes de swipe (gauche/droite)
- **Raccourcis clavier** (flèches gauche/droite)
- **Boutons de navigation** classiques

### 🖼️ **Gestion des images**
- **Support complet des images Markdown**
- **Mode plein écran** pour les images (clic pour agrandir)
- **Légendes automatiques** basées sur le texte alt
- **Lazy loading** pour de meilleures performances

### 📱 **Mobile-first**
- **Interface tactile** optimisée
- **Gestes de navigation** intuitifs
- **Menus adaptatifs** qui ne gênent pas la lecture
- **Performance optimisée** sur tous les appareils

## 🚀 Installation et utilisation

### Installation rapide

1. **Clonez le repository**
```bash
git clone https://github.com/votre-username/lecteur-livre-numerique.git
cd lecteur-livre-numerique
```

2. **Ajoutez votre contenu**
   - Placez votre fichier `book.md` dans le dossier principal
   - Ajoutez vos images dans un dossier `images/` ou `pictures/`

3. **Lancez le lecteur**
   - Ouvrez `index.html` dans votre navigateur
   - Ou servez avec un serveur local pour éviter les restrictions CORS

### Format du fichier book.md

#### Structure de base
```markdown
# Premier Chapitre

Votre contenu ici...

# Deuxième Chapitre  

Suite de votre livre...
```

#### Avec couverture et titre
```markdown
```
title: Mon Livre Fantastique
![Couverture](./cover.png)
```

# Premier Chapitre

Votre contenu commence ici...
```

#### Images dans le contenu
```markdown
# Mon Chapitre

Voici une image avec légende :

![Description de l'image](./images/photo.jpg)

Le texte continue après l'image...
```

## 🎯 Fonctionnalités détaillées

### Navigation
- **Boutons** : Précédent/Suivant en bas de page
- **Clavier** : Flèches ← → pour naviguer
- **Tactile** : Swipe gauche/droite sur mobile et tablette
- **Menu** : Accès direct à n'importe quel chapitre

### Paramètres personnalisables
| Paramètre | Options | Description |
|-----------|---------|-------------|
| **Luminosité** | 30% à 100% | Contrôle la luminosité de toute la page |
| **Taille** | Petit (16px), Moyen (19px), Grand (22px) | Ajuste la taille du texte |
| **Police** | Serif, Sans, Mono | Change la famille de police |
| **Thème** | Jour, Nuit | Bascule entre les modes clair et sombre |

### Support Markdown
- ✅ Titres (`# ## ###`)
- ✅ Texte **gras** et *italique*
- ✅ Listes à puces (`- item`)
- ✅ Images avec légendes
- ✅ Paragraphes avec indentation automatique

## 🎨 Thèmes

### Mode Jour
- Fond crème chaleureux (`#f7dfc6`)
- Texte brun foncé (`#3a2f29`)
- Accents dorés (`#8b6914`)

### Mode Nuit
- Fond sombre (`#2d2d2d`)
- Texte clair (`#e0e0e0`)
- Accents orange (`#ff6b35`)

## 📱 Compatibilité

- ✅ **Chrome** 60+
- ✅ **Firefox** 55+  
- ✅ **Safari** 12+
- ✅ **Edge** 79+
- ✅ **Mobile** iOS Safari, Chrome Mobile
- ✅ **Tablettes** iPad, Android

## 🤝 Contribution

Les contributions sont les bienvenues ! 

1. Fork le projet
2. Créez votre branche (`git checkout -b ma-nouvelle-fonctionnalite`)
3. Commitez vos changements (`git commit -m 'Ajout d'une fonctionnalité'`)
4. Push vers la branche (`git push origin ma-nouvelle-fonctionnalite`)
5. Ouvrez une Pull Request

## 📄 License

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.
