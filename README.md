[README.md](https://github.com/user-attachments/files/32434531/README.md)
# ⚡ NutriCore — Calculator & Onboarding App

**NutriCore** est une application web moderne et interactive (*Web App*) conçue pour permettre aux utilisateurs de calculer précisément leurs besoins énergétiques journaliers (BMR & TDEE) ainsi que leur répartition en macronutriments (Protéines, Lipides, Glucides) selon leur objectif physique.

---

## 🌟 Fonctionnalités Principales

- **Page d'Accueil (Landing Page)** : Présentation moderne et épurée de la marque NutriCore.
- **Formulaire par Étapes (Wizard / Onboarding)** :
  - **Barre de progression dynamique** ($33\%$, $66\%$, $100\%$) offrant un retour visuel en temps réel.
  - **Mensurations** (Sexe, Âge, Taille, Poids).
  - **Niveau d'activité physique** (de Sédentaire à Très Actif).
  - **Objectif personnel** (Sèche, Sèche excessive, Maintien, Prise de masse, Prise de masse excessive).
- **Validation & Contrôle Strict des Données** :
  - Blocage de la progression si des champs sont vides.
  - Fenêtre pop-up personnalisée en cas de données invalides.
  - Limites physiologiques réalistes (Âge : $1\text{–}120$ ans, Taille : $50\text{–}280$ cm, Poids : $20\text{–}600$ kg).
- **Calculs Énergétiques en Arrière-Plan** :
  - **BMR** (*Basal Metabolic Rate*) basé sur la formule de **Mifflin-St Jeor**.
  - **TDEE** (*Total Daily Energy Expenditure*) ajusté selon le niveau d'activité.
  - Répartition précise des **Macronutriments** ($2\text{ g/kg}$ de protéines, $1\text{ g/kg}$ de lipides, le reste en glucides).
- **Dashboard Récapitulatif** :
  - Affichage clair de l'objectif calorique et des macros.
  - Explications simples et pédagogiques sous chaque valeur.
  - Adaptation dynamique du texte selon l'objectif sélectionné.
- **Interface & UI/UX** :
  - Design inspiré du style *Fitness Park* (Noir Anthracite & Jaune Fluo `#FFDE00`).
  - Animations de transition fluides (*slide*) de droite à gauche entre les étapes.
  - **100 % Responsive** (parfaitement optimisé pour smartphones, tablettes et ordinateurs).

---

## 🛠️ Technologies Utilisées

- **HTML5** : Structure de l'application et accessibilité.
- **CSS3** : Flexbox, CSS Grid, variables CSS (`:root`), animations de transition et design sombre (*Dark Theme*).
- **JavaScript (ES6+)** : Gestion des étapes du formulaire, validation des données, algorithmes de calcul nutritionnel et manipulation dynamique du DOM.

---

## 🚀 Déploiement Rapide sur GitHub Pages

Puisque ce projet fonctionne entièrement côté client (*Frontend Client-Side*), il ne nécessite aucun serveur Node.js distant pour être exécuté.

1. Crée un nouveau dépôt public sur votre compte [GitHub](https://github.com/).
2. Déposez votre fichier `index.html` à la racine du dépôt.
3. Allez dans **Settings** > **Pages**.
4. Sous **Build and deployment**, sélectionnez la branche `main` (ou `master`) et cliquez sur **Save**.
5. Votre site sera disponible en quelques secondes à l'adresse :  
   `https://<votre-pseudo>.github.io/<nom-du-depot>/`

---

## 📊 Formules de Calcul Utilisées

1. **Métabolisme de Base (BMR - Mifflin-St Jeor)** :
   $$\text{Hommes} = (10 \times \text{poids}) + (6{,}25 \times \text{taille}) - (5 \times \text{âge}) + 5$$
   $$\text{Femmes} = (10 \times \text{poids}) + (6{,}25 \times \text{taille}) - (5 \times \text{âge}) - 161$$

2. **Dépense Totale (TDEE)** :
   $$\text{TDEE} = \text{BMR} \times \text{Facteur d'activité } (1{,}2 \text{ à } 1{,}725)$$

---

## 📄 Licence

Ce projet est distribué sous la licence **MIT**. Libre à vous de l'utiliser et de le modifier !
