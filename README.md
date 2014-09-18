# Proposal for the Typogrify project

This is a rough first proposal for the Typogrify project. It addresses the following deficiencies of the current project:

 1. It uses a HTML parser (as oppossed to a regex)
 2. The regex for the filters are less complex (mostly due to reason number 1)
 3. The regex for the filters have been cleaned up
 4. The codebase has been neatened up
 5. Specifically ignores tags like script (which does not affect Pelican only because documents are typogrified before scripts are added)
