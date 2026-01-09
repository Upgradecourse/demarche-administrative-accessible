# TP – Formulaire de démarche administrative accessible

## Contexte

Vous intervenez sur une **démarche administrative en ligne** destinée au grand public.
Le formulaire existant est fonctionnel mais **présente de nombreux problèmes d’accessibilité,
d’utilisabilité et de conformité RGAA**.

Votre Mission
Vous héritez d'un code source "legacy" contenant les bases d'un formulaire administratif. Votre objectif est de reconstruire une démarche complète et conforme au RGAA 4.1.

Choisissez l'un des parcours suivants :

Parcours CAF : Demande d'aide au logement (focus sur la logique métier complexe).

Parcours ANTS : Renouvellement de permis (focus sur la gestion des pièces jointes).

Parcours Intérieur : Pré-plainte en ligne (focus sur l'expérience utilisateur et le texte libre).

Parcours Élections : Inscription sur les listes (focus sur la précision des données géographiques).

Contraintes techniques :

Respect strict du contraste et de la navigation clavier.

Utilisation des attributs ARIA pertinents.

Optimisation du poids de la page (zéro framework lourd si possible).

Votre mission consiste à :
- auditer le formulaire existant,
- identifier les non-conformités,
- proposer et mettre en œuvre des correctifs,
- tout en respectant les principes de sobriété numérique.

---

## Objectifs pédagogiques

- Appliquer les principes du RGAA et des WCAG 2.1
- Utiliser des outils d’audit d’accessibilité (Wave, Axe, Lighthouse)
- Améliorer l’accessibilité d’un formulaire HTML
- Produire un audit et un plan d’amélioration structurés
- Adopter une démarche professionnelle et argumentée

---

## Contraintes techniques

- HTML sémantique obligatoire
- ARIA uniquement si nécessaire et justifié
- Le formulaire doit rester utilisable :
  - sans souris
  - sans CSS
  - sans JavaScript
- Aucun framework ou librairie externe autorisé
- Sobriété numérique attendue (RGESN)

---

---

## 📚 Ressources et outils recommandés

### Référentiels officiels
* [RGAA (Référentiel Général d'Amélioration de l'Accessibilité)](https://accessibilite.numerique.gouv.fr/) : La référence légale en France.
* [RGESN (Référentiel Général d'Éco-conception des Services Numériques)](https://ecoresponsable.numerique.gouv.fr/publications/referentiel-general-ecoconception/) : Pour les critères de sobriété.
* [W3C - Web Accessibility Initiative (WAI)](https://www.w3.org/WAI/standards-guidelines/wcag/) : La source internationale (WCAG).

### Outils d'audit (Extensions navigateur)
* [Wave Evaluation Tool](https://wave.webaim.org/extension/) : Pour une analyse visuelle immédiate.
* [Axe DevTools](https://www.deque.com/axe/devtools/) : Pour un audit technique précis.
* [Lighthouse](https://developers.google.com/web/tools/lighthouse) : Intégré à Chrome, pour un score global.

### Outils de test de contraste
* [Adobe Color Contrast Analyzer](https://color.adobe.com/fr/create/color-accessibility) : Pour vérifier la lisibilité des couleurs.
* [Contrast Checker par WebAIM](https://webaim.org/resources/contrastchecker/) : Simple et efficace.

### Documentation technique
* [MDN Web Docs - Accessibility](https://developer.mozilla.org/fr/docs/Web/Accessibility) : La bible du HTML sémantique.
* [WAI-ARIA Authoring Practices](https://www.w3.org/WAI/ARIA/apg/patterns/) : Pour savoir quand et comment utiliser ARIA (et quand ne pas l'utiliser).
