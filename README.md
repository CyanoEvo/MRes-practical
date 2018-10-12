# MRes-practical

# PT1: Learning the command line
# Objectives:
# 1. Learn how to navigate around the Unix command line
# 2. Learn how to write a for loop to perform multiple operations
# 3. Real life example

BASH commands we will use:

`$pwd`: shows you where you are

`$ls`: shows you what is in a folder

`$mkdir dirname`: makes a new folder 

`$cd dirname`: change into the specified folder 

`$cd ..`: change into the previous folder 

`$touch filename`: makes a new empty file

````
$mkdir Sandbox
$ls
$cd Sandbox
$mkdir f1 f2 f3
$ls
````

````
$for folder in ~/sandbox/f*; 
 do cd $folder &&
    touch test &&
    cd ..; 
 done
 ````
 
 ````
$for sample in ~/Sequences/S*; 
 do cd $sample &&
    mafft --auto *.fasta >
    cd ..; 
 done
 ````
