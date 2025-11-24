# Structure des répertoires du projet

## Organisation générale

```
Mousse d agents/
├── README.md                    # Point d'entrée principal
├── INDEX.md                     # Index de navigation
├── STRUCTURE.md                 # Ce fichier - description de l'organisation
│
├── documentation/               # Documentation du modèle
│   ├── conceptuelle/           # Documents conceptuels fondamentaux
│   │   ├── synthèse_conceptuelle.md
│   │   ├── specification_ontologique.md
│   │   ├── lois_dynamiques.md
│   │   └── questions_ouvertes.md
│   │
│   ├── plan_construction.md    # Plan de développement par phases
│   │
│   └── technique/             # Documentation technique (à venir)
│       └── (équations, formalisations mathématiques)
│
├── archive/                    # Documents historiques et sources
│   ├── synthèse conceptuelle.txt
│   └── genese de la théorie des mousses.txt
│
├── references/                 # Références externes (à venir)
│   └── (articles, livres, ressources)
│
└── applications/               # Cas d'application du modèle (à venir)
    └── (exemples, validations, études de cas)
```

## Description des répertoires

### `/documentation/conceptuelle/`

Contient tous les documents conceptuels fondamentaux du modèle :

- **synthèse_conceptuelle.md** : Synthèse exhaustive du modèle (genèse, concepts, ambitions, limites)
- **specification_ontologique.md** : Définition rigoureuse des trois éléments (bulle, substrat, gaz)
- **lois_dynamiques.md** : Règles internes du système (stabilité, fusion, éclatement, formation)
- **questions_ouvertes.md** : Questions de recherche et choix conceptuels à faire

### `/documentation/`

Contient les documents de planification et méthodologie :

- **plan_construction.md** : Feuille de route par phases pour développer le modèle

### `/documentation/technique/` (à venir)

Sera utilisé pour la documentation technique lors des phases ultérieures :

- Équations mathématiques
- Formalisations
- Spécifications techniques
- Documentation de simulation (si applicable)

### `/archive/`

Contient les documents sources historiques :

- Fichiers texte originaux des échanges
- Versions antérieures de documents
- Matériaux de référence utilisés pour développer le modèle

### `/references/` (à venir)

Sera utilisé pour stocker :

- Articles scientifiques de référence
- Livres et ressources
- Liens vers travaux connexes
- Bibliographie

### `/applications/` (à venir)

Sera utilisé pour :

- Cas d'application du modèle
- Validations sur systèmes réels
- Études de cas
- Exemples pratiques

## Conventions de nommage

- **Fichiers Markdown** : `snake_case.md` (ex: `synthèse_conceptuelle.md`)
- **Fichiers texte** : `snake_case.txt` ou avec espaces si nécessaire
- **Répertoires** : `lowercase` (ex: `documentation`, `archive`)

## Navigation

- **Point d'entrée** : `README.md`
- **Index complet** : `INDEX.md`
- **Structure** : Ce fichier (`STRUCTURE.md`)

## Évolution de la structure

Cette structure est conçue pour évoluer avec le projet :

- **Phase 0** (actuelle) : Documentation conceptuelle → `/documentation/conceptuelle/`
- **Phase 1** : Formalisation mathématique → `/documentation/technique/`
- **Phase 3** : Applications → `/applications/`
- **Phase 4** : Extensions → Nouveaux répertoires selon besoins

---

*Structure mise à jour le 24/11/2025*

