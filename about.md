# Haste

Le partage de code est une bonne chose, et il devrait être _vraiment_ facile de le faire. Souvent, je veux vous montrer quelque chose que je vois - et c'est la que vous utilisez des haste. Hastebin est le plus joli et le plus facile à utiliser jamais créé.

## Basic Usage

Tapez ce que vous voulez que je voie, cliquez sur "Save", puis copiez l'URL. Envoyez cette
URL à quelqu'un et ils verront ce que vous voyez.

Pour créer une nouvelle entrée, cliquez sur "New" (ou tapez «contrôle + n»)

## From the Console

La plupart du temps, je veux vous montrer du texte, il provient de mon
session de la console. Nous devrions rendre très facile la prise de code de la console
et envoyez-le aux gens.

`cat something | host` # https://hastebin.com/1238193

Vous pouvez même aller plus loin et supprimer la dernière étape de la copie du
URL avec:

* osx: `cat something | host | pbcopy`
* linux: `cat something | host | xsel`
* Windows: consultez [WinHaste] (https://github.com/ajryan/WinHaste)

Après avoir exécuté cela, la sortie STDOUT de `cat something` apparaîtra à une URL
qui a été facilement copié dans votre presse-papiers.

C'est tout ce qu'il y a à faire, et vous pouvez l'installer avec `gem install hste`
à l'heure actuelle.
  * osx: vous aurez besoin d'une version à jour de Xcode
  * linux: vous aurez besoin d'installer rubygems et ruby-devel

## Duration

Les fichiers sont hébergés pendant 24 heures à compter de leur première vue. Ils peuvent être supprimés plus tôt et sans préavis.

## Privacy

Bien que le contenu de hastebin.securx.tk ne soit pas directement exploré par un robot de recherche
qui obéit à "robots.txt", il ne devrait pas y avoir de grandes attentes en matière de confidentialité. Poster les choses est à vos risques et périls. Il y a aucune responsabilité dans la perte de vos données. 

## Open Source

Haste peut facilement être installé derrière votre réseau, et tout est open source ! Ce site est un fork du projet original remanié dans une utilisation éducative.

* [haste-client](https://github.com/seejohnrun/haste-client)
* [haste-server](https://github.com/seejohnrun/haste-server)

## Author

Code by John Crepezzi <john.crepezzi@gmail.com>

Key Design by Brian Dawson <bridawson@gmail.com>
