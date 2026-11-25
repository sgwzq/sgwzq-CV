# sgwzq-CV

My curriculum vitae (CV) written using LaTeX. In my CV, you may find my contact information, websites, education, experience, achievements, projects, and skills.

## Run on Terminal

On Arch Linux, install the TeX Live packages for both CVs if needed.

```sh
sudo pacman -S --needed texlive-binextra texlive-xetex texlive-latexextra texlive-fontsrecommended texlive-fontsextra texlive-langchinese
```

From the repository directory, build the English and Chinese PDFs with XeLaTeX.

```sh
latexmk -xelatex main.tex
latexmk -xelatex main-cn.tex
```

The commands produce `main.pdf` and `main-cn.pdf`. The English CV also supports `pdflatex main.tex`.

## Screenshots


## Author

👤 **Ziqiu Wang**

* LinkedIn: [@sgwzq](https://www.linkedin.com/in/ziqiu-wang-3b792542a/)
* GitHub: [@sgwzq](https://github.com/sgwzq)
