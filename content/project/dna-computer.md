+++
# Date this page was created.
date = 2016-04-27T00:00:00

# Project title.
title = "DNA computer"

# Project summary to display on homepage.
summary = "Construction of multi-state DNA computer working with more than one restriction enzymes."

# Optional image to display on homepage (relative to `static/img/` folder).

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["dna-computer"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).

+++

<span style="text-align: justify;>
 **Biomolecular  computers**,  along  with  quantum  computers,  may  be  a  future  alternative  for  traditionastrikethrough textl,  silicon-based computers. Main advantages of biomolecular computers are massive parallel processing of data, expanded capacity  of  storing  information  and  compatibility  with  living  organisms  (first  attempts  of  using  biomolecular computers in cancer therapy through blocking of improper genetic information are described in [Benenson et al.](https://www.ncbi.nlm.nih.gov/pubmed/11719800) However,   biomolecular   computers   have   several   drawbacks   including   time-consuming   procedures   of preparing of input, problems in detecting  output signals and interference with by-products. Due to this obstacles, there  are  few  laboratory  implementations  of  theoretically  designed  DNA  computers,  but  there  are  many implementations of DNA computers for particular problems. The first practical laboratory implementation of the  general  theoretical  model  of  a  machine  performing  DNA - based  calculations  was  a  simple  two-symbol  two-state  finite  automaton  established  by  the  Shapiro  team and  it  was  described  in previous  section of  this  project. The authors of Shapiro indicated also limitations of their method in construction of finite automata with greater number  of  states.  They  pointed  that  the  restrictions  are  short  sticky  ends  (4  possible  nucleotides)  and  say  that one could built at most 3-state automaton by using Fok I. But they also indicates that new enzymes, which will be found  in  the  future,  will enable  construction  of  many  states  automata  (they  will  use  longer  sticky  ends). This approach was used by two teams to enhance Shapiro automaton to three states with up to 37 different symbols. In  the  present project,  we  proposed  a  new  attitude,  extending the  capability  of  DNA-based  finite  automaton,  by employing  two  or  potentially  more  restriction  enzymes  instead  of  one  used  in  other  works.  This  creates  an opportunity  to  implement  in  laboratories  of  more  complex  finite  automata  and  other  theoretical  models of computers: *pushdown automata and Turing machines*. 
</span>

**The aims of the project were**:

 1. to implement in laboratory the multi - state DNA computer by
    enhancing of Shapiro automaton, 
    
 2. to study probabilistic model of DNA
    computer based on Shapiro automaton regarding different parameters
    of its reaction.
    
**These objectives were realized through:**

 1. construction of DNA library representing DNA molecules of DNA computer based on enhanced Shapiro automaton to many-state,
 2. laboratory verification of enhanced Shapiro automaton to 6 state,
 3. optimization of enhanced Shapiro automaton to many-state works by establishing of optimal reaction condition including various DNA molecule length,
 4. establishing the role of nondeterminism in 6-state DNA computer,
theoretic and practical implementation of 9-state DNA computer based on Shapiro automaton

