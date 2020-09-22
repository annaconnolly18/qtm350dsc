#!/bin/bash

# Author: Anna Connolly, 2216423

# Write a script called exercise1-<your-name-here>  that takes as input one argument, a directory, and outputs the number of different permission types in this directory.

clear

ls -l $1 | cut -d ' ' -f 1 | tail --lines=+2 | uniq | wc -l