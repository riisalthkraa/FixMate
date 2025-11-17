# Site Web FixMate - Guide d'Utilisation

Site web professionnel pour la présentation de l'application FixMate DiagPC.

**Développé par VIEY David**
Version : 1.0
Date : 17 Novembre 2025

---

## 📁 Structure du Site

```
SITE FIXMATE/
├── index.html              # Page d'accueil
├── fonctions.html          # Page des fonctionnalités détaillées
├── contact.html            # Page de contact
├── cgv.html               # Conditions Générales de Vente
├── mentions-legales.html  # Mentions légales et RGPD
├── styles.css             # Feuille de styles CSS
├── script.js              # Scripts JavaScript
└── README.md              # Ce fichier
```

---

## 🎨 Pages Disponibles

### 1. **Page d'Accueil** (`index.html`)
- Présentation de FixMate
- Tableau comparatif avec la concurrence (CCleaner, Advanced SystemCare, AVG TuneUp)
- Avantages uniques de FixMate
- Section de téléchargement
- Aperçu des fonctionnalités principales

### 2. **Page Fonctions** (`fonctions.html`)
- Détails complets de toutes les fonctionnalités
- Explications des actions sur le PC
- Badges Gratuit/Premium pour chaque fonction
- Tutoriels et guides d'utilisation
- Fonctions couvertes :
  - Diagnostic Système Complet
  - Analyse IA avec Claude
  - Predictive Shield
  - Shield Backup
  - Digital Twin
  - Guides AR
  - One-Click Optimizer
  - Process Manager
  - File Cleaner
  - Startup Manager
  - Mode Expert

### 3. **Page Contact** (`contact.html`)
- Informations du développeur
- Formulaire de contact
- FAQ
- Conseils avant de contacter le support

### 4. **Conditions Générales de Vente** (`cgv.html`)
- Conditions d'utilisation
- Tarification et licences
- Droits et garanties
- Politique de remboursement
- Propriété intellectuelle

### 5. **Mentions Légales** (`mentions-legales.html`)
- Informations légales
- Politique RGPD complète
- Protection des données
- Droits des utilisateurs
- Contact pour exercer vos droits

---

## 🚀 Déploiement

### Option 1 : Hébergement Local (Test)
1. Ouvrir `index.html` directement dans un navigateur
2. Toutes les pages fonctionnent en local

### Option 2 : Hébergement Gratuit
**GitHub Pages :**
1. Créer un repository GitHub
2. Uploader tous les fichiers du dossier `SITE FIXMATE`
3. Activer GitHub Pages dans Settings > Pages
4. Le site sera accessible à `https://username.github.io/repository-name`

**Netlify :**
1. Créer un compte sur Netlify.com
2. Glisser-déposer le dossier `SITE FIXMATE`
3. Le site est en ligne instantanément

**Vercel :**
1. Créer un compte sur Vercel.com
2. Importer le dossier
3. Déploiement automatique

### Option 3 : Hébergement Payant
- OVH, Ionos, o2switch, etc.
- Uploader via FTP
- Configurer le nom de domaine

---

## 🎨 Personnalisation

### Couleurs
Modifier les variables CSS dans `styles.css` :
```css
:root {
    --primary-color: #3b82f6;      /* Bleu principal */
    --secondary-color: #8b5cf6;    /* Violet secondaire */
    --accent-color: #10b981;       /* Vert accent */
}
```

### Contenu
- Tous les textes sont modifiables directement dans les fichiers HTML
- Les images peuvent être ajoutées dans un dossier `assets/images/`
- Remplacer les placeholders de screenshots par de vraies captures

### Formulaire de Contact
Le formulaire utilise actuellement `mailto:` pour ouvrir le client email.

Pour un formulaire avec backend :
1. Créer un backend (PHP, Node.js, etc.)
2. Modifier `script.js` ligne ~60-100
3. Ou utiliser un service comme Formspree, FormKeep

---

## ✅ Fonctionnalités Incluses

### Design
- ✅ Design moderne et professionnel
- ✅ Responsive (mobile, tablette, desktop)
- ✅ Animations au scroll
- ✅ Effets de survol
- ✅ Bouton "Retour en haut"

### Navigation
- ✅ Menu responsive avec hamburger mobile
- ✅ Smooth scroll pour ancres
- ✅ Navigation sticky

### Interactivité
- ✅ Formulaire de contact validé
- ✅ Système de notifications
- ✅ Copie d'email (Ctrl+Clic)
- ✅ Animations d'entrée des éléments

### SEO
- ✅ Balises meta complètes
- ✅ Structure sémantique HTML5
- ✅ Attributs alt (à compléter pour images)
- ✅ Liens internes optimisés

### Performance
- ✅ CSS optimisé
- ✅ JavaScript vanilla (pas de framework lourd)
- ✅ Lazy loading images (prêt à l'emploi)
- ✅ Code minifiable

---

## 📋 Checklist Avant Mise en Ligne

### Contenu
- [ ] Vérifier toutes les informations de contact
- [ ] Relire tous les textes
- [ ] Ajouter de vraies captures d'écran
- [ ] Compléter les liens de téléchargement
- [ ] Vérifier les liens externes

### Légal
- [ ] Compléter le médiateur de la consommation (CGV et Mentions légales)
- [ ] Vérifier la conformité RGPD
- [ ] Ajouter les informations d'hébergement
- [ ] Vérifier les tarifs Premium

### Technique
- [ ] Tester sur différents navigateurs (Chrome, Firefox, Safari, Edge)
- [ ] Tester sur mobile et tablette
- [ ] Vérifier tous les liens
- [ ] Optimiser les images
- [ ] Configurer un certificat SSL (HTTPS)
- [ ] Tester le formulaire de contact
- [ ] Configurer Google Analytics (optionnel)

### SEO
- [ ] Créer un fichier `robots.txt`
- [ ] Créer un fichier `sitemap.xml`
- [ ] Ajouter favicon
- [ ] Vérifier les balises Open Graph pour réseaux sociaux
- [ ] Soumettre à Google Search Console

---

## 🔧 Améliorations Futures

### Court Terme
- Ajouter de vraies captures d'écran de l'application
- Créer un logo et favicon
- Ajouter une page "Téléchargements" avec versions
- Intégrer un système d'analytics

### Moyen Terme
- Blog / Actualités
- Tutoriels vidéo
- Documentation utilisateur en ligne
- FAQ interactive
- Galerie de screenshots

### Long Terme
- Espace client pour licences Premium
- Forum communautaire
- Support en ligne (chat)
- Versions multilingues (EN, ES, DE)
- Programme d'affiliation

---

## 📞 Support

**Développeur :** VIEY David
**Email :** Riisalthkraal@gmail.com
**Projet :** FixMate DiagPC v2.0.0-beta.1

---

## 📄 Licence

Tous les fichiers de ce site sont la propriété de **VIEY David**.

Le design, le contenu et le code sont protégés par le droit d'auteur.

**© 2025 VIEY David - Tous droits réservés**

---

## 🎯 Notes Importantes

### Aucune Mention d'Outils de Développement
Conformément aux directives, ce site ne contient AUCUNE mention de :
- Outils de développement IA
- Frameworks d'aide au développement
- Assistants de code

Le site présente uniquement **FixMate** comme produit de **VIEY David**.

### Conformité
- ✅ RGPD complet dans Mentions Légales
- ✅ CGV professionnelles
- ✅ Formulaire de contact validé
- ✅ Politique de cookies claire
- ✅ Droits utilisateurs expliqués

### Technologies Utilisées
- HTML5 sémantique
- CSS3 moderne (variables, flexbox, grid)
- JavaScript vanilla (ES6+)
- Aucune dépendance externe (légèreté et performance)

---

**Site créé le 17 Novembre 2025**
**Dernière mise à jour : 17 Novembre 2025**

Bon lancement ! 🚀
