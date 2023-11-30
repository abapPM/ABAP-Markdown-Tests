# Test Various Types of Links

## File

[Readme](README.md)
![Book](book.png)

## File with `.`

[Readme](./README.md)
![Book](./book.png)

## File with `..`

[Readme](../README.md)
![Book](../book.png)

## File with relative path 

[Readme](test/README.md)
![Book](test/book.png)

## File with absolute path 

[Readme](/tests/README.md)
![Book](/tests/book.png)

## URL same repository

[Readme](https://github.com/Marc-Bernard-Tools/ABAP-Markdown-Tests/blob/main/README.md)
![Book](https://raw.githubusercontent.com/Marc-Bernard-Tools/ABAP-Markdown-Tests/main/tests/book.png)

[Readme](https://github.com/Marc-Bernard-Tools/ABAP-Markdown-Tests/blob/main/README.md)
![Book](https://raw.githubusercontent.com/Marc-Bernard-Tools/ABAP-Markdown-Tests/main/tests/book.png)

## URL same server, different repository

[Readme](https://github.com/abapGit/abapGit/blob/main/README.md)
![Book](http://raw.githubusercontent.com/Marc-Bernard-Tools/ABAP-Markdown-Tests/main/tests/book.png)

[Readme](https://github.com/abapGit/abapGit/blob/main/README.md)
![Book](https://raw.githubusercontent.com/Marc-Bernard-Tools/ABAP-Markdown-Tests/main/tests/book.png)

## URL different server

[Readme](http://marcbernardtools.com/)

[Readme](https://marcbernardtools.com/)
