# Olympiad Training *Treinamento Olimpíco*

Material for Alpha Online's basic olympiad training. *Material para o treinamento Alpha Online para olimpíadas básicas.*

Note that all the problems and documents are in Portuguese. *Note que todos os problemas e documentos estão em português.*

The problems can be found [on this problem database](https://github.com/TiagoCavalcante/problem_database). *Os problemas podem ser encontrados [nesse banco de dados de problemas](https://github.com/TiagoCavalcante/problem_database).*

## How to build? *Como gerar o PDF?*

```sh
latexmk -bibtex -pdf -pvc --shell-escape -interaction=nonstopmode -outdir=./pdf tex/[filename].tex
```

Note that this project was only tested in Linux. *Note que esse projeto foi testado apenas no Linux.*

## How to install the dependencies? *Como instalar as dependências?*

```sh
sudo apt install texlive-full
```
