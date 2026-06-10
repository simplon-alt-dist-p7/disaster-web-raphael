# Backlog du projet "Optimisation Sante+"

## USER STORIES

---

### Story 1 : Chargement initial plus rapide

**En tant que** nouvel utilisateur web,  
**je veux** que l’écran d’accueil charge en moins de 1,5 s  
**afin de** ne pas décrocher lors d’un pic de réseau lent.

- 🎯 Objectif : temps de chargement < 1500 ms
- 🧱 BP associée : réduire taille des ressources / lazy-loading
- 🛠️ KPI : LCP sur web (Lighthouse)
- 📅 Tag roadmap : M2
- Priorité : 7

---

### Story 2 : Réduction poids images

**En tant que** utilisateur récurrent,  
**je veux** que les visuels du dashboard soient plus légers  
**afin de** économiser de la data sur mon forfait.

- 🎯 Objectif : 80% des images converties en WebP
- 🧱 BP associée : compression d’images / formats modernes
- 🛠️ KPI : poids total dossier `/assets` < 2 Mo
- 📅 Tag roadmap : M3
- Priorité : 1

---

### Story 3 : Accessibilité améliorée

**En tant que** utilisateur malvoyant,  
**je veux** que les contrastes texte/fond soient conformes AA  
**afin de** pouvoir utiliser l’app sans difficulté visuelle.

- 🎯 Objectif : conformité AA WCAG
- 🧱 BP associée : respect contrastes (RGESN 6.3)
- 🛠️ KPI : score accessibilité Lighthouse > 90
- 📅 Tag roadmap : M4
- Priorité : 8

---

### Story 4 : Clignotement du texte retiré

**En tant que** utilisateur souffrant d'épilépsie,  
**je veux** que le clignotement du texte soit supprimé 
**afin de** pouvoir utiliser l’app sans difficulté visuelle.

- 🎯 Objectif : suppression des animations sur les textes 
- 🧱 BP associée : choix plus sobres pour texte (RGESN 4.7)
- 🛠️ KPI : réduction poids visuel
- Priorité : 2

---

### Story 5 : Animation réduite

**En tant que** utilisateur régulier,  
**je veux** que le nombre de cubes animés soit diminué
**afin de** pouvoir utiliser l’app lors d'un pic de réseau plus lent.

- 🎯 Objectif : réduction des animations sur les cubes
- 🧱 BP associée : choix plus sobres pour texte (RGESN 4.7)
- 🛠️ KPI : réduction poid visuel
- Priorité : 6

---

### Story 6 : Réduction du nombre d'animation et hover
**En tant que** utilisateur régulier,  
**je veux** qu'il y ait moins d'animation et de hover
**afin de** améliorer mon expérience.

- 🎯 Objectif : réduire le nombre d'animation dans la page
- 🧱 BP associée : limiter les éléments distrayant et inutiles
- 🛠️ KPI : réduction des éléments dynamiques
- Priorité : 4

---

### Story 7 : Téléchargements des polices d'écriture

**En tant que** développeur de l'application,  
**je veux** télécharger les polices utilisés
**afin de** réduire le nombre d'appels externes à l'application.

- 🎯 Objectif : réduire les appels externes à l'application
- 🧱 BP associée : limiter le nombre des polices de caractères téléchargés (RGESN 4.8)
- 🛠️ KPI : réduction des appels externes
- Priorité : 5

---

### Story 8 : Centraliser le style CSS

**En tant que** développeur de l'application,  
**je veux** centraliser le style CSS du frontend en un seul endroit
**afin de** réduire le nombre d'appels au backend.

- 🎯 Objectif : réduire les appels au backend
- 🧱 BP associée : limiter les injections du backend sur le frontend
- 🛠️ KPI : réduction des injections backend
- Priorité : 3