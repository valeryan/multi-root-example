# multi-root-example

The purpose of this project is for testing the Php Sniffer & Beautifier extension in a multi-root workspace. Each root dir has a different setup and .phpcs.xml files to show that the extension will use the correct .phpcs.xml file for each project in a multi-root workspace.

## Examples

* [Root 1](root1/ReadMe.md): Composer.json and .phpcs.xml(PSR-2) in the root dir.
* [Root 2](root2/ReadMe.md): Composer.json and .phpcs.xml(PEAR) in the root dir and a .phpcs.xml(PSR-2) in the leaf dir.
* [Root 3](root3/ReadMe.md): No composer.json and .phpcs.xml(PSR-2) in the root dir. Needs global install of phpcs and phpcbf.
