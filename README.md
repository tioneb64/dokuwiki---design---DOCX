# DOCX Design

Thème (template) DokuWiki (`docx`).

Thème DokuWiki aligné sur les **documents Word** (DAT) et sur le snippet Obsidian `docx-design` : mise en page sobre, titres et tableaux comme dans les documents. Dérivé du thème par défaut de DokuWiki.

## Installation

Copier le contenu de ce dépôt dans `lib/tpl/docx/` (le fichier `template.info.txt` doit se trouver à la racine de ce dossier), puis vider le cache en rendant la date de `conf/local.php` plus récente (`touch conf/local.php`).

Puis l'activer : *Administration → Paramètres de configuration → Modèle*, ou `$conf['template'] = 'docx';` dans `conf/local.php`.

## Licence

Aucune licence n'a encore été choisie : à ajouter (fichier `LICENSE`) avant de publier le dépôt. DokuWiki est sous GPL-2.0.
