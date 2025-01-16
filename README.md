# Shell Script Bug: File Path Handling

This repository demonstrates a subtle bug in a shell script that processes files within a directory. The script uses `find` to locate `.txt` files, but it has an issue related to how it handles file paths, specifically when dealing with subdirectories. 

The `bug.sh` file contains the buggy script. The `bugSolution.sh` provides the corrected version.

The bug is described in detail within the code comments.  This example highlights the importance of careful path handling in shell scripting to prevent unexpected errors.