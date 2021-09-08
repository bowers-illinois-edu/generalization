---
title: | Decisions
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
bibliography: ../../Research-Group-Bibliography/big.bib
biblatex: true
---

# A fiction:

A mayor has decided to work to improve the educational outcomes of low income
children in her city. She begins by learning about the causes of such outcomes
and comes up with a graph to describe her results.


\begin{tikzcd}
 {\text{Family SES}}  & {\text{Educational Outcomes}} \\
 {\text{Classroom Size}} \\
 {\text{Teacher Quality}} \\ 
    \arrow[from=1-1, to=1-2]
    \arrow[from=2-1, to=1-2]
    \arrow[from=3-1, to=1-2]
\end{tikzcd}


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







Studies do not cumulate. Humans cumulate them: Six Implications of this
 |fact for study coordination for scientific learning and policy action.

Over the past 50 years the US federal government has funded XX studies of the
effectiveness of remote intercessory prayer on the health outcomes of people:
the causal graph:

\begin{tikzcd}
 {\text{Persons A,B,$\ldots$ pray that person Y health improves}}  & {\text{Person A Health}} \\
    \arrow[from=1-1, to=1-2]
\end{tikzcd}

Would it have been better to have coordinated the studies? 

The point of this paper is in the title or alternative titles: 
 - Research designs do not generalize: Humans do.
 - It is all about theory.
 - We study to explain.

These ideas have been articulated before in Shadish etc and even are implicit in
Baremboim. This paper applies them to the question about the policy relevance
and application of studies / cumulated or not. And the question of how
coordianted studies might add value or improve policy decision making. At the
root is the problem of multiple DAGs.

What is the problem? 

The problem is that a given policy maker making a decision
may not be able to use findings about some $\theta_1$ because that path is not
manipulable --- practical or political or ethical reasons prevent use of that
path. So learning that, say, 1,2 or 10 other cities had changes in $Z_1$ work
well for $Y$, doesn't matter for that policy maker. 

The other problem is that the policy maker may have a different DAG --- may not
believe that $\theta_1 > 0$ in their city (**this** could be answered perhaps by
studies in places with similar context to $Z$ and context to $Y$ relationships).

The next problem is that a policy maker may not believe the results --- even if
$Z$ is manipulable and if the policy maker thinks that the context would allow
$Z$ to operate as hoped for or as reported in other places. The policy maker may
worry that the information about $\theta_1$ is basically a political claim, a
statement of hope or desire and not a report from a study which could replicate
even in its own context. Fears of fraud. Fears and mistrust of the producers of
the studies.

And of coruse by $Z$ we are talking about the precise ways that $Z$ could be
manipulated --- when there is the slippage in concept (what it means to provide
coaching to families in one city might be different in another city --- so there
may be no $Z$ but a series of related manifestations --- where the diffeernces
could easily lead to big differences in outcomes or at least a savvy leader may
fear this.)

Given a shared DAG. And a sense that you can intervene on one arm. Then the
question is about either or both of $\theta$ and $p$ or posterior about
$\theta$. But often we do not have a shared DAG and the purpose of the study is
to suggest that one or more paths of a DAG are 0 or non-zero, or perhaps
describe the moderating effect of certain contexts (also paths on the DAG, but
indirect).






What are the implications?

 - We need to elicit DAGs from both researchers and policy decision making
   teams.
 - Studies can and should target parts of the DAGs --- they need not target the
   main driver to main outcome if that is difficult. We may learn more by
   targetting parts of the DAGs.
 - Some studies basically add evidence to the existence of a path in a DAG ---
   which in and of itself is useful but may not make it easier for a policy
   expert to use the study.
 - Studies must be intelligible and trusted in order to be useful.
 - Concepts are not the same.

