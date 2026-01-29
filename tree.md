# Latex
Learning Latex which result in this document.
## Making Tree data Structure in Latex
Lets take an example for tree data structure: 
```
node
 ├─ child
 │   ├─ child
 │   └─ child
 └─ child
```

### Make sure to include the following library
```latex
\usepackage{tikz}
\usetikzlibrary{trees}
```
### The logic to draw the above tree data structure: 
```latex
\begin{tikzpicture}[<options>]
  \node {Root}
    child { node {Child1} }
    child { node {Child2} };
\end{tikzpicture}
```


### Nested Children
```latex
\node {A}
  child {
    node {B}
    child { node {D} }
    child { node {E} }
  }
  child { node {C} };
```

### option
```latex
node[circle,draw] {A}
```

### Universal Styling
```latex
\begin{tikzpicture}[
  every node/.style={circle,draw},
  level distance=1.2cm
]
```
