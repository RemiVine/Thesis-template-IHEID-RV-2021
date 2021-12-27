# Thesis-template-IHEID
This is a LaTeX template for paper-based IHEID thesis. I built it using *overleaf*, I am not sure it works directly on other LaTeX.

The template allows to have a thesis with independent chapters, containing their own appendices and bibliographies. On the other hand, it is meant to have sections, figures, etc. numbered as part of a consistent document. 

The use of this template shall be rather intuitive. The folder "Chapter" is meant to include the main.tex document, one by one, of your thesis. The respective bibliographies are to be inserted in the "Bibliography" folder.

There is one bibliography per paper and only the referred documents are displayed in the bibliography. I chose the "Chicago" style, you can change that in the "BIBLIOGRAHPY" part of the "packages.tex" file (the *ad hoc* *\stylechoice* command).

:warning:          Every chapter contains its own appendix. The appendix for each paper must be put within *\begin{subappendices}* ... *\end{subappendices}*

## The folder contains:
 
 
 - **Bibliographies**
     - *preamble.bib*
     - *paper1.bib*
     - *...*
 - **Chapters**
     - *0_Abstract_Page.tex*    &rarr;   this is required as the last page of the specimen
     - *0_Acknowledgments.tex*   &rarr;   *optional*
     - *0_pre_thesis_quote_dedication_etc.tex*    &rarr;   *optional*
     - *Paper1.tex*
     - *...*
     - *Preamble.tex*
- **Editing**
     - *specimen.tex*    &rarr; IHEID-specific template for the first 6 pages
     - *glossary.tex*    &rarr; can be used for listing abbreviations (or to do a glossary, more on the file) 
     - *information_to_fill.tex*   &rarr;  must complete these information to fill the specimen
     - *logo.png*        &rarr; IHEID logo (to adapt if changed...)
     - *packages.tex*    &rarr; I add put the packages that were useful to me
- **graphs_and_pictures**
     - *Waldseemuller_map.jpg*
     - *...*
- **IMPRIMATUR.pdf**    &rarr;   must change this with the document the IHEID will provide you with once the defense done
- **main.tex** 
 
 
 ## Some changes to be done
 
- **Personnal information, discipline, *etc.*** 
   - *information_to_fill.tex* contains all the personnal information that should be changed for the specimen 
   - make sure the year is the correct one (if pre-defense and post-defense submissions at different years)
   - the thesis number will be given by the administration
   - the imprimatur will be given by the administration after the defense
 
 ## Changes that can be done 

- **Font size**  &rarr;   directly in the *main.tex*
- **Include or not** table of contents, list of figures, list of tables, list of abbreviations    &rarr;   directly in the *main.tex* 
- **Margins**   &rarr;    in the *packages.tex*
- **(Hyper)link color**   &rarr;    in the *packages.tex*
- **Bibliography style**    &rarr;   in the *packages.tex*
- **Font type** &rarr; can be changed if using a different compiler






