1. mkdir git-basic
2. cd git-basic
3. echo file1 > first.txt
4. git init
5. git add first.txt
6. git commit -m "adding first.txt"
7. git log
8. echo file2 > second.txt
9. git add second.txt
10. git commit -m "adding second.txt"
11. git rm "first.txt"
12. git add .
13. git commit -m "removing first.txt"
14. git log