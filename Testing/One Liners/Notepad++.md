## Pull Emails
###### Find
```regex
(\\b\[A-Za-z0-9.\_%+-\]+@\[A-Za-z0-9.-\]+\\.\[A-Za-z\]{2,4}\\b)
```
###### Replace
```regex
\\n$1\\n
```
***