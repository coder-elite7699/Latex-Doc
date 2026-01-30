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

### Writing Algorithm: 
Make sure include below packages for algorithm  
```latex
\usepackage{algorithm}
\usepackage{algpseudocode}
```

Code  
```latex
\begin{algorithm}
\caption{Binary Search}
\begin{algorithmic}
\State $l \gets 0$
\State $r \gets n - 1$
\While{$l \le r$}
    \State $m \gets \lfloor (l + r)/2 \rfloor$
    \If{$A[m] = x$}
        \State \Return $m$
    \EndIf
\EndWhile
\State \Return $-1$
\end{algorithmic}
\end{algorithm}
```
