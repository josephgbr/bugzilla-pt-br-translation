bugzilla-pt-br-translation
==========================

Brazilian Portuguese translation for Bugzilla

## Translation process

1- Create diff from german to english template files

2- Replace "+++ en/" with "+++ pt-BR/"

3- TRANSLATE

4- Replace accents and special characters using correspondent HTML code, listed http://www.lsi.usp.br/~help/html/iso.html, otherwise garbage charactere will be displayed.

5- Apply the diff file in the respective bugzilla version to have a translated instance of Bugzilla

## Some links

Bugzilla's Old Localizer Guide - http://www.bugzilla.org/docs/localizer.html
Bugzilla's New Localizer Guide - https://wiki.mozilla.org/Bugzilla:L10n:Guide


## FAQ

### What is bugzilla-pt-br-translation?

It is a task force to translate Bugzilla to Brazilian Portuguese language. Here you can seem what is going on with this task and also send/suggest translations.

### How can I help?

You can send merge requests via github, or you can send patches, or you can send translated files.

Alternatively, you can file an issue in Github.

### How the translation is being done?

I couldn't find a easy way (e.g. gettext), so here is how I'm doing: German team has done a great job so far translating Bugzilla. A diff between German (de) and English (en) files from same version will display in which lines and files the German team translated. Knowing the lines that should be translated, eases a little bit the translation task.
