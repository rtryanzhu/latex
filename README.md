# latex

# quick command in editing math formulae

\newcommand{\bl}[1]{\bm{#1}} % bold letter for vector/matrix
\newcommand{\ul}[1]{\underline{#1}} % underlined letter for vector/matrix
\newcommand{\pd}{\partial} % partial derivative notation
\newcommand{\hf}{\frac{1}{2}} % just 1/2 
\newcommand{\dl}[1]{\mathbb{#1}} % double letter with args
\newcommand{\grad}{\nabla} % gradient notation
\newcommand{\fun}[1]{\mathcal{#1}} % script letter for functions
\newcommand{\norm}[1]{\lVert #1 \rVert} % norm

# multiple conditions
\begin{equation*}
    \begin{cases}
        f_{x}=\frac{\pd f}{\pd x}=0\\
        f_{y}=\frac{\pd f}{\pd y}=0
    \end{cases}
\end{equation*}

# calculation process
\begin{align*}
        \grad g(\ul{z})
        &=\hf \begin{bmatrix}
            \frac{\pd}{\pd z_1} \\
            \frac{\pd}{\pd z_2} \\
        \end{bmatrix}+\ul{c}\\
        &= \hf (\ul{Q'}+\ul{Q})\ul{z}+\ul{c}
    \end{align*}

# calculation process of vecotrs
    \begin{align*}
        \grad g(\ul{z})
        &=\hf \begin{pmatrix}
            \begin{bmatrix}
                \frac{\pd g(\ul{z})}{\pd z_1} \\
                \frac{\pd g(\ul{z})}{\pd z_2} \\
            \end{bmatrix}-
            \begin{bmatrix}
                \frac{\pd \sum_{i=1}^{2}{c_i z_i}}{\pd z_1}\\
                \frac{\sum_{i=1}^{2}{c_i z_i}}{\pd z_2}\\                
            \end{bmatrix}
        \end{pmatrix}\\ 
        &= \hf (\ul{Q'}+\ul{Q})\ul{z}-\ul{c}
    \end{align*}\\

# limit symbol
$\lim\limits_{v_k \to 0}$
