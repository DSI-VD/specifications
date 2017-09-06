# Cahier des charges technique

Les différents livrables, outils et principes d'architecture demandés dans le cadre d'un développement web pour l'État de Vaud vous sont présentés ci-après.

## PatternLab

Le design (HTML, CSS, JS) doit être présenté sous la forme d'un [pattern lab](http://patternlab.io/).
Cela permet de visualiser le comportement du site et des différents modules qui le compose.

Une architecture du site selon le principe de l'[Atomic Design](http://bradfrost.com/blog/post/atomic-web-design/) est conseillé.

## Navigateurs

Les navigateurs à supporter selon [browserlist](https://github.com/ai/browserslist) sont les suivants:

- `last 2 versions` : the last 2 versions for each major browser.
- `> 5% in CH`: uses CH usage statistics.
- `IE >= 8`: Internet Explorer 8
- `Firefox >= 31`: Firefox 31
- `Firefox ESR`: the latest [Firefox ESR](https://www.mozilla.org/en-US/firefox/organizations/faq/) version.

## Accessibilité

les prestations offertes par l'administration cantonale sont soumises l'[Ordonnance sur l'égalité pour les handicapés(OHand)](http://www.admin.ch/opc/fr/classified-compilation/20031813/index.html).

> L'information et les prestations de communication ou de transaction proposées sur Internet doivent être accessibles aux personnes handicapées de la parole, de l'ouïe, de la vue ou handicapées moteur. A cet effet, les sites doivent être aménagés conformément aux standards informatiques internationaux, notamment aux directives régissant l'accessibilité des pages Internet, édictées par le Consortium World Wide Web (W3C) et, subsidiairement, aux standards nationaux.
> — [OHand art. 10](http://www.admin.ch/opc/fr/classified-compilation/20031813/index.html#a10)

De ce fait, les développements doivent répondre aux exigences **[WCAG 2.0 level AA](http://www.w3.org/TR/WCAG20/)**.

## HTML

Le code HTML doit être validé et ne présenter aucune erreur lors de [le validateur du W3C](http://validator.w3.org).

## CSS

Les CSS ne doivent présenter aucune erreur.

### Architecture

L'architecture des feuilles de style doit éviter d'être trop spécifique et être modulable. Elles doivent être développées selon le principe d'architecture [ITCSS](http://itcss.io)
Cela a comme effet de faciliter leur maintenance.

### Framework

Des framework CSS comme [Bootstrap](http://getbootstrap.com) peuvent être utilisés même si **une CSS dédiée est préférable**.
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

Privilégier [Bower](http://bower.io/) si l'utilisation d'un gestionnaire de packets web est nécessaire.

## Taskrunner

[Grunt](http://gruntjs.com/) a notre préférence.

## CMS TYPO3

A titre d'information, [TYPO3](http://typo3.org/) est le <abbr title="Content Management System">CMS</abbr> utilisé à l'Etat de Vaud.

## Open Source

L'Etat de Vaud, se réserve le droit de rendre Open Source les travaux effectués. Merci de développer dans ce sens et de ne pas utiliser de matériel sujet à copyright.

---

## Questions

Si vous avez des questions, n'hésitez pas à nous contacter en [ouvrant un cas](https://github.com/vdch/specifications/issues/new).
