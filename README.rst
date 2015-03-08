########################
Translations for GeeCart
########################

This project contains translations for the GeeCart 
application messages folder, **application/language/english**.

Copy the folder(s) for the idioms you are interested in,
from inside the **language** folder of this project to your 
**application/language** folder.

You may then use the CodeIgniter Language class to reference the translations
directly, or you can set the default language in **application/config/config**
to the idiom appropriate for your webapp.

There have been several questions about RTL languages, but that is not
something addressed in CodeIgniter. The suggested approach is to keep any
translations in left-to-right order, and to deal with right-to-left
rendering through the "dir" attribute of an HTML element, or the "direction"
attribute in CSS.

************
Requirements
************

These translations are intended for use with GeeCart.

*******
License
*******

These translations are licensed under the `MIT license <license.txt>`_.

**********************
Repository Information
**********************

Each language is maintained by a community member, per the table below:

=======================  ===========  ==============  =========================
Idiom                    Status       User            Maintainer
=======================  ===========  ==============  =========================
italian                  1.0  ( 10%)  geekita         Danilo Migliarino
=======================  ===========  ==============  =========================

If you have a translation or correction, please fork the repository, clone it
locally, and then create a new branch (from develop) 
for each set of related changes or for
a complete language pack. Once your branch is complete, *then* create a pull 
request to merge it into the main repository. Remember to "sign" your commits.

Pull requests to the repository will only be considered if they come from 
the maintainer for any translations in the request, or if the maintainer
adds a comment indicating they approve of any changes.

If you would like provide a translation, please send me an email, with
your name, github account, and a brief explanation of your suitability.

`Danilo Migliarino <d.migliarino@geekita.com>`_
