# Diploma thesis - Quantum turbulence & Simulations

If interested in re-building the project (check example result in `Bc_final`), clone repo:

`git clone git@github.com:KuboBahyl/diploma-thesis.git`

, open your fav LaTeX (TexMaker, Overleaf,..) compiler and run `main.tex`. In case of missing packages,
try to comment them (I'm not sure if which are necessary) or download them
freely from `https://ctan.org/pkg`.

Files `chap*.tex` (the big ones) are not compilable separately since they work only as dependency files for `main.tex`. To build any of them, try to add:

`\begin{document}`  
`...`  
`\end{document}`

with all pre-begin settings from `main.tex`, that should work.
