# Analyse de la croissance des enfants — Projet BUT 3 Science des Données  
## Parcours : Exploration & Modélisation Statistique  
**Auteur : Saânbèterfaa Joël DABIRE**

---

## 🇫🇷 Résumé (FR)
Ce projet analyse les trajectoires de croissance (taille, poids, IMC) d'une cohorte d'enfants (1–18 ans) à partir d'un jeu de données longitudinal. Après nettoyage et harmonisation (interpolation spline), l'étude compare profils filles/garçons, teste 6 méthodes de classification supervisée et retient le meilleur modèle (KNN) pour produire une liste d'enfants à surveiller (IMC extrême et discordance morphologique).

### Objectifs
- Prétraitement et harmonisation des trajectoires  
- Analyse descriptive et tests statistiques par âge  
- Comparaison de modèles supervisés (Arbre, LDA, QDA, KNN, Bayes, Régression logistique)  
- Détection d'anomalies (IMC et discordance prédite)  
- Produire une vitrine reproductible pour démontrer compétences en data science

### Contenu du dépôt
- `data/` : `croissance.csv` (jeu de données, échantillon ou instructions de téléchargement)  
- `notebooks/` : `Sujet1_Croissance des enfants.Rmd` (analyse complète, RMarkdown)  
- `reports/` : `Projet_SAE_de_data_mining_final.pdf` + `figures/hero.png`  
- `docs/` : site portfolio (GitHub Pages)  
- `src/` : fonctions R réutilisables (optionnel)

### Résultats clés (synthèse)
- Meilleur modèle : **KNN** (accuracy ≈ 72.5%)  
- Nombre d'enfants analysés : 9 184 (125 933 mesures)  
- Enfants identifiés à surveiller (IMC ou discordance) : **5 374** (111 cumul)  

### Reproduction rapide (local)
1. Cloner le repo  
```bash
git clone https://github.com/Sadabire/Croissance-enfants.git
cd Croissance-enfants

