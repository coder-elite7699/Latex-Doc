# Working With Code
### Inlclude the following Package
```latex
\usepackage{listings}
\usepackage{xcolor}
```

### Styling of the code Block
```latex
\lstset{
    basicstyle=\ttfamily\small,
    numbers=left,
    numberstyle=\tiny,
    stepnumber=1,
    frame=single,
    breaklines=true,
    tabsize=2,
    showstringspaces=false,
    keywordstyle=\color{blue},
    commentstyle=\color{gray},
    stringstyle=\color{orange}
}
```

### Code Block
```latex
\begin{lstlisting}[language=Python]
def merge_sort(arr):
    if len(arr) <= 1
        return arr
    mid = len(arr) // 2
    return merge(merge_sort(arr[:mid]), merge_sort(arr[mid:]))
\end{lstlisting}
```

Primary Language which are supported: 
1. C
2. C++
3. Java
4. Python
5. Javascript
6. SQL
7. Bash
8. many more....
