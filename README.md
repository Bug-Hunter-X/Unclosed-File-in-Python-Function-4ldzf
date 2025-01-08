# Unclosed File Bug in Python

This repository demonstrates a common error in Python: not properly closing files.  This can lead to resource leaks, especially when dealing with many files.

The `bug.py` file contains the buggy code. The `bugSolution.py` file provides a corrected version using `with open(...) as f:` which ensures the file is automatically closed, even if exceptions occur.