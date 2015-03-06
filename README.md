# Cahier des charges technique

Les différents livrables, outils et principes d'architecture demandés dans le cadre d'un développement web pour l'État de Vaud vous sont présentés ci-après.

## PatternLab

Le design doit être présenté sous la forme d'un [pattern lab](http://patternlab.io/). 

## Accessibilité

Selon la directive *[OHand](http://www.admin.ch/opc/fr/classified-compilation/20031813/index.html#a10)*, les prestations offertent doivent être accessibles à tout un chacun.

De ce fait, nous demandons de répondre aux exigences [WCAG 2.0 level AA](http://www.w3.org/TR/WCAG20/).

## HTML

Le code HTML doit être validé et ne présenter aucune erreur dans [le validateur du W3C](http://validator.w3.org).

## CSS

### Architecture

L'architecture des feuilles de style doit éviter d'être trop spécifique et être modulable. Elles doivent être développées selon le principe d'architecture [ITCSS](http://itcss.io).
Cela a comme effet de faciliter leur maintenance.

### Frameworks

Des frameworks CSS comme [Bootstrap](http://getbootstrap.com) peuvent être utilisé même si **une CSS dédiée est préférable**.
Il est cependant demandé de désactiver tous les composants qui ne sont pas nécessaires.

### Préprocesseur

Favoriser l'utilisation de [SASS](http://sass-lang.com) plus tôt que [less](http://lesscss.org/).

### Styleguide

Les feuilles de style doivent être documentées et commentées.
Il est demandé d'utiliser un système de génération automatique de styleguide sur la base des commentaires dans les CSS ("living styleguide").

Quelques exemples d'outils de génération de styleguide:
- [Hologram](http://trulia.github.io/hologram/)
- [KSS](http://warpspire.com/kss/)