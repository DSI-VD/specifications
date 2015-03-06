# Cahier des charges technique

Les différents livrables, outils et principes d'architecture demandés dans le cadre d'un développement web pour l'État de Vaud vous sont présentés ci-après.

## PatternLab

Le design (HTML, CSS, JS) doit être présenté sous la forme d'un [pattern lab](http://patternlab.io/).  
Cela permet de visualiser le comportement du site et des différents modules qui le compose.

Une architecture du site selon le principe de l'[Atomic Design]() est conseillé.

## Accessibilité

Selon la directive *[OHand](http://www.admin.ch/opc/fr/classified-compilation/20031813/index.html#a10)*, les prestations offertent doivent être accessibles à tout un chacun.

> L'information et les prestations de communication ou de transaction proposées sur Internet doivent être accessibles aux personnes handicapées de la parole, de l'ouïe, de la vue ou handicapées moteur. A cet effet, les sites doivent être aménagés conformément aux standards informatiques internationaux, notamment aux directives régissant l'accessibilité des pages Internet, édictées par le Consortium World Wide Web (W3C) et, subsidiairement, aux standards nationaux.  
> — [OHand art. 10](http://www.admin.ch/opc/fr/classified-compilation/20031813/index.html#a10)

De ce fait, nous demandons de répondre aux exigences [WCAG 2.0 level AA](http://www.w3.org/TR/WCAG20/).

## HTML

Le code HTML doit être validé et ne présenter aucune erreur lors de [le validateur du W3C](http://validator.w3.org).

## CSS

Les CSS ne doivent présenter aucune erreur.

### Architecture

L'architecture des feuilles de style doit éviter d'être trop spécifique et être modulable. Elles doivent être développé selon le principe d'architecture [ITCSS](http://itcss.io)
Cela a comme effet de faciliter leur maintenance.

### Framework

Des framework CSS comme [Bootstrap](http://getbootstrap.com) peuvent être utilisé même si **une CSS dédiée est préférable**.
Il est cependant demandé de désactiver tous les composants qui ne sont pas nécessaires.

### Preprocesseur

Favoriser l'utilisation de [SASS](http://sass-lang.com) plutôt que [less](http://www.lesscss.org).

### Styleguide

Les feuilles de style doivent être documentées et commentées.
Il est demandé d'utiliser un système de génération automatique de styleguide sur la base des commentaire dans les CSS ("living styleguide").

Quelques exemple d'outils de génération de styleguide:
- [Hologram](http://trulia.github.io/hologram/)
- [KSS](http://warpspire.com/kss/)

## JavaScript

Le code Javascript ne doit présenter aucune erreur.


## Web package manager

Privilégié [Bower](http://bower.io/) si l'utilisation d'un gestionnaire de packets web est nécéssaire.

## Taskrunner

[Grunt](http://gruntjs.com/) a notre préférence.

---

## Questions

Si vous avez des questions, n'hésitez pas à nous contactez en [ouvrant un cas](https://github.com/vdch/specifications/issues/new).