<p align="center">
  <img
    src="https://lottie.host/cdb5e749-f393-4333-ad23-8200f121e8d3/Z4sIS9xKDC.svg?v=1"
    alt="Animation dotLottie"
    width="550"
  />
</p>

# Compétence en design de mouvement

Des principes universels de design de mouvement pour les agents IA, centrés sur la philosophie et indépendants de l’implémentation.

Cette compétence apprend aux agents à penser comme des directeurs de mouvement : choisir le bon timing, l’easing, la chorégraphie et l’intention émotionnelle avant d’écrire le code d’animation. Elle s’applique aux interfaces et aux vidéos HTML produites avec [HyperFrames](https://github.com/heygen-com/hyperframes).

## Installation

### Installer cette compétence

```bash
npx skills add eliabdevweb-svg/motion-design-skill
```

Compatible avec [plus de 40 agents](https://skills.sh), dont Claude Code, Cursor, Codex, GitHub Copilot et d’autres.

### L’utiliser avec HyperFrames

Dans le dossier de votre projet vidéo HyperFrames, installez ou mettez à jour les compétences HyperFrames officielles :

```bash
npx hyperframes skills update
```

Cette commande installe l’ensemble de compétences de base HyperFrames correspondant à la version de la CLI. Vous pouvez aussi installer les compétences autonomes via le sélecteur interactif :

```bash
npx skills add heygen-com/hyperframes
```

Choisissez le groupe **Core Skills**. Installez ensuite la compétence de ce dépôt avec la commande ci-dessus, si elle n’est pas déjà disponible pour votre agent. Redémarrez ou rouvrez l’agent dans le dossier du projet après l’installation.

**Prérequis HyperFrames :** Node.js 22 ou ultérieur et FFmpeg pour le rendu local. Consultez la [documentation officielle](https://hyperframes.heygen.com/quickstart) pour les détails à jour.

### Démarrer un projet HyperFrames

```bash
npx hyperframes init ma-video
cd ma-video
npx hyperframes preview  # aperçu dans le navigateur
npx hyperframes render   # rendu MP4
```

Demandez à l’agent d’utiliser d’abord `/hyperframes` pour respecter le format du projet et le processus de production HyperFrames, puis de s’appuyer sur `motion-design` pour les décisions artistiques : par exemple, « Avec `/hyperframes`, crée une vidéo produit de 10 secondes. Utilise les principes de `motion-design` pour le rythme, l’easing et la chorégraphie. Prévisualise le résultat. »

> Les compétences HyperFrames fournissent le contrat technique et les étapes de production vidéo. `motion-design` les complète par des principes de mouvement ; elle ne remplace ni les instructions HyperFrames ni leur documentation.

## Contenu

**Core** (`SKILL.md`) — Référence rapide : checklist en 8 étapes, archétypes de personnalité du mouvement, tableaux de durée et d’easing, guide de sélection des propriétés, patterns courants et règles de qualité.

**Philosophie** (`director/`) — Les trois piliers, les 12 principes de Disney adaptés à l’UI, la traduction des émotions en mouvement, la chorégraphie, la structure narrative et l’adaptation au contexte.

**Patterns** (`patterns/`) — Recettes d’animations d’entrée et de sortie, de retours d’état (succès, erreur, chargement, survol), de mouvements d’ambiance et de chorégraphies multi-éléments.

**Références** (`reference/`) — Tables de timing et d’easing, guide de sélection des propriétés, checklist qualité, dépannage et guide d’application à HyperFrames.

## Quand l’utiliser

La compétence est utile pour :

- Les animations d’interface (boutons, cartes, modales, transitions de page)
- Les micro-interactions et les animations de feedback
- Les états de chargement, de succès ou d’erreur
- Les animations déclenchées par le défilement ou liées à une progression
- La création d’une identité de mouvement de marque
- La chorégraphie et le séquençage de plusieurs éléments
- Les titres, transitions, incrustations, visualisations de données et scènes de vidéos HyperFrames

## Exemples de prompts

```
Ajoute une animation d’entrée ludique à ces composants de carte.
```

```
Crée une transition chargement → succès → erreur pour ce bouton de formulaire.
```

```
Chorégraphie l’entrée de ce tableau de bord : d’abord le graphique principal, puis les cartes de statistiques, puis la barre latérale.
```

```
Dans ce projet HyperFrames, crée une séquence de titre de 10 secondes. Utilise les principes de motion-design et les compétences HyperFrames, puis prévisualise et rends la vidéo.
```

```
Passe en revue mon code d’animation et propose des améliorations fondées sur les principes du design de mouvement.
```

## Ressources HyperFrames

- [Dépôt officiel HyperFrames](https://github.com/heygen-com/hyperframes)
- [Guide de démarrage rapide](https://hyperframes.heygen.com/quickstart)
- [Documentation](https://hyperframes.heygen.com/introduction)
- [Exemples et showcase](https://hyperframes.heygen.com/examples)
- [Guides d’animation GSAP](https://hyperframes.heygen.com/guides/gsap-animation)
- [Catalogue de blocs et composants](https://hyperframes.heygen.com/catalog)
- [Référence de l’API Core](https://hyperframes.heygen.com/packages/core)
- [Studio HyperFrames](https://hyperframes.studio/studio)

## Structure de la compétence

```
skills/motion-design/
├── SKILL.md
├── director/
│   ├── core-philosophy.md
│   ├── decision-framework.md
│   ├── disney-principles.md
│   ├── motion-personality.md
│   ├── emotion-mapping.md
│   ├── choreography.md
│   ├── narrative-structure.md
│   └── context-adaptation.md
├── patterns/
│   ├── entrance-exit.md
│   ├── state-feedback.md
│   ├── ambient-continuous.md
│   └── multi-element.md
└── reference/
    ├── timing-easing-tables.md
    ├── property-selection.md
    ├── quality-checklist.md
    ├── troubleshooting.md
    └── hyperframes-workflow.md
```

## Licence

MIT
