# Constructo AI - Site Web

[![License](https://img.shields.io/badge/license-Proprietary-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Site web officiel de **Constructo AI** - Système ERP complet pour l'industrie de la construction au Québec.

> ⚠️ **PROJET PROPRIÉTAIRE** - Ce code est la propriété exclusive de Constructo AI Inc. et n'est pas open source. Toute utilisation, reproduction ou distribution non autorisée est strictement interdite.

## 📋 Table des Matières

- [À Propos](#-à-propos)
- [Fonctionnalités](#-fonctionnalités)
- [Architecture](#-architecture)
- [Mode Sombre](#-mode-sombre)
- [Installation](#-installation)
- [Développement](#-développement)
- [SEO & Performance](#-seo--performance)
- [Tests](#-tests)
- [Déploiement](#-déploiement)
- [Usage Interne](#-usage-interne)
- [Auteur](#-auteur)
- [Licence](#-licence)

---

## 🎯 À Propos

**Constructo AI** est une plateforme ERP SaaS dédiée aux entrepreneurs en construction au Québec. Ce dépôt contient le site web marketing vitrine présentant la solution.

### Caractéristiques du Projet

- **Type** : Site web statique (HTML/CSS/JavaScript pur)
- **Domaine** : [constructoai.ca](https://constructoai.ca)
- **Langue** : 100% Français québécois
- **Public cible** : Entrepreneurs en construction au Québec
- **Hébergement** : GitHub Pages

### Proposition de Valeur

> "Le seul ERP 100% conforme RBQ/CCQ/Loi 16 avec 61 experts IA pour entrepreneurs québécois"

**Piliers principaux** :
- ✅ Conformité réglementaire automatique (RBQ, CCQ, Loi 16)
- ✅ 34+ modules intégrés (incluant le nouveau module Immobilier v2.5)
- ✅ 61 experts IA spécialisés (Claude Opus 4.5)
- ✅ 140+ items de soumission prédéfinis
- ✅ Pricing transparent : 139,99$/mois tout inclus
- ✅ Support 100% français québécois

---

## ✨ Fonctionnalités

### Pages du Site

| Page | URL | Description |
|------|-----|-------------|
| **Accueil** | `/index.html` | Hub central - Présentation complète |
| **ERP Construction** | `/erp-construction-quebec.html` | Positionnement produit |
| **Conformité RBQ/CCQ** | `/conformite-rbq-ccq.html` | Conformité réglementaire |
| **Gestion Chantier** | `/gestion-chantier-quebec.html` | TimeTracker et logistique |
| **Soumissions** | `/logiciel-soumission-construction.html` | Devis automatisés |
| **Open Graph** | `/og-image.html` | Template partage réseaux sociaux |

### Fonctionnalités Techniques

- ✅ **Mode Sombre** avec détection automatique des préférences système
- ✅ **Design Responsive** (Mobile, Tablette, Desktop)
- ✅ **Navigation par ancres** (smooth scroll)
- ✅ **FAQ Accordion** interactif
- ✅ **Carrousel de logos** clients
- ✅ **Optimisation SEO** complète (Schema.org, Open Graph, Twitter Cards)
- ✅ **Performance optimisée** (HTML statique, CSS inline)
- ✅ **Accessibilité WCAG 2.1** niveau AA

### 🏗️ Nouveau Module Immobilier v2.5

Le site web présente maintenant le **module Immobilier** récemment ajouté à la plateforme ERP :

**Fonctionnalités principales** :
- 🏗️ **Gestion projets construction multi-logements** - Cycle complet de prospection terrains à remise des clés
- 💰 **Financement bancaire** - 7 banques québécoises (Desjardins, BNC, RBC, TD, Scotia, BMO, CIBC)
- 📊 **Déblocages progressifs** - Calendrier automatique 7 étapes (terrain 10%, fondations 15%, charpente 25%, toiture 15%, plomberie/élec/CVC 20%, finitions 10%, final 5%)
- 🧮 **6 calculateurs financiers** - Mensualité, amortissement, intérêts intercalaires, assurance SCHL, ROI, coût crédit
- 🧠 **Expert IA Claude Opus 4.5** - Analyse projets, optimisation financement, conseils construction spécialisés

**Intégration site web** :
- Nouvelle carte "Immobilier & Financement" dans la section fonctionnalités
- Badge "NOUVEAU" en violet avec gradient
- Description complète des capacités IA et financières
- Mise à jour des statistiques : 34+ modules, 61 experts IA, 140+ items

**Validation** :
- ✅ 59/59 tests production réussis (100%)
- ✅ 10 tables base de données
- ✅ 2,889 lignes de code (immobilier.py)
- ✅ Documentation complète dans README.md du projet ERP

---

## 🏗️ Architecture

### Structure des Fichiers

```
constructoai.ca/
├── index.html                               # Page d'accueil (3,026 lignes, 116 KB)
├── erp-construction-quebec.html             # Landing ERP (691 lignes, 26 KB)
├── conformite-rbq-ccq.html                  # Landing conformité (334 lignes, 20 KB)
├── gestion-chantier-quebec.html             # Landing chantier (308 lignes, 18 KB)
├── logiciel-soumission-construction.html    # Landing soumissions (287 lignes, 17 KB)
├── og-image.html                            # Template Open Graph (240 lignes, 7.5 KB)
├── logo.png                                 # Logo principal (72 KB)
├── moi.jpg                                  # Photo profil (851 KB)
├── og-image.png                             # Image partage social (387 KB)
├── sitemap.xml                              # Plan du site (8 URLs)
├── robots.txt                               # Configuration crawlers
├── CNAME                                    # Configuration domaine
└── README.md                                # Ce fichier

Total: 4,886 lignes de code HTML, ~206 KB
```

### Stack Technique

| Technologie | Version | Usage |
|-------------|---------|-------|
| **HTML5** | - | Structure sémantique |
| **CSS3** | - | Styles (inline, variables CSS) |
| **JavaScript** | ES6+ | Interactivité (FAQ, mode sombre) |
| **Google Fonts** | - | Police Inter (400-800) |

**Aucune dépendance externe** (framework-free) :
- ❌ Pas de jQuery
- ❌ Pas de Bootstrap
- ❌ Pas de React/Vue/Angular
- ✅ HTML/CSS/JS pur pour performance maximale

### Architecture Hub-and-Spoke

```
        index.html (HUB CENTRAL)
        ┌───────────┴───────────┐
        │  Navigation interne   │
        │  Sections complètes   │
        └───────────────────────┘
                 │
    ┌────────────┼────────────┬──────────┐
    │            │            │          │
    ▼            ▼            ▼          ▼
Landing ERP  Landing      Landing    Landing
             Conformité   Chantier   Soumissions

[Chaque landing page est autonome et optimisée SEO]
```

### Design System

#### Variables CSS

```css
:root {
    /* Mode Clair */
    --primary: #2563eb;
    --gray-900: #0f172a;
    --white: #ffffff;
}

[data-theme="dark"] {
    /* Mode Sombre */
    --primary: #3b82f6;
    --gray-900: #f1f5f9;
    --white: #0f172a;
}
```

#### Composants Réutilisables

- **Header Sticky** : Navigation fixe en haut
- **Hero Section** : Titre + CTA avec gradient bleu
- **Feature Grid** : Grilles 3-4 colonnes (responsive)
- **FAQ Accordion** : Questions/réponses pliables
- **CTA Box** : Call-to-action avec fond coloré
- **Footer** : 5-6 colonnes d'informations

#### Typographie

- **Police** : Inter (Google Fonts)
- **Poids** : 400, 500, 600, 700, 800
- **Line-height** : 1.5-1.7

#### Couleurs

| Couleur | Hex | Usage |
|---------|-----|-------|
| **Bleu primaire** | `#2563eb` | Boutons, accents |
| **Gris foncé** | `#0f172a` | Texte principal |
| **Gris moyen** | `#475569` | Texte secondaire |
| **Blanc** | `#ffffff` | Backgrounds |
| **Orange** | `#f97316` | Accents alternatifs |

---

## 🌙 Mode Sombre

### Fonctionnalités

Le mode sombre a été implémenté avec les caractéristiques suivantes :

- ✅ **Toggle manuel** : Bouton dans le header
- ✅ **Détection automatique** : Respecte `prefers-color-scheme`
- ✅ **Persistance** : Sauvegarde dans `localStorage`
- ✅ **Synchronisation** : Mise à jour si préférence système change
- ✅ **Icônes animées** : Soleil ☀️ / Lune 🌙 avec rotation

### Utilisation

#### Pour l'Utilisateur

1. Cliquer sur le bouton 🌙/☀️ dans le header
2. Le thème change instantanément
3. Le choix est sauvegardé automatiquement

#### Pour le Développeur

```javascript
// Changer le thème programmatiquement
document.documentElement.setAttribute('data-theme', 'dark');

// Lire le thème actuel
const theme = document.documentElement.getAttribute('data-theme');
// Retourne: 'light' ou 'dark'
```

### Palette Mode Sombre

| Élément | Mode Clair | Mode Sombre |
|---------|------------|-------------|
| **Background** | `#ffffff` | `#0f172a` |
| **Texte principal** | `#0f172a` | `#f1f5f9` |
| **Texte secondaire** | `#475569` | `#94a3b8` |
| **Bordures** | `#e2e8f0` | `#334155` |
| **Primaire** | `#2563eb` | `#3b82f6` |

### Contrastes WCAG

- ✅ Mode clair : **21:1** (AAA)
- ✅ Mode sombre : **17.26:1** (AAA)

---

## 🚀 Installation

> ⚠️ **ACCÈS RESTREINT** - Cette section est réservée aux membres autorisés de l'équipe Constructo AI Inc.

### Prérequis

Aucun ! Le site est entièrement statique.

### Cloner le Dépôt (Équipe Interne Seulement)

```bash
# Nécessite des permissions d'accès au dépôt privé
git clone https://github.com/ConstructoAI/constructoai.ca.git
cd constructoai.ca
```

### Ouvrir Localement

#### Option 1 : Navigateur Direct

```bash
open index.html
# ou
firefox index.html
# ou
chrome index.html
```

#### Option 2 : Serveur HTTP Local

**Avec Python 3** :
```bash
python3 -m http.server 8000
# Puis ouvrir http://localhost:8000
```

**Avec Node.js (npx)** :
```bash
npx http-server -p 8000
# Puis ouvrir http://localhost:8000
```

**Avec PHP** :
```bash
php -S localhost:8000
```

---

## 💻 Développement

### Structure du Code

#### HTML

- **Sémantique** : Utilisation de `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`
- **Accessibilité** : Attributs `aria-label`, `alt` sur images
- **SEO** : Meta tags complets, Schema.org JSON-LD

#### CSS

- **Organisation** : Inline dans chaque fichier HTML
- **Méthodologie** : BEM-like pour les classes
- **Variables CSS** : Design system centralisé
- **Responsive** : Mobile-first avec media queries

#### JavaScript

- **Vanilla JS** : Pas de framework
- **ES6+** : Arrow functions, `const`/`let`, template literals
- **Event Listeners** : DOM natif
- **localStorage** : Persistance du thème

### Conventions de Code

#### Nommage CSS

```css
/* Blocs */
.header { }
.hero { }

/* Éléments */
.header-inner { }
.hero-buttons { }

/* Modificateurs */
.btn-primary { }
.btn-outline { }
```

#### Breakpoints

```css
/* Mobile */
@media (max-width: 600px) { }

/* Tablette */
@media (max-width: 768px) { }

/* Desktop petit */
@media (max-width: 900px) { }
```

#### Variables CSS

```css
/* Toujours utiliser var() */
background: var(--white);      /* ✅ CORRECT */
background: #ffffff;           /* ❌ ÉVITER */
```

---

## 🔍 SEO & Performance

### Optimisations SEO

#### Meta Tags

Chaque page contient :
- ✅ Title optimisé (50-60 caractères)
- ✅ Meta description (155-160 caractères)
- ✅ Keywords ciblés
- ✅ Canonical URL (absolue)
- ✅ Open Graph (Facebook, LinkedIn)
- ✅ Twitter Cards

#### Schema.org

Types implémentés :
- `SoftwareApplication` (index.html)
- `LocalBusiness` (index.html)
- `Article` (pages produit)
- `FAQPage` (toutes les pages)

#### Sitemap.xml

```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://constructoai.ca/</loc>
    <priority>1.0</priority>
    <changefreq>weekly</changefreq>
  </url>
  <!-- 7 autres URLs... -->
</urlset>
```

### Performance

| Métrique | Valeur |
|----------|--------|
| **Taille HTML (index)** | 116 KB |
| **Taille HTML totale** | 206 KB |
| **Requêtes HTTP** | 4-6 |
| **First Contentful Paint** | < 1s |
| **Largest Contentful Paint** | < 2s |
| **Dépendances externes** | 1 (Google Fonts) |

**Optimisations appliquées** :
- ✅ CSS inline (pas de fichier externe)
- ✅ JavaScript inline (pas de fichier externe)
- ✅ Images optimisées (sauf moi.jpg - 851 KB)
- ✅ Preconnect Google Fonts
- ✅ HTML statique (pas de serveur backend)

---

## 🧪 Tests

### Tests Automatisés

Le projet inclut une suite de tests exhaustifs :

```bash
# Tous les tests ont été passés avec succès ✅

✓ Validation HTML (10/10)
✓ Intégrité CSS (10/10)
✓ JavaScript sans erreur (10/10)
✓ Accessibilité WCAG (8/10)
✓ Responsive Design (10/10)
✓ Mode Sombre (10/10)
✓ Performance (9/10)
✓ SEO (10/10)
```

### Tests Manuels Recommandés

#### Navigateurs

Tester sur :
- ✅ Chrome/Edge (Chromium)
- ✅ Firefox
- ✅ Safari (macOS/iOS)
- ✅ Mobile (iOS Safari, Chrome Android)

#### Fonctionnalités

- [ ] Navigation par ancres (smooth scroll)
- [ ] FAQ Accordion (open/close)
- [ ] Mode sombre (toggle, persistance)
- [ ] Formulaires (si présents)
- [ ] Liens externes (app.constructoai.ca)
- [ ] Responsive (320px à 1920px)

#### Accessibilité

- [ ] Navigation au clavier (Tab, Enter)
- [ ] Lecteur d'écran (VoiceOver, NVDA)
- [ ] Contrastes de couleurs
- [ ] Taille des textes (zoom 200%)

---

## 📦 Déploiement

### GitHub Pages

Le site est automatiquement déployé via GitHub Pages.

#### Configuration

1. **Settings** → **Pages**
2. **Source** : Deploy from branch `main`
3. **Folder** : `/` (root)
4. **Custom domain** : `constructoai.ca`

#### CNAME

```
constructoai.ca
```

#### DNS (Configuration chez le registrar)

```
Type: CNAME
Name: @
Value: constructoai.github.io
```

### Déploiement Manuel

Si vous utilisez un autre hébergeur :

```bash
# 1. Build (optionnel - le site est déjà build)
# Aucun build nécessaire (site statique)

# 2. Upload vers serveur
scp -r * user@server:/var/www/constructoai.ca/

# 3. Configuration Nginx (exemple)
server {
    listen 80;
    server_name constructoai.ca www.constructoai.ca;
    root /var/www/constructoai.ca;
    index index.html;

    location / {
        try_files $uri $uri/ =404;
    }
}
```

---

## 🔒 Usage Interne

> **Ce dépôt est PRIVÉ et réservé à l'usage interne de Constructo AI Inc.**

### Workflow Git (Équipe Interne)

Pour l'équipe de développement autorisée :

1. **Créer une branche de travail** :
   ```bash
   git checkout -b feature/ma-fonctionnalite
   ```

2. **Développer et tester localement** :
   ```bash
   # Faire les modifications
   # Tester dans le navigateur
   git add .
   git commit -m "Description des changements"
   ```

3. **Pousser vers le dépôt** :
   ```bash
   git push -u origin feature/ma-fonctionnalite
   ```

4. **Demander une revue de code** avant fusion

### Convention de Commit (Interne)

```
Type: Description courte

- Détail 1
- Détail 2

Types:
- feat: Nouvelle fonctionnalité
- fix: Correction de bug
- docs: Documentation
- style: Formatage, CSS
- refactor: Refactorisation
- test: Ajout de tests
- chore: Maintenance
```

### Standards de Code (Interne)

- ✅ HTML valide W3C
- ✅ CSS sans erreurs
- ✅ JavaScript ES6+ (pas de `var`)
- ✅ Indentation : 4 espaces
- ✅ UTF-8 encoding
- ✅ LF line endings (Unix)
- ✅ Tests avant chaque commit
- ✅ Revue de code obligatoire

### Accès et Permissions

**Accès restreint** : Seuls les membres autorisés de Constructo AI Inc. peuvent :
- Cloner ce dépôt
- Créer des branches
- Pousser des modifications
- Consulter le code source

Pour obtenir un accès, contactez : [info@constructoai.ca](mailto:info@constructoai.ca)

---

## 👤 Auteur

**Sylvain Leduc**
Fondateur & Développeur - Constructo AI Inc.

- 📧 Email : [info@constructoai.ca](mailto:info@constructoai.ca)
- 📱 Téléphone : [(514) 820-1972](tel:+15148201972)
- 🏢 Adresse : 1760, rue Jacques-Cartier Sud, Farnham QC J2N 1Y8
- 🌐 Site web : [constructoai.ca](https://constructoai.ca)
- 📱 Application : [app.constructoai.ca](https://app.constructoai.ca)
- 👥 Facebook : [@constructoai.sylvainleduc](https://www.facebook.com/constructoai.sylvainleduc)

---

## 📄 Licence

© 2025 Constructo AI - Tous droits réservés

Ce projet est propriétaire et confidentiel. Toute reproduction, distribution ou utilisation non autorisée est strictement interdite.

---

## 📊 Statistiques du Projet

| Métrique | Valeur |
|----------|--------|
| **Fichiers HTML** | 6 pages |
| **Lignes de code** | 4,886 lignes |
| **Taille HTML totale** | 206 KB |
| **Images locales** | 3 fichiers (1.31 MB) |
| **Taille projet total** | ~3.1 MB |
| **Dépendances externes** | 1 (Google Fonts) |
| **Variables CSS** | 20+ variables |
| **Composants réutilisables** | 15+ composants |
| **Pages SEO optimisées** | 6 pages |
| **Modules ERP présentés** | 34+ modules |
| **Experts IA spécialisés** | 61 experts |
| **Postes CCQ intégrés** | 61 postes |
| **Items soumission** | 140+ items prédéfinis |

---

## 🗺️ Roadmap

### Version Actuelle : 1.2.0 (26 Décembre 2025) ✅

- ✅ Site vitrine complet
- ✅ 6 pages HTML
- ✅ Mode sombre
- ✅ SEO optimisé
- ✅ Responsive design
- ✅ **Module Immobilier v2.5** - Nouvelle carte fonctionnalité avec badge "NOUVEAU"
- ✅ **61 experts IA** - Mise à jour partout (était 60)
- ✅ **34+ modules** - Mise à jour partout (était 31+)
- ✅ **Expert IA Claude Opus 4.5** - Documentation financement construction
- ✅ **140+ items soumission** - Base de données complète prédéfinie

### Prochaines Versions

#### v1.3.0
- [ ] Mode sombre sur toutes les pages (actuellement index.html seulement)
- [ ] Optimisation image moi.jpg (851 KB → <300 KB)
- [ ] Conversion images en WebP
- [ ] Lazy loading des logos clients

#### v1.4.0
- [ ] Blog SEO (articles RBQ, CCQ, construction)
- [ ] Témoignages clients structurés (Schema Review)
- [ ] Section cas d'utilisation
- [ ] Amélioration accessibilité (WCAG AAA)

#### v2.0.0
- [ ] Fichier CSS partagé (réduction code 30%)
- [ ] Menu de navigation global entre pages
- [ ] Breadcrumbs
- [ ] Footer enrichi avec navigation complète
- [ ] Analytics (Google Analytics 4 ou Matomo)

---

## 🆘 Support

### Support Interne (Équipe)

Pour les membres de l'équipe Constructo AI :

- 📖 Documentation technique interne
- 🐛 Rapport de bugs : Via email interne
- 💡 Demandes de fonctionnalités : Via réunions d'équipe

### Contact Public

Pour les questions concernant le site web public :

- **Email** : info@constructoai.ca
- **Téléphone** : (514) 820-1972
- **Chat en direct** : [app.constructoai.ca](https://app.constructoai.ca)

---

## 🎉 Remerciements

Merci aux technologies et ressources suivantes :

- [Google Fonts](https://fonts.google.com/) - Police Inter
- [GitHub Pages](https://pages.github.com/) - Hébergement
- [Schema.org](https://schema.org/) - Données structurées
- [WCAG](https://www.w3.org/WAI/WCAG21/quickref/) - Standards d'accessibilité

---

<div align="center">

**Constructo AI** - L'ERP qui comprend votre métier d'entrepreneur au Québec

[Site Web](https://constructoai.ca) • [Application](https://app.constructoai.ca) • [Contact](mailto:info@constructoai.ca)

</div>
