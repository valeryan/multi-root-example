# Root 2 Example

This example is setup to show how two sets of standards can be applied. The php files in the src root dir are covered by the .phpcs.xml in the the top level. The leaf dir has a phpcs.xml file that is used to cover the .php files in the leaf dir. The Php Sniffer & Beautifier will use the .phpcs.xml file in the leaf dir to check the .php files in the leaf dir and the .phpcs.xml file in the top level to check the .php files in the src dir.

Return to the main [read me](../README.md)
