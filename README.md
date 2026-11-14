<p align="center">
  <img
    src="https://lottie.host/cdb5e749-f393-4333-ad23-8200f121e8d3/Z4sIS9xKDC.svg?v=1"
    alt="dotLottie Animation"
    width="550"
  />
</p>

# Compétence en design de mouvement

Principes universels de design de mouvement pour les agents IA. Basé sur la philosophie, agnostique à l'implémentation.

Apprend aux agents à penser comme des directeurs de mouvement — choisir le bon timing, l'easing, la chorégraphie et l'intention émotionnelle avant d'écrire une seule ligne de code d'animation. Fonctionne avec n'importe quel système d'animation.

## Installer

```bash
npx skills add LottieFiles/motion-design-skill
```

Prend en charge [40+ agents](https://skills.sh) dont Claude Code, Cursor, Codex, GitHub Copilot et bien d'autres.

## Ce que contient

**Core** (`SKILL.md`) — Référence rapide avec la checklist en 8 étapes, les archétypes de personnalité de mouvement, les tableaux de durée et d'easing, le guide de sélection des propriétés, les patterns courants et les règles de qualité.

**Philosophie** (`director/`) — Approfondissements sur les trois piliers, les 12 principes de Disney adaptés à l'UI, la cartographie émotion → mouvement, la chorégraphie, la structure narrative et l'adaptation au contexte.

**Patterns** (`patterns/`) — Recettes prêtes à l'emploi pour les animations d'entrée/sortie, les retours d'état (succès, erreur, chargement, survol), les mouvements ambiants/continus et la chorégraphie multi-éléments.

**Reference** (`reference/`) — Tables de référence pour les timings et easing, guide de sélection des propriétés, checklist qualité et dépannage des problèmes d'animation courants.

## Quand elle s'active

La compétence s'active lorsque vous travaillez sur :

- Animations UI (boutons, cartes, modales, transitions de page)
- Micro-interactions et animations de feedback
- États de chargement, succès ou erreur
- Animations déclenchées par le scroll ou basées sur la progression
- Établissement d'une identité de mouvement de marque
- Chorégraphie et séquençage multi-éléments

## Exemples de prompts

```
Ajoute une animation d'entrée ludique à ces composants de carte
```

```
Crée une transition chargement → succès → erreur pour ce bouton de soumission de formulaire
```

```
Chorégraphie la séquence d'entrée de ce tableau de bord — premier le graphique principal, puis les cartes de statistiques, puis la barre latérale
```

```
Passe en revue mon code d'animation et suggère des améliorations selon les principes du design de mouvement
```

## Structure de la compétence

```
skills/motion-design/
├── SKILL.md                          # Instructions principales de la compétence (< 500 lignes)
├── director/
│   ├── core-philosophy.md            # Analyse des trois piliers
│   ├── decision-framework.md         # Pipeline complet de décision
│   ├── disney-principles.md          # 12 principes, adaptés à l'UI
│   ├── motion-personality.md         # 4 archétypes + identité de marque
│   ├── emotion-mapping.md            # Traduction émotion → mouvement
│   ├── choreography.md              # Coordination multi-éléments
│   ├── narrative-structure.md       # Cadre micro-story
│   └── context-adaptation.md         # Plateforme, accessibilité, performance
├── patterns/
│   ├── entrance-exit.md              # Recettes d'entrée/sortie
│   ├── state-feedback.md             # Succès, erreur, chargement, survol
│   ├── ambient-continuous.md         # Boucles, respiration, parallaxe
│   └── multi-element.md               # Recettes de stagger + chorégraphie
└── reference/
    ├── timing-easing-tables.md       # Tables de durée + easing
    ├── property-selection.md         # Guide de communication des propriétés
    ├── quality-checklist.md          # Critères d'évaluation
    └── troubleshooting.md            # Maux d'animation + corrections
```

## Licence

MIT
