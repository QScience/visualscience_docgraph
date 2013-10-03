Visual Science - Document Graph
===============================

This project provides some visual information about the connections between
authors of papers, references and citations between papers.

The aim is to extend features with keyword extractor and display those
informations as well.

Important changes
===

Because of some Drupal caching or file renaming we had to change the 'arbor_path()' function of arbor.js.
Now it uses a variable set by Drupal instead of getting the path from the Script's src attribute to import some other files.
