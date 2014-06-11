This file is part of Moodle - http://moodle.org/

Moodle is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Moodle is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with Moodle.  If not, see <http://www.gnu.org/licenses/>.

copyright 2014 Lancaster University (http://www.lancaster.ac.uk/)
license   http://www.gnu.org/copyleft/gpl.html GNU GPL v3 or later


TinyMCE wordcount plugin for Moodle
===================================

A Moodle sub-plugin to override the word counting rules in the standard TinyMCE
wordcount plugin to make them consistent with Moodle's own word count function.


Installation
------------

Installing from the Git repository (recommended if you installed Moodle from
Git):

Follow the instructions at
http://docs.moodle.org/27/en/Git_for_Administrators#Installing_a_contributed_extension_from_its_Git_repository,
e.g.
$ cd /path/to/your/moodle/
$ cd lib/editor/tinymce/plugins/
$ git clone https://github.com/tonyjbutler/moodle-tinymce_wordcount.git
  wordcount
$ cd /path/to/your/moodle/
$ echo /lib/editor/tinymce/plugins/wordcount/ >> .git/info/exclude


Installing from a zip archive downloaded from
https://moodle.org/plugins/pluginversions.php?plugin=tinymce_wordcount:

1. Download and unzip the appropriate release for your version of Moodle.
2. Place the extracted "wordcount" folder in your
   "/lib/editor/tinymce/plugins/" subdirectory.

Whichever method you use to get the plugin code in place, the final step is to
visit your Site Administration > Notifications page in a browser to invoke the
installation script and make the necessary database changes.


Updating Moodle
---------------

If you installed Moodle and the TinyMCE wordcount plugin from Git you can run
the following commands to update both (see
http://docs.moodle.org/27/en/Git_for_Administrators#Installing_a_contributed_extension_from_its_Git_repository):
$ cd /path/to/your/moodle/
$ git pull
$ cd lib/editor/tinymce/plugins/wordcount/
$ git pull

If you installed from a zip archive you will need to repeat the installation
procedure using the appropriate zip file downloaded from
https://moodle.org/plugins/pluginversions.php?plugin=tinymce_wordcount for your
new Moodle version.
