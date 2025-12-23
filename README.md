# WLHorizon - Plateforme Multi-Sorties

Site de présentation de la plateforme WLHorizon, qui génère une application mobile client, un outil métier et un site vitrine à partir d'un seul système.

## Description

WLHorizon est une plateforme unique qui permet à un commerce de disposer, à partir d'un même moteur :

1. **Application mobile client** - Publiée sur les stores (commande, compte client, fidélité)
2. **Application métier** - Pour le commerce (admin, gestion)
3. **Site vitrine** - Pour le SEO et la présentation

Ces trois sorties utilisent la même base de données, les mêmes modules et la même configuration, mais avec des rendus différents.

## Caractéristiques du Site

### Architecture
- **Plateforme unique** : Une source de vérité pour toutes les sorties
- **Modules réutilisables** : Activation/désactivation selon les besoins
- **Configuration centralisée** : Une modification impacte toutes les sorties

### Fonctionnalités Présentées
- Vue d'ensemble de l'architecture plateforme
- Détails des trois sorties générées
- Démonstration interactive de la modularité
- Exemples de personnalisation white-label

### Technologies
- HTML5
- CSS3 (avec variables CSS)
- JavaScript vanilla (sans dépendances)

## Utilisation

Ouvrez simplement `index.html` dans un navigateur moderne pour voir le site.

```bash
# Avec un serveur local (optionnel)
python3 -m http.server 8000
# ou
npx serve
```

Puis accédez à `http://localhost:8000`

## Structure du Projet

```
/
├── index.html      # Page principale du site
├── styles.css      # Styles et mise en page
├── script.js       # Interactivité (module toggles, smooth scroll)
└── README.md       # Documentation
```

## Principes de Conception

1. **Fidélité au produit réel** : Aucune fonctionnalité inventée
2. **Clarté** : Explication sans ambiguïté du système
3. **Démonstration visuelle** : Schémas et exemples concrets
4. **Pas d'UI fictive** : Représentations conceptuelles uniquement
5. **Modularité visible** : Impact immédiat des changements de configuration