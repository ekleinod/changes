# changes

Change markup for LaTeX.

The changes-package allows the user to manually markup changes of text, such as additions, deletions, or replacements.
Changed text is shown in a different colour; deleted text is striked out.
The package allows free defining of additional authors and their associated colour.
It also allows you to change the markup of changes, authors, or annotations.

Das changes-Paket dient zur manuellen Markierung von geändertem Text, insbesondere Einfügungen, Löschungen und Ersetzungen.
Der geänderte Text wird farbig markiert und, bei gelöschtem Text, durchgestrichen.
Das Paket ermöglicht die freie Definition von Autoren und deren zugeordneten Farben.
Es erlaubt zusätzlich die Änderung des Änderungs-, Autor- und Anmerkungsmarkups.

Internet: http://ekkart.de/computer/latex/pakete.html (German)

Lizenz: LaTeX Project Public License (LPPL), siehe Datei LICENSE.
License: LaTeX Project Public License (LPPL), see file LICENSE.

## Nutzung

- ausführliches Nutzerhandbuch (aktuelles Release): <https://github.com/ekleinod/changes/blob/master/texmf/doc/latex/changes/changes.ngerman.pdf>

## Usage

- extensive user manual (current release): <https://github.com/ekleinod/changes/blob/master/texmf/doc/latex/changes/changes.english.pdf>

## Git-Repository

Short information about the structure of the git repository:

The branches are constructed regarding the git branching model of http://nvie.com/posts/a-successful-git-branching-model/

This means, there are always at least three branches:

1. `master` - contains released versions
2. `develop` - main synchronisation branch for feature, release, and hotfix branches
3. `feature/work` - main working branch for development

Additionally, the following branches may occur:

- `feature/*` - writing a special feature
- `release/*` - synchronizing release versions between `develop` and `master`
- `hotfix/*` - fast bugfixes

## Legal stuff

### Licenses

License: LaTeX Project Public License (LPPL), see file LICENSE.

### Copyright

%% README.md
%% Copyright 2007-2017 Ekkart Kleinod <ekleinod@edgesoft.de>
%
% This work may be distributed and/or modified under the
% conditions of the LaTeX Project Public License, either version 1.3
% of this license or (at your option) any later version.
% The latest version of this license is in
%   http://www.latex-project.org/lppl.txt
% and version 1.3 or later is part of all distributions of LaTeX
% version 2005/12/01 or later.
%
% This work has the LPPL maintenance status `maintained'.
%
% The Current Maintainer of this work is Ekkart Kleinod.
%
% This work consists of the files
%
% source/latex/changes/changes.drv
% source/latex/changes/changes.dtx
% source/latex/changes/changes.ins
% source/latex/changes/examples.dtx
% source/latex/changes/README
% source/latex/changes/userdoc/*.tex
%
% scripts/changes/delcmdchanges.bash
%
% and the derived files
%
% doc/latex/changes/changes.english.pdf
% doc/latex/changes/changes.english.withcode.pdf
% doc/latex/changes/changes.ngerman.pdf
%
% doc/latex/changes/examples/changes.example.*.tex
% doc/latex/changes/examples/changes.example.*.pdf
%
% tex/latex/changes/changes.sty
