## Math support

We can use inline math like this:  $a^2>=2$ 

This is display math:
$$
1 + 2 + 3
$$

This is display math with align:
$$
\begin{align}
\pi_{1}(A\times B) & =A,\\
\pi_{2}(A\times B) & =B.
\end{align}
$$

## Using preambles

We can use the plugin [`obsidian-latex`][plugin] to have macros.

[plugin]: https://github.com/xldenis/obsidian-latex/

Do the macros work? $\mymacro$. 

Example use:

$$
\begin{prooftree}
\AxiomC{$\typing[x : A, \Gamma]{M}{B}$}
\RL{(T-ABS)}
\UnaryInfC{$\typing{\lambda x. M}{A \rightarrow B}$}
\end{prooftree}
$$

$$
\begin{prooftree}
\AxiomC{$\typing{M}{A \rightarrow B}$}
\AxiomC{$\typing{N}{A}$}
\RL{(T-APP)}
\BinaryInfC{$\typing{M~N}{B}$}
\end{prooftree}
$$

$$
\begin{prooftree}
\AxiomC{$x : A \in \Gamma$}
\RL{(T-VAR)}
\UnaryInfC{$\typing{x}{A}$}
\end{prooftree}
$$
