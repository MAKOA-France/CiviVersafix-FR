# CiviVersafix
Une version personnalisée du Modèle de Base Versafix-1 de Mosaico pour CiviCRM (traduit en français)

## En quelques mots

C'est un fork en français de https://lab.civicrm.org/homotechsual/CiviVersafix qui est elle même un fork de  Mosaico Versafix-1 template, et inclut des nouveaux blocs.

**Note:** Le depot officiel de cette extension est https://lab.civicrm.org/homotechsual/CiviVersafix - c'est là que les problemes/issues devraient être soumis.

Vous pouvez cloner cette extension en français depuis :

* https://github.com/MAKOA-France/CiviVersafix-FR

## Davantage de blocs !

We're happy to add blocks - assuming we can see a use-case for them! Open an issue to request a block - please provide as much indication as you can as to how the block should look and what, if any, configuration should be possible :-).

## Qu'est ce qui a changé ?

Adds the following new/changed blocks to the Mosaico Versafix-1 template:

1. Centered Text Block

![Centered Text Block](edres/centeredTextBlock.png?raw=true "Centered Text Block")

2. Multi Button Block (with per-row and per-button customisation in UI)

![Multi Button Block](edres/multiButtonBlock.png?raw=true "Multi Button Block")

3. Social Icon only Block (with customisation)

![Social Block](edres/socialBlock.png?raw=true "Social Block")

4. Customised Single Article block - allowing top or bottom image placement.

![Single Article Block](edres/singleArticleBlock.png?raw=true "Single Article Block")

5. Triple Image Block

![Triple Image Block](edres/tripleImageBlock.png?raw=true "Triple Image Block")

6. Double Text block

![Double Text Block](edres/doubleTextBlock.png?raw=true "Double Text Block")

## Installation

Ceci n'est pas une extension Civi comme les autres. Il ne faut pas l'installer dans civicrm/ext.

1. Télécharger et extraire ou Git Clone vers un dossier nommé `CiviVersafix`
2. Placer ce dossier dans le dossier `mosaico_tpl` (cela doit donner au final `/files/civicrm/mosaico_tpl/CiviVersafix`).
3. **Important:** Le dossier DOIT être nommé `CiviVersafix` si vous changez le nom du dossier, assurez vous que le nom du fichier html soit aussi nommé comme ceci  `template-NOMDUNOUVEAUDOSSIER.html`.

**CiviCRM Files Directory:**

**Drupal** sites/default/files/civicrm

**Wordpress** wp-content/uploads/civicrm
