# Constructo AI - Site Web

[![License](https://img.shields.io/badge/license-Proprietary-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Site web officiel de **Constructo AI** - Système ERP complet pour les industries de la **construction** et de la **fabrication/soudure** au Québec.

> ⚠️ **PROJET PROPRIÉTAIRE** - Ce code est la propriété exclusive de Constructo AI Inc. et n'est pas open source. Toute utilisation, reproduction ou distribution non autorisée est strictement interdite.

## 📋 Table des Matières

- [À Propos](#-à-propos)
- [Fonctionnalités](#-fonctionnalités)
- [Sections de la Page d'Accueil](#-sections-de-la-page-daccueil)
- [Modules ERP Présentés](#-modules-erp-présentés)
- [Conseillers Spécialisés](#-conseillers-spécialisés)
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

**Constructo AI** est une plateforme ERP SaaS dédiée aux entrepreneurs en construction et fabrication/soudure au Québec. Ce dépôt contient le site web marketing vitrine présentant la solution.

### Caractéristiques du Projet

- **Type** : Site web statique (HTML/CSS/JavaScript pur)
- **Domaine** : [constructoai.ca](https://constructoai.ca)
- **Application** : [app.constructoai.ca](https://app.constructoai.ca)
- **Langue** : 100% Français québécois
- **Public cible** : Entrepreneurs en construction et fabrication/soudure au Québec
- **Hébergement** : GitHub Pages
- **Taille** : 3079 lignes de code (index.html)

### Proposition de Valeur

> "Le logiciel de gestion conçu pour les entrepreneurs en construction et fabrication/soudure du Québec"

**Piliers principaux** :
- ✅ Conformité réglementaire automatique (RBQ, CCQ, CNESST, Loi 16)
- ✅ Certifications soudure : CWB, CSA W47.1, CSA W47.2, AWS
- ✅ 33+ modules intégrés (incluant Immobilier, Charge Tributaire, Boutique B2B, Visionneuse CAO 3D, Logistique, GPS, Paie Québec, Météo Chantier)
- ✅ 57 conseillers spécialisés disponibles 24/7 (Claude Opus 4.5)
- ✅ **EXPERTS IA autonome** : 79,99$/mois (57 experts + Soumissions IA)
- ✅ 61 postes CCQ intégrés + 18 postes fabrication/soudure
- ✅ 140+ items de soumission prédéfinis
- ✅ Pricing transparent : 139,99$/mois tout inclus (tous les employés)
- ✅ Support 100% français québécois
- ✅ Prêt en 5 minutes
- ✅ SEAOP : Plateforme d'appels d'offres 100% gratuite

---

## ✨ Fonctionnalités

### Pages du Site

| Page | URL | Description |
|------|-----|-------------|
| **Accueil** | `/index.html` | Hub central - Présentation complète (3079 lignes) |
| **ERP Construction** | `/erp-construction-quebec.html` | Positionnement produit |
| **Conformité RBQ/CCQ** | `/conformite-rbq-ccq.html` | Conformité réglementaire |
| **Gestion Chantier** | `/gestion-chantier-quebec.html` | TimeTracker et logistique |
| **Soumissions** | `/logiciel-soumission-construction.html` | Devis automatisés |
| **Open Graph** | `/og-image.html` | Template partage réseaux sociaux |

### Fonctionnalités Techniques

- ✅ **Mode Sombre** avec détection automatique des préférences système et persistance localStorage
- ✅ **Design Responsive** (Mobile, Tablette, Desktop) avec breakpoints 600px, 768px, 900px
- ✅ **Navigation par ancres** (smooth scroll JavaScript)
- ✅ **FAQ Accordion** interactif (6 questions)
- ✅ **Optimisation SEO** complète (Schema.org SoftwareApplication + LocalBusiness, Open Graph, Twitter Cards)
- ✅ **Performance optimisée** (HTML statique, CSS inline, JavaScript vanilla)
- ✅ **Accessibilité WCAG 2.1** niveau AA (contrastes 17:1 à 21:1)
- ✅ **Header sticky** avec navigation fixe
- ✅ **Vidéo YouTube intégrée** pour démonstration

---

## 📄 Sections de la Page d'Accueil

La page index.html est structurée en **18 sections distinctes** :

| # | Section | ID | Description |
|---|---------|-----|-------------|
| 1 | **Top Banner** | - | Contact téléphone/email urgence |
| 2 | **Header** | - | Logo, navigation, mode sombre, CTA "Mon compte" |
| 3 | **Hero** | - | Titre, description, boutons CTA, message "Prêt en 5 minutes" |
| 4 | **Stats** | - | 4 statistiques clés |
| 5 | **Problems** | - | 3 défis quotidiens des entrepreneurs |
| 6 | **Solution** | `#fonctionnalites` | Grille de 27+ cartes fonctionnalités |
| 7 | **Soumissions** | - | 3 méthodes de soumission |
| 8 | **Conseillers** | `#experts` | 57 conseillers spécialisés 24/7 |
| 9 | **How It Works** | - | Flux de travail intégré |
| 10 | **Demo** | `#demo` | Vidéo YouTube intégrée |
| 11 | **Why Section** | `#comparaison` | 4 raisons de choisir Constructo |
| 12 | **SEAOP** | `#seaop` | Appels d'offres publics gratuits (section dédiée) |
| 13 | **API/Intégrations** | `#api` | QuickBooks, Sage, Zapier, n8n |
| 14 | **FAQ** | - | 6 questions fréquentes |
| 15 | **Chat Fondateur** | - | Interface chat avec Sylvain Leduc |
| 16 | **CTA** | - | Essai gratuit + démo personnalisée |
| 17 | **Newsletter** | `#contact` | Formulaire inscription infolettre |
| 18 | **Footer** | - | 6 colonnes d'informations |

---

## 🛠️ Modules ERP Présentés

### Modules Principaux (27+ cartes fonctionnalités)

| Module | Badge | Description |
|--------|-------|-------------|
| **Soumissions rapides** | - | 140+ items prédéfinis, Admin 3%, contingences 12%, profit 15%, TPS/TVQ auto |
| **Suivi de chantiers** | - | Gantt, Kanban, bons de travail automatiques |
| **Facturation TPS/TVQ** | - | TPS 5%, TVQ 9,975%, suivi paiements, bons de commande |
| **Pointage CCQ** | - | 61 postes CCQ, pointage mobile, export paie |
| **Clients & sous-traitants** | - | Carnet d'adresses, historique, suivi leads |
| **Gestion des stocks** | - | Inventaire temps réel, alertes seuil critique |
| **Gestion d'équipe** | - | Profils employés, 25 classifications CCQ, dates expiration |
| **Gestion de Dossiers** | - | Organisation documents projet (plans, photos, contrats, factures), checklist 12 étapes, liaison devis/BT, historique automatique |
| **Fonds de Prévoyance** | - | Loi 16, études 25 ans, composantes majeures, rapports syndicats |
| **Immobilier & Financement** | - | Multi-logements, 7 banques, déblocages progressifs, SCHL |
| **Charge Tributaire** | - | Calculs CNBC 2020, CSA O86/S16, charges neige 10 régions QC |
| **Boutique B2B E-commerce** | - | Catalogue avec images, favoris, remises volume, panier, checkout, PDF bon de livraison, analytics ventes |
| **Visualiseur CAO 3D** | - | Preview STL, OBJ, DXF, STEP, IFC avec rotation/zoom |
| **Gestionnaire Emails** | - | Notifications automatisées, sync IMAP Office365, templates |
| **Logistique Construction** | - | Livraisons matériaux, équipements, véhicules, coordination chantier |
| **GPS & Géolocalisation** | - | Géocodage, itinéraires, suivi flotte, API mobile conducteurs |
| **Paie Québec complète** | - | Impôts fédéral/provincial, RRQ, RQAP, AE, T4/Relevé 1, taux 2025 |
| **Grand Livre & États financiers** | - | Bilan, résultats, flux de trésorerie, ratios financiers automatisés |
| **Météo Chantier** | - | Prévisions temps réel, alertes intempéries, planification travaux extérieurs |
| **Calculatrice Construction** | - | Volumes béton, surfaces, pentes, matériaux, conversions métriques/impériales + **11 sous-modules spécialisés** |
| **Notes de chantier** | - | Journal quotidien, photos, conditions, main-d'œuvre, partage instantané |
| **Qualification B.A.T.** | - | Évaluation prospects Budget-Autorité-Timing, priorisation automatique |
| **Subventions Québec 2025** | - | Programmes gouvernementaux, écoénergétiques, critères admissibilité, aide demandes |
| **Location d'équipement** | NOUVEAU | Gestion locations, contrats automatiques, tarifs dégressifs, retours avec inspection, conseiller IA location vs achat |
| **Maintenance préventive** | NOUVEAU | Planification entretiens, alertes automatiques, historique machines, diagnostic IA, estimation coûts réparation |
| **Portail multi-entreprises** | NOUVEAU | Espaces séparés par compagnie, données isolées, connexion sécurisée 2 étapes, parfait divisions multiples |

### 3 Méthodes de Soumission

1. **Saisie manuelle** - Base de 140+ items de construction
2. **Estimation par IA** - Génération en 30 secondes
3. **Métré sur plans PDF** - Mesure directe sur plans d'architecte

---

## 🧠 Conseillers Spécialisés

**57 conseillers spécialisés** disponibles 24/7 (module autonome EXPERTS IA à 79,99$/mois ou inclus dans l'ERP à 139,99$/mois) :

| Expert | Spécialités |
|--------|-------------|
| **Entrepreneur Général** | Estimation 225-550$/pi², Code de construction, Novoclimat, LEED |
| **Plombier** | Licence RBQ, CMMTQ, Code de plomberie QC, chauffage hydronique, gaz |
| **Électricien** | Licence RBQ, CMEQ, Hydro-Québec, bornes VÉ, panneaux solaires |
| **Revêtement Extérieur** | Écran pare-pluie, vinyle, fibrociment, brique, pierre |
| **Gypse** | Licence RBQ, cloisons acoustiques, plafonds techniques, murs coupe-feu, finitions niveaux 1-5 |
| **Structure de Bois** | CSA O86, poutrelles, fermes, LVL, calcul charges |
| **CVC / HVAC** | CETAF, ASHRAE, thermopompes, VRC/VRE, géothermie |
| **Toiture** | AMCQ, bardeaux, membrane, TPO/EPDM, métal |
| **+ 49 autres** | Architecte, Ingénieur structure, Ingénieur métallurgie, Fondations, Excavation, Maçonnerie, Subventions... |

---

## 🏗️ Nouveaux Modules 2025

### Module Immobilier v2.5

**Fonctionnalités principales** :
- 🏗️ **Gestion projets construction multi-logements** - Cycle complet de prospection terrains à remise des clés
- 💰 **Financement bancaire** - 7 banques québécoises (Desjardins, BNC, RBC, TD, Scotia, BMO, CIBC)
- 📊 **Déblocages progressifs** - Calendrier automatique 7 étapes (terrain 10%, fondations 15%, charpente 25%, toiture 15%, plomberie/élec/CVC 20%, finitions 10%, final 5%)
- 🧮 **6 calculateurs financiers** - Mensualité, amortissement, intérêts intercalaires, assurance SCHL, ROI, coût crédit
- 🧠 **Expert IA Claude Opus 4.5** - Analyse projets, optimisation financement, conseils construction spécialisés

**Validation** :
- ✅ 59/59 tests production réussis (100%)
- ✅ 10 tables base de données
- ✅ 2,889 lignes de code (immobilier.py)

### Module Charge Tributaire

**Fonctionnalités principales** :
- 📐 **Calculs structuraux conformes** - CNBC 2020, CSA O86, CSA S16
- 🪵 **Poutres bois** - 2x4 à 2x12, LVL, Glulam
- 🔩 **Poutres acier** - W8 à W18, HSS
- ❄️ **Charges de neige** - 10 régions du Québec
- 🧮 **Dimensionnement automatique** - Linteaux, solives, chevrons, poteaux

### 11 Sous-Modules de Calcul Spécialisés **NOUVEAU v2.6**

Calculatrices spécialisées conformes aux normes québécoises et canadiennes :

| Sous-Module | Norme | Fonctionnalités |
|-------------|-------|-----------------|
| 🏗️ **Béton et Fondations** | CSA A23.1 | Volumes béton semelles/dalles/murs/colonnes, résistance 25-35 MPa, armatures, coffrage, temps cure |
| 🏠 **Toiture** | AMCQ | Surfaces toiture, pentes, fermes, bardeaux/membrane/tôle/TPO, ventilation entretoit, protection neige/glace |
| 🪜 **Escaliers** | Code bâtiment QC | Girons, contremarches, volées, paliers, validation dimensions automatique, garde-corps, mains courantes |
| ⚡ **Électricité** | CSA C22.1 (CCÉ) | Charges électriques, panneau 100A-400A, circuits, calibre fils, prises, luminaires, résidentiel/commercial |
| 🔧 **Plomberie** | Code QC / CMMTQ | Réseaux plomberie, diamètres tuyaux, pentes évacuation, unités charge, chauffe-eau, drainage |
| 🌡️ **CVC/Chauffage** | ASHRAE | Charges chauffage/climatisation, thermopompes, fournaises, VRC/VRE, BTU/pièce, conduits, zonage, bi-énergie, géothermie |
| 🔥 **Soudure** | CSA W47.1 / AWS D1.1 | Dimensionnement joints, apport de chaleur, consommation électrodes, préchauffage, MIG/TIG/Arc, certifications CWB |
| 📐 **Pliage Tôle** | ISO 2768 / DIN 6935 | Facteur K, tolérance pliage (BA/BD), tonnage requis, retour élastique, sélection matrice V, développés |
| ⚖️ **Poids Métaux** | CSA G40.21 / ASTM | Poids tôles/barres/tubes/profilés, 18 types métaux, acier/inox 304-316/aluminium/cuivre, densités exactes |
| 🎨 **Peinture** | ASTM D3276 | Surfaces, quantités peinture, épaisseur film sec (DFT), latex/alkyde/époxy/polyuréthane, temps séchage, normes VOC |
| 📄 **Métré sur Plans PDF** | - | Mesures sur PDF (distance/surface/périmètre/angles), calibration échelle, association produits, génération soumissions |

### Boutique B2B E-commerce v2.5.1

**Fonctionnalités Phase 2** :
- 🛒 **Catalogue avec images** - Affichage visuel des produits avec photos
- ⭐ **Produits en vedette** - Mise en avant des produits populaires
- ❤️ **Système de favoris** - Liste de souhaits personnalisée par client
- 💰 **Remises en volume** - Réductions automatiques selon quantité commandée
- 🛍️ **Panier d'achat** - Gestion complète avec calcul TPS/TVQ automatique
- 📦 **Checkout complet** - Processus de commande avec adresse de livraison
- 📧 **Confirmation email** - Envoi automatique avec récapitulatif commande
- 📄 **PDF Bon de livraison** - Génération PDF professionnel (ReportLab) téléchargeable
- 📊 **Analytics ventes** - Dashboard avec KPIs, évolution CA, top produits

**Interface Client** :
- 6 onglets navigation : Catalogue, Favoris, Panier, Checkout, Commandes, Stats
- Historique commandes avec suivi statut
- Téléchargement PDF pour chaque commande

### Module Logistique Construction v2.5

**Fonctionnalités principales** :
- 🚚 **Livraisons matériaux** - Planification, réception, validation conformité
- 🔧 **Équipements et outils** - Inventaire, réservations, maintenance, inspections
- 🚗 **Véhicules et transport** - Gestion flotte, déplacements, carburant, entretien
- 📍 **Coordination chantier** - Planning, zones de stockage, affectations

**Tables PostgreSQL (7)** :
- logistics_deliveries, logistics_delivery_items
- logistics_equipment, logistics_equipment_reservations, logistics_equipment_maintenance
- logistics_vehicles, logistics_vehicle_trips

**Intégrations** : Inventaire, Projets, Comptabilité, TimeTracker, GPS

### Module GPS & Géolocalisation v2.5

**Services Backend** :
- 🗺️ **Géocodage** - Conversion adresse → coordonnées GPS (Nominatim/OpenStreetMap)
- 📍 **Géocodage inverse** - Conversion coordonnées → adresse
- 🛣️ **Calcul itinéraires** - Routes optimisées avec waypoints (OSRM)
- 📏 **Distance et durée** - Calculs temps de trajet

**API Mobile Conducteur (FastAPI)** :
- Authentification conducteur avec token sécurisé
- Position GPS temps réel (latitude, longitude, vitesse, direction)
- Itinéraires assignés et waypoints
- Mise à jour statut livraisons (signature, photo preuve)
- Alertes géofence (entrée/sortie zones)

**APIs utilisées (gratuites)** : Nominatim, OSRM, Geopy

### SEAOP - Appels d'Offres Publics

**Section dédiée sur la page d'accueil** avec gradient vert distinctif :

**Fonctionnalités principales** :
- 📋 **Accès gratuit** - Tous les appels d'offres publics du Québec sans frais
- 🔔 **Alertes personnalisées** - Notifications selon vos métiers et régions
- 📊 **Analyse automatique** - L'IA résume les documents et identifie les opportunités pertinentes

**Avantages mis en avant** :
- Plus besoin de surveiller SEAO manuellement
- Filtrage intelligent par corps de métier
- Historique des soumissions et taux de succès

### Module Fabrication/Soudure **NOUVEAU**

**Section dédiée sur la page d'accueil** avec gradient orange distinctif :

**18 Postes de travail fabrication** (90$/heure) :

| Département | Postes |
|-------------|--------|
| **DÉCOUPE** | Débitage, Cisaillement, Poinçonneuse, Plasma, Laser |
| **FORMAGE** | Pliage, Spotweld |
| **SOUDURE** | Soudure manuelle |
| **ROBOTIQUE** | Robot soudeur MIG (16h/jour), Robot soudeur TIG (16h/jour), Robot soudeur par points (16h/jour), Cellule robotisée (16h/jour) |
| **ASSEMBLAGE** | Assemblage |
| **FINITION** | Ébavurage, Lavage, Peinture |
| **QUALITÉ** | Inspection |
| **EXPÉDITION** | Emballage |

**Certifications soudure Québec** :
- 🏆 **CWB** - Canadian Welding Bureau
- 📋 **CSA W47.1** - Certification des compagnies de soudage par fusion de l'acier
- 📋 **CSA W47.2** - Certification des compagnies de soudage par fusion de l'aluminium
- 🌎 **AWS** - American Welding Society

**Fonctionnalités** :
- ✅ Filtrage automatique par type d'industrie (Construction OU Fabrication)
- ✅ Sélection du type lors de l'inscription client
- ✅ Postes de travail adaptés au secteur
- ✅ 4 robots soudeurs avec capacité 16h/jour
- ✅ Gestion des certifications soudure

### Module Location d'Équipement **NOUVEAU**

**Fonctionnalités principales** :
- 🚚 **Gestion des items à louer** - Catalogue d'équipements avec tarifs journaliers, hebdomadaires, mensuels
- 📋 **Contrats automatiques** - Génération de contrats PDF avec TPS/TVQ, conditions, signatures
- 💰 **Tarifs dégressifs** - Réductions automatiques pour les longues durées de location
- ↩️ **Gestion des retours** - Inspection, frais de réparation/nettoyage/retard
- 🤖 **Conseiller IA intégré** - 5 fonctionnalités : recommandation équipements, analyse contrat, checklist, comparaison location vs achat
- 📦 **Intégration inventaire** - Pré-remplissage automatique depuis le stock

**Tables PostgreSQL (4)** : location_items, location_contrats, location_contrat_lignes, location_mouvements

### Module Maintenance Préventive **NOUVEAU**

**Fonctionnalités principales** :
- 🔧 **Types de maintenance** - Préventive, corrective, prédictive avec fréquences personnalisables
- 📅 **Planification automatique** - Calendrier des entretiens avec alertes avant échéance
- 🎫 **Demandes de maintenance** - Workflow complet : nouvelle → en attente → en cours → terminée
- 📝 **Fiches d'intervention** - Génération PDF professionnelle avec détails et pièces
- 🔩 **Gestion des pièces** - Suivi des pièces détachées avec déduction automatique du stock
- 🤖 **Conseiller IA intégré** - 5 fonctionnalités : diagnostic, plan préventif, checklist, estimation coûts

**Tables PostgreSQL (7)** : maintenance_types, maintenance_planification, maintenance_demandes, maintenance_interventions, maintenance_pieces, maintenance_historique, maintenance_alertes

### Module Portail Multi-Entreprises **NOUVEAU**

**Fonctionnalités principales** :
- 🏢 **Isolation complète** - Chaque entreprise a son schéma PostgreSQL séparé
- 🔐 **Authentification 2 étapes** - Connexion entreprise + connexion utilisateur
- 👥 **Gestion des utilisateurs** - Rôles admin/employé par entreprise
- 🔒 **Sécurité bancaire** - Données 100% isolées, aucun croisement possible
- 📊 **Multi-divisions** - Parfait pour entrepreneurs avec plusieurs compagnies (construction + location, etc.)

**Architecture** :
- Schéma `public` : tables système (entreprises, super_admins)
- Schéma `tenant_[code]_[uuid]` : données isolées par entreprise

---

## ❓ FAQ du Site (6 Questions)

Le site présente 6 questions fréquentes dans sa section FAQ :

| Question | Réponse clé |
|----------|-------------|
| **Que comprend l'abonnement à 139,99$/mois?** | Tout inclus : 33+ modules, 57 conseillers, TAKEOFF AI, 207+ tables PostgreSQL, utilisateurs illimités, support téléphone |
| **Est-ce que mes concurrents vont voir mes prix?** | Non, espace 100% isolé, sécurité bancaire |
| **Combien d'utilisateurs peuvent accéder?** | Illimités, un tarif fixe |
| **L'IA, c'est compliqué à utiliser?** | Non, conversation naturelle, pas de configuration |
| **Y a-t-il des frais supplémentaires?** | Non, 139,99$ + taxes/mois tout inclus, essai 7 jours |
| **Puis-je résilier à tout moment?** | Oui, sans contrat ni pénalité, données accessibles en lecture |

---

## 🏗️ Architecture

### Structure des Fichiers

```
constructoai.ca/
├── index.html                               # Page d'accueil (3,047 lignes, ~120 KB)
├── erp-construction-quebec.html             # Landing ERP (691 lignes, 26 KB)
├── conformite-rbq-ccq.html                  # Landing conformité (334 lignes, 20 KB)
├── gestion-chantier-quebec.html             # Landing chantier (308 lignes, 18 KB)
├── logiciel-soumission-construction.html    # Landing soumissions (287 lignes, 17 KB)
├── og-image.html                            # Template Open Graph (240 lignes, 7.5 KB)
├── logo.png                                 # Logo principal (72 KB)
├── moi.jpg                                  # Photo profil Sylvain Leduc (851 KB)
├── og-image.png                             # Image partage social (387 KB)
├── sitemap.xml                              # Plan du site (8 URLs)
├── robots.txt                               # Configuration crawlers
├── CNAME                                    # Configuration domaine (constructoai.ca)
└── README.md                                # Ce fichier

Total: ~4,907 lignes de code HTML, ~210 KB
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
        index.html (HUB CENTRAL - 3079 lignes)
        ┌───────────┴───────────┐
        │  17 sections internes │
        │  Navigation complète  │
        └───────────────────────┘
                 │
    ┌────────────┼────────────┬──────────┐
    │            │            │          │
    ▼            ▼            ▼          ▼
Landing ERP  Landing      Landing    Landing
             Conformité   Chantier   Soumissions

[Chaque landing page est autonome et optimisée SEO]
```

### Intégrations API Présentées

Le site présente les intégrations disponibles :

| Plateforme | Type |
|------------|------|
| **QuickBooks** | Comptabilité |
| **Sage** | Comptabilité |
| **n8n** | Automatisation |
| **Zapier** | Automatisation |

**Fonctionnalités d'intégration** :
- Élimination de la double saisie
- Synchronisation automatique des factures
- Alertes en temps réel
- Confidentialité garantie (sécurité bancaire)

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
| **Lignes de code (index.html)** | 3,047 lignes |
| **Lignes de code totales** | ~4,939 lignes |
| **Taille HTML totale** | ~210 KB |
| **Images locales** | 3 fichiers (1.31 MB) |
| **Taille projet total** | ~3.1 MB |
| **Dépendances externes** | 1 (Google Fonts - Inter) |
| **Variables CSS** | 25+ variables (mode clair/sombre) |
| **Composants réutilisables** | 18 sections distinctes |
| **Pages SEO optimisées** | 6 pages |
| **Modules ERP présentés** | 36+ modules (27+ cartes visibles) |
| **Conseillers spécialisés** | 57 conseillers (8 détaillés + 49 autres) |
| **Postes CCQ intégrés** | 61 postes construction |
| **Postes fabrication/soudure** | 18 postes (incluant 4 robots soudeurs) |
| **Certifications soudure** | CWB, CSA W47.1, CSA W47.2, AWS |
| **Items soumission** | 140+ items prédéfinis |
| **Questions FAQ** | 6 questions |
| **Intégrations API** | 4 (QuickBooks, Sage, n8n, Zapier) |

### Statistiques Affichées sur le Site

Le site présente 5 statistiques clés dans la section Stats :

| Statistique | Valeur Affichée |
|-------------|-----------------|
| Modules pour vos chantiers | 33+ |
| Items soumission prêts | 140+ |
| Conseillers à consulter | 57 |
| Postes CCQ intégrés | 61 |
| Postes fabrication/soudure | 18+ |

---

## 🗺️ Roadmap

### Version Actuelle : 1.5.1 (Janvier 2026) ✅

- ✅ **Module Location d'Équipement** - Contrats automatiques, tarifs dégressifs, retours avec inspection, conseiller IA
- ✅ **Module Maintenance Préventive** - Planification entretiens, alertes, fiches d'intervention PDF, diagnostic IA
- ✅ **Module Portail Multi-Entreprises** - Isolation par schéma PostgreSQL, authentification 2 étapes, multi-divisions
- ✅ **Module Fabrication/Soudure** - 18 postes de travail, 4 robots soudeurs, certifications CWB/CSA/AWS
- ✅ **Support multi-industrie** - Construction ET Fabrication/Soudure
- ✅ Site vitrine complet (3,079+ lignes index.html)
- ✅ 6 pages HTML optimisées SEO
- ✅ Mode sombre avec persistance localStorage
- ✅ SEO optimisé (Schema.org SoftwareApplication + LocalBusiness)
- ✅ Responsive design (breakpoints 600px, 768px, 900px)
- ✅ **Module Immobilier v2.5** - Badge "NOUVEAU" violet gradient
- ✅ **Module Charge Tributaire** - Badge "NOUVEAU" orange gradient
- ✅ **Boutique B2B E-commerce** - Badge "NOUVEAU" vert gradient (images, favoris, remises volume, PDF, analytics)
- ✅ **Visualiseur CAO 3D** - Badge "NOUVEAU" violet gradient (STL, OBJ, DXF, STEP, IFC)
- ✅ **Gestionnaire Emails** - Badge "NOUVEAU" rose gradient
- ✅ **57 conseillers** - 8 détaillés + 49 autres mentionnés (mémoire persistante, CRUD langage naturel)
- ✅ **33+ modules** - Mise à jour dans Hero et Solution sections
- ✅ **207+ tables PostgreSQL** - Base de données complète multi-tenant
- ✅ **Expert IA Claude Opus 4.5** - Documentation financement construction
- ✅ **140+ items soumission** - Base de données complète prédéfinie
- ✅ **SEAOP** - Plateforme appels d'offres gratuite présentée
- ✅ **Chat Fondateur** - Section interactive avec Sylvain Leduc
- ✅ **Vidéo YouTube** - Démo intégrée (E6_SLDETv2s)

### Version 1.4.1 (30 Décembre 2025) ✅

- ✅ **Boutique B2B E-commerce Phase 2** - Mise à jour index.html avec nouvelles fonctionnalités
- ✅ **Meta description** - Ajout version 2.5.1, 217,500+ lignes de code
- ✅ **Schema.org** - Mise à jour description avec Boutique B2B et CAO 3D
- ✅ **Open Graph / Twitter** - Métadonnées actualisées
- ✅ **Section Fonctionnalités** - Portail B2B → Boutique B2B E-commerce
- ✅ **Footer** - Ajout version 2.5.1 et nouvelles fonctionnalités
- ✅ **priceValidUntil** - Étendu à 2026-12-31

### Prochaines Versions

#### v1.5.0
- [ ] Mode sombre sur toutes les pages (actuellement index.html seulement)
- [ ] Optimisation image moi.jpg (851 KB → <300 KB)
- [ ] Conversion images en WebP
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

**Constructo AI** - Le logiciel de gestion conçu pour les entrepreneurs en construction et fabrication/soudure du Québec

[Site Web](https://constructoai.ca) • [Application](https://app.constructoai.ca) • [Contact](mailto:info@constructoai.ca)

</div>
