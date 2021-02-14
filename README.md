# Canevas LaTeX par Jerome
Un modèle LaTeX afin de principalement faire des devoirs et rapports de laboratoires mais aussi d'autres documents de nature scientifique comme des notes de cours par exemple.

### Remerciments
Un gros merci à Alexande Simoneau et David Sénéchal, desquels j'ai emprunté quelques fonctions mathématiques et de mise en page.

## Utilisation
Vous trouverez dans ce repertoire les fichier d'un exemple de ce que l'on peut accomplir avec ce canevas. `Demo.pdf` est même un exemple compilé. Si vous êtes déjà à l'aise avec les commandes et modules utilisé, vous pouvez utiliser les fichiers dans `Canevas.zip` directement. Le fichier principal dans ce dossier est relativement vide et permet de rapidement commencer un nouveau travail. Notez que dans cette version du travail, le code dans `special.sty` sont en commentaire. La raison est détaillée plus loin.

## Description des fichiers
`Demo.tex` - Le fichier principal compilé, il est utile de le renomer dans vos propres travaux pour facilement vous retrouver. Pour ce fichier spécifiquement, il s'agit d'un exemple de la majorité des fonctionalité de ce modèle.

`math_func.tex` - Ce fichier contient ce qui touche aux fonctions, symboles et mise en page mathématique et physique.

`mise_en_page.sty` - Ce fichier contient ce qui concerne la mise en page du document. Il y a aussi des fonction d'emphase pour divers sections.

`special.sty` - Ce fichier contient des modules permettant de produire des documents spécifiques, comme des diagrames de circuits par exemple. 

**Important: ** Le contenu de ce fichier peut ralentir le temps de compilation d'un document, il est donc préférable de garder les section inutilisées en commentaires. C'est la cas dans `Canevas.zip`. Aussi, certains diagrammes requierts le compilateur *LuaLaTeX*, qui peut facilement être choisi dans *Overleaf*.

`reference.sty` - Ce fichier contient des éléments spécifique à ma situation, donc des raccourcis pours les titres de cours, nom de professeurs et page titre.

`Demo.pdf` - Un exemple compilé de `Demo.tex`.

`Canevas.zip` Comme indiqué précedemment, les mêmes fichier que dans ce répertoire mais prêt à utiliser.

Les fichiers dans `Demo` sont spécifiques à la crétaion de `Demo.pdf`. Il ne sont pas nécessaires pour vos propres travaux.
