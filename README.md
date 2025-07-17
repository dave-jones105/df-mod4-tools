# df-mod4-tools
## Exercise 1: Autopsy - import Hash Database (of Known Files)
- open autopsy
- dont start a case, but go to tools -> options
- click on "Hash Sets"
- click "Import Hash Set"
- speicfy the path 
- click "Apply", then "Okay"
## [task 1 screenshot] (https://github.com/dave-jones105/df-mod4-tools/blob/main/Screenshots/001.JPG)
-having a hash set already on your computer is usefull so you can more quickly varrify the contents of files you encounter

## Exercise 2: Autopsy - create Hash Database (of Evidence Files)
- when ingesting the module, you must have Hash Lookup selected
- search for known bad files names
- select all and tag 
- get the MD5 hash values from the metadata in Autopsy 
- navigate to tools -> options -> hash sets
- select new has set
- paste all MD5 values to new db
## [task 2 screenshot] (https://github.com/dave-jones105/df-mod4-tools/blob/main/Screenshots/002.JPG)

## Exercise 3: Hex Editor - Match File Remnants
- I used notepadd++ with the Hex Editor plugin
- open the file, go to Plugins -> Hex Editor -> View in Hex
- Notepad ++ does not have a dedicated function to view only a selected sector
- You have to look at the address to determine the first sector 
## [task 3 screenshot] (https://github.com/dave-jones105/df-mod4-tools/blob/main/Screenshots/003.JPG)

## Exercise 4: Simple Encryption
