# Modelo de TCC da Universidade Anhembi Morumbi em LaTex #
Este projeto contém um modelo em LaTex do formato do TCC utilizado pela UAM em 2016.

# Instruções para gerar o PDF #

Para "compilar" esse modelo e gerar o arquivo no formato “.pdf”, os seguintes
comandos devem ser executados: pdflatex tcc-SI.tex, bibtex tcc-SI e mais duas vezes pdflatex
tcc-SI.tex.

Em alternativa, ao usar o TexMaker, basta configurá-lo em Opções -> Configurar o TexMaker -> Compilar[MENU ESQUERDO] e usar a opção PdfLaTex + Bib(la)tex + PdfLaTex(2x) + View PDF.

Obs: Necessarios os pacotes texlive-babel-portuges, texlive-babel-french texlive-abntex2 texlive-titlesec texlive-lastpage texlive-ulem
