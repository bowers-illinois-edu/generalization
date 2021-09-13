---
title: |
 | Decisions
author:
 - Jake Bowers^[<jwbowers@illinois.edu>]
 - James Kuklinski
 - Carrie Cihak
header-includes: |
  \usepackage{fancyhdr,quiver}
  \fancypagestyle{myfancy}{%
    \fancyfoot[C]{}
    \fancyfoot[R]{Version of --- \today --- \thepage}}
  \pagestyle{myfancy}
secnumdepth: 2
geometry: margin=1in
link-citations: true
numbersections: true
colorlinks: true
mainfont: Merriweather-Light
bibliography: ../../Research-Group-Bibliography/big.bib
biblatex: true
---

# Overview/Introduction

A mayor has decided to work to improve the educational outcomes of low income
children in her city. Inspired by the success of the Providence Talks pilot
study, and the literature on the "word gap", she decides to try to improve the
verbal abilities of children from low income families before they enter
kindergarten.


<!--  from: https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBoBGAXVJADcBDAGwFcYkQAxEAX1PU1z5CKMsWp0mrdgCMefEBmx4CRMgCZxDFm0QgAxnP5KhRchU2SdIAJ6GFA5cORmNNLVN1Qe4mFADm8ESgAGYAThAAtkhkIDgQSADMvCHhUYgxcUhmINIwYF7pNDj0WIzskGBsySBhkUhqRfGISfK1admZzdVtSAAsjYndqfUDiNm5+X0AnEN1iA2xTcSzaQudvdyU3EA -->
\begin{tikzcd}[every arrow/.append style=-latex]
\text{Home Language Environment Quality} \arrow[rd]                                              &             \\
\text{Family SES} \arrow[r] \arrow[u] & \text{pre-Kindergarten Verbal Ability}          \\
\text{Neighborhood Poverty} \arrow[ru] \arrow[uu, bend left=69] \arrow[u] \arrow[r] & \text{Pre-School Quality} \arrow[u]
\end{tikzcd}



# A decision setting:



A mayor has decided to work to improve the educational outcomes of low income
children in her city. She begins by learning about what social scientists
currently think cause such outcomes and comes up with a graph to describe her
results.

\begin{figure}[!h]
\centering
\begin{tikzcd}[every arrow/.append style=-latex]
 {\text{Family SES}}  & {\text{Educational Outcomes}} \\
 {\text{Classroom Size}} \\
 {\text{Teacher Quality}} \\
 {\text{Neighborhood Poverty}} \\
    \arrow[from=1-1, to=1-2]
    \arrow[from=2-1, to=1-2]
    \arrow[from=3-1, to=1-2]
    \arrow[from=4-1, to=1-2]
\end{tikzcd}
\caption{A theory of educational outcomes at the level of concepts and
relationships.}\label{fig:theory1}
\end{figure}

While puzzling over what she could do with her limited budget (or what she could
convince the city council to support given the politics of that body), she hears
about the Providence Talks Program (the Mayor of Providence, RI received an
award for this program and the Bloomberg Foundation was funding a 5 city
replication of it, using RCTs instead of the original observational study
design). This was useful to  learn because it also highlighted that the first
causal graph was much too general --- Whose educational outcomes should matter?
What age? Obviously certain kinds of policy interventions focus on different
parts of the graph and aim at certain causal pathways and outcomes. The
Providence Talks program focused on verbal abilities among toddlers with the aim
that they would enter kindergarten well-prepared for school. Early childhood
education outcomes seemed like something that the mayor would like to focus on
this term --- maybe educational outcomes for older groups could be the focus
next term if she is re-elected or a focus for some other person in her
administration.


\begin{figure}[!h]
\centering
\begin{tikzcd}[every arrow/.append style=-latex]
{\text{Family SES}}  \arrow[from=1-1, to=1-2] \arrow[from=1-1, to=2-1] & {\text{Kindergarten Readiness Verbal Skills}} \\
{\text{Home Language Environment Quality}}   \arrow[from=2-1, to=1-2] \\
{\text{Neighborhood Poverty}}  \arrow[from=3-1, to=1-2] \\
{\text{Pre-School Classroom Size}}       \arrow[from=4-1, to=1-2] \\
{\text{Pre-School Teacher Quality}} \arrow[from=5-1, to=1-2] \\
   \end{tikzcd}
\caption{A theory of educational outcomes at the level of concepts and
relationships.}\label{fig:theory2}
\end{figure}




She now has some decisions to make:

 - She could commission research in her own city (let's imagine that all
   research in this paper is an RCT just to make it a bit easier).
 - She could contribute to fund research in another city (say, this is cheaper
   and less disruptive of her own city). (the other city could be (a) "like" her
   city or (b) not very similar to her own city. Where similarity has to do with
   context --- and the savvy mayor is really thinking about context as different
   variables that could change or limit any of the arrows drawn above (i.e.
   imagine a "context" node in between each of the main causal drivers and the
   outcomes)
 - She could contribute to one of the coordinated experiments occuring around
   the world (where, say, similar interventions are done in multiple different
   cities --- none of them very similar to her own city)
 - She could try to get her city to participate in a coordinated experiment.


Now, there is a preliminary problem which is that "educational outcomes" are too
vague to be easily measured. And the literature review in fact included studies
of math scores among high school seniors and studies of kindergarten readiness.
She decides to focus on kindergarten readiness and specifically on language
abilities at kindergarten entry because she read some essays that claim that
language abilities upon entering kindergarten can seriously disadvantage
children with effects that are very long term --- if those kids had not been
behind in reading and speaking and writing, they would have not been behind in
math in their senior year of high school, or been behind in high school graduate
rates.


