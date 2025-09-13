# Beamer + Simplus (XeLaTeX, main.tex)

- XeLaTeX only build (Korean-friendly)
- Local Simplus theme included (`themes/simplus/beamerthemesimplus.sty`)
- Entry point: `main.tex`

## Build
- VS Code: use the provided recipe `latexmk (XeLaTeX)`
- Terminal:
  ```bash
  make       # builds main.pdf with xelatex
  make clean
  ```

## Notes
- If you prefer the official CTAN `beamer-simplus`, remove the local theme and install the package system-wide, keeping `\usepackage[blue]{beamerthemesimplus}`.
