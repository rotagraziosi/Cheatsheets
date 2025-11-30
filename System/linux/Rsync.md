
# Description

Allow folders synchronization between a source and a destination.

# Arguments

Usual arguments : 

-a : archive mode
-v : verbose
-h : human readable
-P : progress

# Examples

## Copy a folder into another one

`rsync -avhP source destination`

The result will be destination/source/* .

## Copy the files from a source into a destination

`rsync -avhP source/ destination`

The result will be all the files and folder from source will be in the destination folder.






