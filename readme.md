How to use:
0. Install python if not already
1. Create a file named .gitrid, with the filename with sensitive information, the start line number of sensitive information, and end line number
  separated with space
  for example: xyz.c 2 4
  this denotes that I want to hide lines 2-4 in xyz.c
2. Run python gitrid.py before adding to repo. Do this everytime before committing as well
