# 🌍 Visualisation 3D de la Tour Hassan avec CesiumJS

## 🎯 Objectif

Développement d'une application web simple utilisant **CesiumJS** pour visualiser un globe en 3D, centrer la vue sur la ville de **Rabat**, et afficher un **point d’intérêt (POI)** sur la **Tour Hassan**, accompagné d'une description contextuelle dans une info-bulle.

---

## 🧱 Structure du projet

- `index.html` : Fichier principal contenant le code HTML, CSS et JavaScript nécessaire à la visualisation.

---

## ⚙️ Technologies utilisées

- HTML5 / CSS3  
- JavaScript  
- CesiumJS (via CDN)

---

## 🛠️ Étapes de réalisation

### 🔧 Préparation de l’environnement

- Création du fichier `index.html`  
- Intégration de la bibliothèque **CesiumJS** via CDN  
- Mise en place d’un conteneur `<div>` occupant toute la fenêtre pour afficher la scène 3D  

### 🌐 Initialisation du globe

- Utilisation de `Cesium.Viewer` avec le terrain mondial  
- Centrage automatique de la caméra sur **Rabat, Maroc**  

### 📍 Ajout du point d’intérêt (POI)

- Placement d’un marqueur rouge représentant la **Tour Hassan**  
- Ajout d’une info-bulle descriptive qui s’affiche au clic  

### 🧪 Test de l’interaction

- L’utilisateur peut cliquer sur le marqueur pour afficher des **informations historiques** sur la Tour Hassan

---

## 📍 Informations affichées : Tour Hassan

> La **Tour Hassan** est un minaret inachevé situé à **Rabat**, capitale du Maroc.  
> Construite au XIIe siècle par le sultan **Yacoub al-Mansour**, elle devait devenir la plus grande mosquée du monde.  
> Haute de **44 mètres**, elle incarne aujourd’hui un symbole fort de l’architecture almohade et du patrimoine marocain.

---

## 📷 Résultat

- 🌐 Un **globe 3D** centré sur Rabat  
- 📍 Un **marqueur rouge** sur la position exacte de la Tour Hassan  
- 📝 Une **info-bulle** s’affichant avec un texte descriptif au clic

---


