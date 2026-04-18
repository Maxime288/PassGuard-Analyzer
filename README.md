# 🛡️ PassGuard-Analyzer

Un outil léger et performant d'analyse de la complexité des mots de passe, entièrement exécuté côté client. Ce projet permet aux utilisateurs de vérifier la robustesse de leurs identifiants en temps réel.

## 🚀 À propos du projet
Développé pour démontrer les bonnes pratiques de sécurité web, **PassGuard-Analyzer** utilise des expressions régulières (Regex) pour évaluer instantanément la force d'un mot de passe lors de la saisie.

L'objectif est d'éduquer les utilisateurs sur l'importance de la complexité des mots de passe en fournissant une estimation visuelle et théorique du temps de résistance aux attaques par force brute.

## ⚙️ Fonctionnalités
- **Analyse en temps réel :** Le score est mis à jour à chaque touche pressée.
- **Validation multi-critères :** Vérification de la longueur, des majuscules, des chiffres et des caractères spéciaux.
- **Retour visuel dynamique :** Une barre de progression change de couleur selon le niveau de sécurité (Faible, Moyen, Fort, Très Fort).
- **Estimation Cyber :** Indication théorique du temps de cassage par brute-force.

## 🛠️ Stack Technique
- **HTML5 :** Structure sémantique du formulaire.
- **CSS3 :** Design moderne, responsive et transitions fluides.
- **JavaScript (Vanilla) :** Logique métier, Regex et manipulation du DOM.

## ⚠️ Avertissement Cybersécurité
Les estimations de temps de "brute-force" affichées par cet outil sont **purement théoriques et indicatives**. 

Dans un scénario réel, le temps de cassage dépend de nombreux facteurs variables que cet outil ne peut pas mesurer, tels que :
1. La puissance de calcul de l'attaquant (GPU, fermes de serveurs, FPGA).
2. L'utilisation de tables de hachage précalculées (Rainbow Tables).
3. L'algorithme de hashage utilisé côté serveur.

Cet outil est destiné à des fins **éducatives et de sensibilisation**.

## 🚀 Déploiement
Ce projet est compatible avec **GitHub Pages**.
1. Activez GitHub Pages dans les paramètres de votre dépôt.
2. Choisissez la branche `main` (ou `master`).
3. Votre outil sera accessible via votre URL GitHub Pages.

---
*Projet réalisé par [Maxime288](https://github.com/Maxime288)*
