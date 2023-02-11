# CiviVersafix

Une version (alpha) totalement traduite en français et basé sur le modele le plus récent de Versafix-1 de Mosaico pour CiviCRM

**Info : La largeur de ce modèle est de 700px !**

La compatibilité doit être meilleure mais il faut la tester avant d'utiliser ça en production (c'est votre responsabilité) !

## Davantage de blocs et d'options !

Il y a de nouveaux blocs et de nouvelles options :
- utiliser une nouvelle police (Open Sans),
- réduire ou augmenter les marges générales et entre les blocs, entre les lignes (sur le stype principal et sur plusieurs blocs mais pas tous),
- modifier la taille des images un peu plus finement
- modifier les paramètres des boutons.

Si vous avez des idées d'améliorations, il y a encore des paramètres configurables, contribuez ou écrivez une issue, merci.

## Les blocs

Sur la base de Mosaico Versafix-1 template 0.18.9 et du travail de @homotechsual entre autres :

1. Bloc de texte centré (testé sur Outlook et Gmail)

![Centered Text Block](edres/centeredTextBlock.png?raw=true "Centered Text Block")

2. Bloc Multi Boutons Multi Button Block (personnalisation possible par ligne / par button)

![Multi Button Block](edres/multiButtonBlock.png?raw=true "Multi Button Block")

3. Un bloc d'icônes des Réseaux Sociaux seulement (personnalisable)

![Social Block](edres/socialBlock.png?raw=true "Social Block")

4. Un bloc qui permet d'afficher un texte avec une image en dessous ou au dessus + un bouton (le tout, paramétrable)

![Single Article Block](edres/singleArticleBlock.png?raw=true "Single Article Block")

5. Bloc 3 images

![Triple Image Block](edres/tripleImageBlock.png?raw=true "Triple Image Block")

6. Bloc 2 images

![Double Text Block](edres/doubleTextBlock.png?raw=true "Double Text Block")

7. Nouveau Titre de Section (avec possibilité d'agrandire / réduire les marges)

...

## Installation

Ceci n'est pas une extension Civi comme les autres. Il ne faut pas l'installer dans civicrm/ext.

1. Télécharger et extraire ou Git Clone vers un dossier nommé `CiviVersafix`
2. Placer ce dossier dans le dossier `mosaico_tpl` (cela doit donner au final `/files/civicrm/mosaico_tpl/CiviVersafix`).
3. **Important:** Le dossier DOIT être nommé `CiviVersafix` si vous changez le nom du dossier, assurez vous que le nom du fichier html soit aussi nommé comme ceci  `template-NOMDUNOUVEAUDOSSIER.html`.

**CiviCRM Files Directory:**

- **Drupal** sites/default/files/civicrm

- **Wordpress** wp-content/uploads/civicrm

## En quelques mots

Ce travail est base sur la version 0.18.9 de mosaico https://github.com/voidlabs/mosaico/releases/tag/v0.18.9

C'est un fork en français de https://lab.civicrm.org/homotechsual/CiviVersafix qui est elle même un fork de  Mosaico Versafix-1 template.

La première traduction du modèle en français a d'abord été établie par https://github.com/allinappli/ et l'aide de @bgm est toujours précieuse.

Merci à chacune et chacun !

Vous pouvez cloner ce fork en français depuis :

* https://github.com/MAKOA-France/CiviVersafix-FR

## TODO

* Faire davantage de tests d'envoi / compatibilité avant d'utiliser en production s'il vous plait !
* Corriger le bug js sur data-ko-height="imageHeight" quand on ajoute les nouveaux blocs de Reseaux Sociaux, dommage car à part ce bug ils sont prêts !
* Des images en français ?
* Rendre plus compatible certains blocs (SingleArticle et MultiButton...)
* Améliorer les blocs de 3 images ou 3 articles
* Afficher du contenu de Civi ou du CMS est possible mais ce sera l'objet d'autres extensions.

3 blocs ont été déplacés dans tmp/unused_mosaico_ready_blocks.html :
- footerBlock
- titleBlock (version du bloc de titre dans l'ancienne version du modele Versafix)
- HRBlock (version du bloc de ligne de séparation dans l'ancienne version du modele Versafix)
Si pour des raisons de compatibilité vous en avez besoin il faudrait les remettre dans template-CiviVersafix.html

Des blocs prêts mais qui générent des bugs pour l'instant sont ici : "/tmp/template-versafix-1-draft-already-adapted-mosaico.html"

## Assistance et Maintenance

**Note:** Le depot officiel de cette extension est https://lab.civicrm.org/homotechsual/CiviVersafix - c'est là que les problemes/issues devraient être soumis en priorité.

Cette extension est maintenue avec l'aide de la communauté CiviCRM www.civicrm.org par :

Makoa - www.makoa.fr

Nous proposons de l'assistance et du développement spécifique facturés.
Si vous rencontrez un problème vous pouvez aussi nous faire une demande d'analyse (facturée 2 heures minimum) via https://support.makoa.fr.
