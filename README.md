[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



# About the Project
This repository will contain my LaTeX templates, lecture notes, etc. for the MA Mathematics program 
that I will be taking at the University of the Philippines Diliman.


## Lecture Notes Template

The only thing special with this template is that it lets you write elegant Definitions, Theorems, etc. using the `itaewon` package.

#### Sample Usage

```tex
\documentclass{article}
\usepackage{itaewon}
\usepackage{amsfonts}

\begin{document}

    \begin{DefinitionBox}[]{Definition}{Vectors in $\mathbb{R}^n$}
        
        Lorem ipsum dolor sit amet, consectetuer adipiscing elit.  
        Etiam lobortis facilisissem.  Nullam nec mi et neque pharetra 
        
        sollicitudin.  Praesent imperdiet mi necante...
    \end{DefinitionBox}

\end{document}


```

#### Sample Output

![alt text](screenshot.png "Title")

[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/benjcabalona1029/MAMathematics2021/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/benjcabalonajr
