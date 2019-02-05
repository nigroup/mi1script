# !!! Under Construction !!! #

# Machine Intelligence I: Supervised Methods #

Latex sources for generating the lecture notes to the [Machine Intelligence I: Supervised Methods](https://www.ni.tu-berlin.de/menue/teaching_activities/all_courses/machine_intelligence_i/) course at the TU Berlin

## Disclaimer ##

The lecture has been restructured in the previous terms (WiSe 2016/17 as well as WiSe 2017/18) and several new topics were added, too. Many of these changes are so far only reflected in the lecture slides but not yet in these lecture notes which are thus outdated. Although we plan to complete the lecture notes soon, it is unlikely that we reach this goal until the end of the term. Therefore, it is strongly recommended to make hand-written notes within the lectures to complement the information of this script. We apologize for the inconvenience.

## Setup ##

Ubuntu:

    apt-get install texlive-full
    # Optional 
    apt-get install texmaker (an editor we like to use)

## Generating the pdf ##

Texmaker

    Tools > Quick Build

OR

    Tools > PdfLaTeX + Tools > View PDF

Unix

    cd ./latex
    pdflatex -synctex=1 -interaction=nonstopmode mi1.tex


## License

The content of the lecture notes itself is licensed under the [Creative Commons license](https://creativecommons.org/licenses/by-nc-sa/1.0/), and the underlying source code used to generate, format and display that content is licensed under the [BSD 2-clause license](LICENSE).
