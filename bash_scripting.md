#Bash
##IMP
1. Never miss out on the $
2. $variable will be treated same as ${variable}
3. If failed to write the "PATH" without the $ it would be treated as a normal string
4. If you see a "" in between the path that means its empty space (null)
5. We use "" except of this ''.

##Example
* $val="123"
* val=/path1:/path2:$val
* val=/path3:$val
* Explination
* val=/path1:/path2:$val="/path1":"/path2":"123"
* val=/path3:$val="/path3":"/path1":"/path2":"123"







