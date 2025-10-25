# profile-professionnel
Création d'une Page de Profil Professionnel en HTML et CSS

## Objectif du Projet
L’objectif de cet exercice est de recréer une page de profil similaire au design fourni, inspiré d'une carte de profil professionnel. Ce projet permettra de :
- Se familiariser avec la structure d'une page de profil dans un contexte professionnel.
- Pratiquer l’utilisation de Flexbox et CSS Grid pour organiser les éléments de manière élégante et responsive.
- Renforcer ta compréhension des propriétés CSS avancées pour un rendu professionnel.

## Mise en Page et Structure
Flexbox et Grid sont deux systèmes de mise en page CSS puissants : Flexbox gère les alignements en une seule dimension (ligne ou colonne), tandis que Grid permet des mises en page bidimensionnelles (lignes et colonnes).

### 🧱 Flexbox : Mise en page unidimensionnelle
Flexbox est idéal pour aligner les éléments dans une seule direction — soit horizontalement (ligne), soit verticalement (colonne).

#### 🔑 Concepts principaux
- display: flex : active le mode Flexbox sur un conteneur.
- flex-direction : définit l’orientation (row, column, etc.).
- justify-content : aligne les éléments sur l’axe principal (ex. : center, space-between).
- align-items : aligne les éléments sur l’axe secondaire (ex. : stretch, center).
- flex-grow, flex-shrink, flex-basis : contrôlent la taille des éléments flexibles.
- order : change l’ordre visuel des éléments sans modifier le HTML.

#### ✅ Utilisation typique
.container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}

### 🧮 Grid : Mise en page bidimensionnelle
Grid est conçu pour organiser les éléments en lignes et colonnes, parfait pour des mises en page complexes.

#### 🔑 Concepts principaux
- display: grid : active le mode Grid sur un conteneur.
- grid-template-columns / grid-template-rows : définissent la structure du quadrillage.
- grid-gap ou gap : espace entre les lignes et colonnes.
- grid-column / grid-row : positionnent les éléments dans la grille.
- grid-area : nomme et place les zones de grille.

#### ✅ Utilisation typique
.container {
  display: grid;
  grid-template-columns: 1fr 2fr;
  grid-template-rows: auto;
  gap: 10px;
}
