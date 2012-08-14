SHARISM.ORG
===========

This repository contains the text and layout for [Sharism.org](http://sharism.org) and is compiled using [Jekyll](https://github.com/mojombo/jekyll/).

Translations
------------

We would love your help to make Sharism.org available in more languages. For now we are concentrating on translating the home page for greater accessibility.

### Get the code

If you can use git, you can clone this repository. If you are unfamiliar with git, use the Downloads link.

### Translate the home page

Look in the <code>_includes</code> folder, and make copies of <code>home.html</code> and <code>footer.html</code>. Rename the files to include your two-letter language code. For example, the Chinese versions will be called <code>home-zh.html</code> and <code>footer-zh.html</code>.

Open up these your new <code>home-**.html</code> and translate it into your language. Open up <code>footer-**.html</code> and translate it into your language.

Copy the folder <code>zh</code> to a new folder with the name of your language code. For example, the French translation should be in a folder called <code>fr/</code>.

Open up the new folder for your language and edit the file <code>index.html</code>. Change the include links which read <code>{% include home-zh.html %}</code> and <code>{% include footer-zh.html %}</code> to point to your language versions instead. Save your changes to the file.

You should also edit the other footer pages in the <code>_includes</code> directory and make them link to your new language.

### Send your translation

Finally, email your changes, send a patch, or put in a pull request.
