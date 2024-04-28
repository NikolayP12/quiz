# SQLab question

## Instalation of the extension quiz plugin

This extension is designed to enhance the existing Quiz module in Moodle. Follow these steps to install the extension:
This plugin should replace the existing quiz plugin in your Moodle installation directory.

    {your/moodle/dirroot}/mod/quiz/

Due to this plugin does not modify the install.xml, it is not necessary to uninstall the original. It is as simple as replacing the folder and that's it. Once the folder has been replaced, the next step is to log in as administrator and purge the cache. To do this go to \_Site administration > \_Development > \_Purge caches and select the buttom "Purge all caches".

## License

2024 Nikolay <nikolaypn2002@gmail.com>

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.
If not, see <https://www.gnu.org/licenses/>.

## Purpose

In order to know the ID of the questionnaires, this extension has been developed to provide the teachers information about wich is this ID.
The ID can be found in the configuration section of the created quiz, under the field that contains the quiz name, the field can be found as "Quiz id".
This extension is necesary for the "SQLab" plugin.

## Configuration and Usage

Once the plugin is replaced, you can start creating a new questionnaire as you would do normally.

This ID is used by the "SQLab" plugin to find the questionnaire that contains the "sql questions". Therefore, once the questionnaire is created, is necessary to associate the "sql questions" from the question bank (or create them directly for the questionnaire) to the just created questionnaire.

The "SQLab" plugin can be find in this url:

    https://github.com/josefernandez02/sqlab.git

The "SQLquestion" plugin can be find in this url:

    https://github.com/NikolayP12/sqlquestion.git

## Support

For questions or issues regarding the Quiz extension, please send an email to the plugin maintainer at nikolaypn2002@gmail.com.
