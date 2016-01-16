# Beautification test results

In an effort to automatically keep the Authoring Practices Guide (APG) source
code readable, we would like to introduce some rules and scripts to do so.
These automation efforts should not prohibit editors to make edits.
Cleanliness of the APG source code will help editors expand it more easily.
It is thus important that the source code be kept readable.
This is currently not the case.

There is a copy of the APG as it was on 16th of January 2016 in this folder.
This will ensure consistency between tests and their results.

## Test 1: EditorConfig

Arguable the easiest way to improve readability and consistency of the APG
source code is an EditorConfig file; such a file provides certain settings
for text editors. These settings include removal of whitespace at the end of
lines, consistent use whitespace before lines, and consistent line feeds.

EditorConfig files cannot prevent inconsistent indentation,
line feeds between elements, and code validation.

APG's EditorConfig file can be found in the practices folder and is named
`.editorconfig`. This file is hidden by default on most operating systems.

### EditorConfig test result

Steps taken to achieve result:

1. Open test-1-editorconfig.html
2. Converted tabs to spaces with separate plugin
   (EditorConfig does not convert current characters, remember,
   it applies settings for future use)
3. Save file

The result of these steps can be found in `test-1-editorconfig.html`.

### EditorConfig conclusion

While future edits will now be consistent in the use of certain characters,
nothing has really changed in the document
(except for the conversion of whitespace).
For a more readable editor experience we need more rigorous measures.
