# Tulad
Moodle Plugin: Cheating Detection Tool
Tulad is a plugin created for Moodle meant to detect cheating in forum posts. This version of Tulad is a plagiarism plugin that displays two similarity indexes inside forum posts based on lexical and semantic standards relative to other forum posts inside that discussion. The similarity index for the lexical standard utilizes the Sorensen-Dice Coefficient and the semantic standard utilizes cosine similarity with Term Frequency - Inverse Document Frequency. A high similarity index might indicate traces of cheating. Please note of the keyword 'might' since both implementations are both crude and will not necessarily be always accurate.

# Installing via uploaded ZIP file

Log in to your Moodle site as an admin and go to Site administration >
Plugins > Install plugins.
Upload the ZIP file with the plugin code. You should only be prompted to add
extra details if your plugin type is not automatically detected.
Check the plugin validation report and finish the installation.


# Installing manually
The plugin can be also installed by putting the contents of this directory to

{your/moodle/dirroot}/blocks/tulad

Afterwards, log in to your Moodle site as an admin and go to Site administration >
Notifications to complete the installation.
Alternatively, you can run

$ php admin/cli/upgrade.php

to complete the installation from the command line.
