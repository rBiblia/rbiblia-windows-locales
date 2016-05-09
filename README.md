rBiblia locales
===============

Localisation repository for [rBiblia](http://rbiblia.toborek.info) application.

All contributions are welcome.

Here you will find informations on how to translate rBiblia's interface into desired language.

Step by step instruction
------------------------

* start your work by forking this repository,
* create a new branch for your work,
* create a new folder using language culture specific name (eg. `pl-PL`, `en-GB`, `fr-FR` etc.),
* copy all files included in `en-GB` folder to your new location,
* start your work by opening `translation.xml` file in your favorite text editor (eg. Notepad),
* change (or add a new one) name under `<authors></authors>` tags. Name between `<name></name>` tags will be shown in the About box of the Language settings window,
* start translating strings stored between `<value id="..." type="..."></value>` tags. Please, do not change anything beyond this area, especially do not touch `id` or `type` attributes.
* after your work is done, you can add a new commit with the proper name, for example `[en-GB] added interface translation file` - all your commits should be preceded with culture specific id stored between `[`square brackets`]`,
* push your local branch to your fork and create a new Pull Request.

After successful review of your Pull Request your commits will be merged into master branch of the upstream repository.

Only two files are required to translate rBiblia's interface: `translation.xml` and `aliases.xml`.

If you have any questions, please do not hestitate to contact the author of this repository.

You can drop me a line using dedicated [contact form](http://toborek.info/kontakt/) (please keep in mind that I can understand only Polish or English language).