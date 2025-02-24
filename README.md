# Stussy Clone - Drupal Custom Theme

## Description
Ce projet est un clone du site e-commerce Stussy, développé avec Drupal et un thème personnalisé. Il reproduit les principales fonctionnalités et le design du site original, en se concentrant sur l'expérience utilisateur et l'interface visuelle.

## Fonctionnalités principales

- Navigation principale avec sous-menus dynamiques
- Pages produits avec galerie d'images et sélecteurs
- Système de grille responsive pour les produits
- Sections collapsibles pour les informations détaillées
- Conversion d'unités (pouces/cm) pour les tailles
- Système de navigation entre produits
- Prévisualisation des couleurs disponibles
- Interface de sélection des tailles

## Structure du thème

### Templates principaux
- `page--detail-page.html.twig`
- `page--new-arrivals.html.twig`
- `components/navigation/main-navigation.html.twig`

### Organisation des fichiers
```
custom_theme/
├── css/
│   ├── component/
│   ├── base/
│   ├── layout/
│   └── theme/
├── js/
├── images/
└── templates/
    ├── layout/
    ├── components/
    └── page/
```

## Installation

1. Cloner le repository
```bash
git clone [url-du-repo]
```

2. Installer les dépendances Drupal
```bash
composer install
```

3. Activer le thème
```bash
drush theme:enable custom_theme
drush config-set system.theme default custom_theme
```

4. Vider le cache
```bash
drush cache:rebuild
```

## Technologies utilisées

- Drupal 11
- HTML5/CSS3
- JavaScript vanilla
- Twig templating
- YAML pour la configuration

## Configuration requise

- PHP 8.0 ou supérieur
- Drupal 9.x ou 10.x
- Composer
- Node.js (pour la compilation des assets)

## Personnalisation

### Styles
Les styles peuvent être modifiés dans :
- Les fichiers CSS individuels dans `/css`
- Les templates Twig directement
- Le fichier de configuration du thème

### Templates
Les templates peuvent être surchargés en suivant la convention de nommage Drupal :
```
templates/[module]/[template-name].html.twig
```

## Développement

### Installation environnement de développement
```bash
npm install
npm run watch
```

### Compilation des assets
```bash
npm run build
```

## Bonnes pratiques

- Utilisation des commentaires pour le code complexe
- Structure modulaire des composants
- Respect des standards de codage Drupal
- Tests réguliers sur différents navigateurs

## Contribution

1. Fork le projet
2. Créer une branche (`git checkout -b feature/AmazingFeature`)
3. Commit les changements (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request


## Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE.md](LICENSE.md) pour plus de détails.

## Contact

Tristan Gerber - tristan.gerber@etu.unistra.fr

Lien du projet: [https://github.com/Tristan-stack/st-ssy-drupal](https://github.com/Tristan-stack/st-ssy-drupal)
