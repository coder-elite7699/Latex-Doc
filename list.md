# Working with list in Latex
## Unordered list
```latex
\begin{itemize}
  \item First item
  \item Second item
  \item Third item
\end{itemize}
```
## Ordered
### Defult 1,2,3
```latex
\begin{enumerate}
  \item First step
  \item Second step
  \item Third step
\end{enumerate}
```

### Custom Numbering Style
For this we have include package: \usepackage{enumitem}
```latex
\begin{enumerate}[label=\alph*)]
  \item First
  \item Second
\end{enumerate}
```

### Adjusting Spaces between items: 
```latex

\begin{itemize}[itemsep=5pt, topsep=2pt]

```

### Inline List: In One Line
```latex
\begin{enumerate*}[label=(\arabic*)]
  \item one
  \item two
  \item three
\end{enumerate*}
```

### Cutsom Symbol: 
```latex
\begin{itemize}
  \item[$\star$] Star item
  \item[$\rightarrow$] Arrow item
\end{itemize}

```
