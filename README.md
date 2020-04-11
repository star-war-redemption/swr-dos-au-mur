# Dos Au Muur - Campagne Star Wars Redemption

## Synopsys
Cette campagne est écrite initialement pour [Star Wars Redemption](https://swr.ght1pc9kc.fr/categories/livre-de-base/) mais un scénar reste un scénar et il est jouable dans n’importe quel univers de Star Wars.

L’idée était de faire une campagne d’introduction avec des personnages partant de rien. Les joueurs commencent Novice et n’ont pas besoin d’historique complexe et élaboré (bien que cela ne soit pas interdit bien sûr). De cette façon, les personnages devraient être assez vite fait. Et elle est adaptable aussi bien avec des joueurs orienté Alliance Rebelle que Empire. Dans les deux cas, l’objectif sera le même mais les dessains changeront.

La campagne se déroule dans les premières années de l’avènement de l’Empire, au MJ de voir s’il veut préciser.

La trame de la campagne se base sur un très ancien artéfact Sith, le [Talisman de Muur](http://www.starwars-holonet.com/encyclopedie/technologie-talisman-muur.html). Un artéfact créé par Karness Muur, un Sith se servant de la Force pour prolonger sa vie. L’artéfact contient l’âme de Muur, celui qui le porte est possédé par Karness et peut contrôler les Rakghoules.

On trouve beaucoup d’informations sur cet artéfact sur HoloNet et je me suis grandement inspiré de ces informations pour cette campagne en faisant vivre à mes héros les aventures des divers individus qui ont croisé le Talisman\ldots


## License
![image](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-1.png)

## Contributions

### Pré-requis LaTeX
Avant toutes chose, il faut installer XeLaTeX et quelques dépendances pour pouvoir compiler :

```
# apt install --no-install-recommends gv texlive-base texlive-bibtex-extra texlive-extra-utils texlive-font-utils texlive-fonts-recommended texlive-lang-french texlive-latex-extra texlive-latex-recommended texlive-pictures texlive-xetex latexmk lmodern biber 
```

### Clone
Le projet utilise un sous-module pour importer le style.

```
git clone --recursive https://github.com/star-war-redemption/swr-dos-au-mur.git
```

### Build

```
latexmk -f -r swr-class/latexmkrc 
```
