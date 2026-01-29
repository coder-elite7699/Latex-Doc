# Initialization
How to initialize a blank Latex Document  
Syntax
```latex
documentclass[options]<class>
\begin{document}
Hello Latex
\end{document}
```
For writing article on A4 size paper: 
```latex
documentclass[options]<class>
\begin{document}
Hello Latex
\end{document}
```
List of Classes:  
1. article
2. report
3. book
4. letter
5. sildes/beamer
6. minimal

For Options following can be used:  
1. Font size: 10pt, 11pt, 12pt(max)
2. Paper Layout: a4paper, letterpaper(default), legalpaper
3. Layout:
 1. oneside, twoside(default for book class)
 2. onecoulmn(default), twocolumn
 3. landscape
4. Title Page: titlepage, notitle
(article defaults to notitlepage while report and book defaults to titlepage
