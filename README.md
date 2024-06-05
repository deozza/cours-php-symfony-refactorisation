# Symfony avancé - refactorisation

Bonjour et bienvenu pour ce cours sur la refactorisation. Vous y apprendrez :
 * ce qu'est la refactorisation
 * comment refactoriser pour augmenter la qualité du code

Pour aborder sereinement ce cours, vous devez savoir ce qu'est :
 * une variable
 * une fonction
 * une boucle et des conditions

Ce cours s'appuie sur des exemples en PHP et utilise le framework Symfony. Vous n'êtes pas obligé de maîtriser ces langages. Tous les concepts abordés sont applicables avec d'autres langages et outils.

## Table des matières

- [Symfony avancé - refactorisation](#symfony-avancé---refactorisation)
  - [Table des matières](#table-des-matières)
  - [Qu'est-ce que c'est](#quest-ce-que-cest)
  - [Pourquoi refactoriser](#pourquoi-refactoriser)
    - [Gagner en performance](#gagner-en-performance)
    - [Faire évoluer une fonctionnalité](#faire-évoluer-une-fonctionnalité)
    - [Gagner en lisibilité](#gagner-en-lisibilité)
  - [Quand refactoriser](#quand-refactoriser)
  - [Les prérequis](#les-prérequis)
  - [Les méthodes](#les-méthodes)
    - [Renommage de fonctions et de variables](#renommage-de-fonctions-et-de-variables)
    - [Fail fast](#fail-fast)
    - [Supprimer le code mort](#supprimer-le-code-mort)
    - [Extraire les fonctions](#extraire-les-fonctions)
    - [Supprimer les duplicatas](#supprimer-les-duplicatas)
    - [Meilleure utilisation du typage](#meilleure-utilisation-du-typage)
    - [Meilleure utilisation du framework](#meilleure-utilisation-du-framework)


## Qu'est-ce que c'est

Si on prend un exemple mathématiques, on peut se rapporter aux identités remarquables. Soit 

(a + b)^2 = a^2 + b^2 + 2ab

La partie à gauche du signe `=` vaut la même chose que la partie à droite. 

Passer de la partie gauche à la partie droite s'appelle `développer` : le but est de se rapprocher de la forme finale, la plus simiilaire possible au vrai résultat. Le problème étant que dans des équations plus complexes, cette forme est très peu compréhensible et difficilement manipulable. On a du mal à savoir d'où on part et encore moins vers quoi on tend.

Passer de la partie droite à la partie gauche s'appelle `factoriser` : le but est de ramener la forme vers quelque chose de plus reconnaissable, facilement lisible et compréhensible par tous. On sait vers quoi le résultat va correspondre.

La refactorisation en développement reprend ce concept. Le plus souvent, notre code ressemble à la partie développée de l'équation : c'est une implémentation naive, qui répond au besoin de la fonctionnalité le plus directement possible. 

> Refactoriser notre code revient à le modifier vers une forme plus lisible et reconnaissable, le tout sans perdre de fonctionnalité.


## Pourquoi refactoriser

On va choisir de refactoriser du code pour 3 raisons : 
 * gagner en performance
 * faire évoluer une fonctionnalité
 * gagner en lisibilité

### Gagner en performance

*Dans ce cours, nous n'aborderons pas la refactorisation pour gagner en performance. C'est une technique qui dépend d'indicateurs qui sont plus complexes et abstraits à mettre en place. De plus, les techniques pourraient davantage changer d'un langage à un autre. Enfin, avant de refactoriser son code pour gagner en performances, d'autres éléments sont à envisager (amélioration du réseau, des requêtes à la base de données, ...)*

### Faire évoluer une fonctionnalité

### Gagner en lisibilité

*Ce cours se concentrera sur cet aspect.*

## Quand refactoriser


## Les prérequis


## Les méthodes

### Renommage de fonctions et de variables

### Fail fast

### Supprimer le code mort

### Extraire les fonctions

### Supprimer les duplicatas

### Meilleure utilisation du typage

### Meilleure utilisation du framework

