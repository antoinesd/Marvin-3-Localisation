Introduction
---------------

To localise Marvin into your own language, you will have to translate one string table (called "Localizable.strings") and eleven HTML files - these HTML files are quite straightforward and are Marvin's in-app help. The string table contains several hundreds of strings, so the process is rather involving. If you still want to go ahead, please have a look at the following notes...


Important Notes
---------------

* Before starting a translation, please contact me at kris (at) appstafarian.com just in case someone else is already working on it.

* Please base ALL translations on the "en-us" version. Do NOT translate files that have already been translated (e.g. from "fr-fr" to "de-de"). Meaning *will* get lost doing that.

* This localisation process covers every single possible message, screen, and menu in Marvin. You should be deeply familiar with Marvin and its behaviour to understand each message and how it translates.

* If you want to change anything in an existing translation, do your best to discuss with the orignal translator.

* Do NOT translate or delete comments ("/\* ... \*/" and "// ..."). I need them to get around.

* You can add comments (see previous point) in between entries, e.g. to see the original English version.

* If you find an error, please send a pull request or something similar.

* If you have any questions concerning the original English strings, get in touch. 

* If you make "non-standard" stylistic choices when translating, please annotate them in commit messages.

* Let me know if you think you found a mistake in the original English translation.

* "Marvin" is a proper name and shouldn’t be translated.

* "Deep View" is a proper name and shouldn’t be translated.

* Please do your absolute best to try and keep the length of strings as equal as possible to their English counterparts. This is important. I don't mind abbreviations that make sense.

* Please leave file names and encoding alone.

* Please keep the layout of the string files intact.

* Be on the lookout for parameters such as %i, %lu, %@, etc... in string constants. Strings that have parameters usually have a trailing comment explaining what they are.

* Be on the lookout for HTML elements in string constants. Please don't break them.

* Don’t remove the semicolons at the end of each line in string files. They're syntactical elements.

* Use sentence case for messages and titles - capitalise the first word but avoid capitalising the remaining ones unless you have to.

* Feel free to contact me at kris (at) appstafarian.com if you need help.

Thanks for helping!