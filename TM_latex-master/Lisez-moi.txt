TM_latex
========

Modèle de travail de maturité en latex pour le lycée.

À lire avant toute chose la documentation qui se trouve dans le répertoire documentation du présent modèle.

Pratiquement
============
Le modèle de travail de maturité se présente sous le forme d'un répertoire zippé. Il faut donc tout d'abord le décompresser et lire le fichier Lisez-moi.txt ou readme.md.

Puis, il faut tenter une première compilation du fichier main.tex pour détecter des erreurs dues à l'éventuelle absence de certains packages nécessaires et le cas échéant, il faut les installer et refaire la compilation jusqu'à ce qu'il n'y ait plus d'erreurs.

Alors seulement, le travail à proprement parlé peut commencer.

Compilation
===========
Pour compiler le document, il n'est théoriquement pas nécessaire de faire appel à un éditeur latex dédié. On peut tout faire à l'aide d'une bonne vieille console ou d'un simple éditeur de texte. Mais, il est évidemment plus pratique d'avoir recours à un éditeur dédié à LaTeX comme Texmaker.

Comme déjà dit, le document à compiler est main.tex. À la fin, il est aussi nécessaire de préparer cette compilation pour permettre aux bibliographies d'être correctement intégrées dans le document. Pour cela, il faut réaliser une première compilation, puis dans la console associée à Texmaker, exécuter successivement bibtex main et bibtex web. Cela permettra de créer les fichiers nécessaires pour les bibliographies. Enfin, il faut recompiler une ou deux fois le document principal.