rBiblia for Windows locales
===========================

![linter](https://github.com/rBiblia/rbiblia-windows-locales/actions/workflows/lint.yaml/badge.svg)

Localisation repository for the [rBiblia](https://rbiblia.toborek.info/en-US/) application.

All contributions are welcome.

Here you will find details on how to translate rBiblia's interface into your language.

Step-by-Step Instructions
-------------------------

* Start your work by forking this repository.
* Create a new branch for your work.
* Create a new folder using a language culture-specific name (e.g., `pl-PL`, `en-GB`, `fr-FR`, etc.).
* Copy all files included in the `en-GB` folder to your new location.
* Start your work by opening the `translation.xml` file in your favorite text editor (e.g., Notepad).
* Change (or add a new) name under the `<authors></authors>` tags. The name between the `<name></name>` tags will be shown in the About box of the Language settings window.
* Start translating strings stored between the `<value id="..." type="..."></value>` tags. Please do not change anything beyond this area, especially do not touch the `id` or `type` attributes.
* After your work is done, you can add a new commit with the proper name, for example, `[en-GB] added interface translation file` - all your commits should be preceded with the culture-specific ID stored between `[`square brackets`]`.
* Push your local branch to your fork and create a new Pull Request.

After a successful review of your Pull Request, your commits will be merged into the master branch of the upstream repository.

Only two files are required to translate rBiblia's interface: `translation.xml` and `aliases.xml`.

If you have any questions, please do not hesitate to contact the author of this repository.

You can drop me a line using the dedicated [contact form](https://kontakt.toborek.info) (please keep in mind that I can understand only Polish and English).

Please [support my work](https://rbiblia.toborek.info/donation/).

You can follow rBiblia on [Facebook](https://www.facebook.com/rBiblia) and [Telegram](https://t.me/rBiblia).
