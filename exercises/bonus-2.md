# Bonus Exercise 2 - Still want more? 

Use the JSON java directory that you downloaded in the earlier exercises. 

:pencil2: Try to extract all the lines that define public functions from the code files. Can
  you exclude class names?
  
:pencil2: Make a script that recursively finds all the java files below the directory
  you're in. For each file, it should extract the function names and put the
  result into a new file (all the function names from all files into one file)

:pencil2: Make your bash script directly executable so that you only have to type
  `./myScript.sh` rather than `bash myscript.sh`

:pencil2: Try to remove everything but the function names from each line. Example:

  ```java
  public void removePrefixOfFunctionName(String line) {
  ```
    
  would become
  
  ```
  removePrefixOfFunctionName(String line)
  ```
  
  or even just
  
  ```
  removePrefixOfFunctionName
  ```
