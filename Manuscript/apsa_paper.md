---
title: |
 | What is the role of coordinated studies in evidence-based policy making?
author:
 - Jake Bowers^[<jwbowers@illinois.edu> Thanks to Jim Kuklinski (University of
   Illinois), Carrie Cihak
   (King County, WA),
   James Diossa (The Policy Lab @ Brown), and participants in The Policy Lab @
   Brown University Providence Talks Replication project and meetings.]
date: September 26, 2021
header-includes: |
  \usepackage{fancyhdr,quiver,float}
  \fancypagestyle{myfancy}{%
      \fancyhf{}
      \renewcommand{\headrulewidth}{0pt}
      \fancyfoot[R]{Version of --- \today --- \thepage}}
  \pagestyle{myfancy}
secnumdepth: 2
geometry: margin=1in
link-citations: true
numbersections: true
colorlinks: true
fontsize: 11pt
bibliography: ../../Research-Group-Bibliography/big.bib
biblatex: true
biblio-style: authoryear-comp
---

\begin{abstract}

Coordinated randomized trials can help convince researchers that certain kinds
of causal explanations are more or less plausible: helping elaborate a shared
causal model linking interventions to outcomes. Policy makers may not share the
same causal model although coordinated studies combined with transparency
practices may convince policy makers to add nodes and paths to their model.

\end{abstract}

How can the advances in the cumulation of social science knowledge and
extrapolation of findings from one context to another help policy makers make
better decisions within their jurisdictions? As the evidence-based public policy
movement increases in strength and scope, many policy experts are eager to
ensure that tight budgets are efficiently and effectively allocated --- so that
money is not wasted, and most lives are improved. How can the promises of this
movement to be policy makers be fulfilled by efforts in academia to coordinate experiments,
to increase transparency, and to better predict the results of studies done in
one place in another? This paper is motivated by the second question and tries
to answer the first.

To foreshadow the contributions here: I suggest that the challenges to the use
of, say, an average treatment effect and confidence interval resulting from
either a single study, a set of coordinated studies, or an extrapolation using
some weighting or prediction faced by a mayor or a city council or some other
policy making body are not currently well addressed with current developments
from academia, although those developments lay the groundwork to overcome some
of those challenges. It seems to me that academia can help policy makers most,
at this stage in the development of the evidence-based policy movement, in the
development of theoretical frameworks explaining the mechanisms between possible
inputs and desired outputs. This effort may be helped by coordination among
policy-maker+academic teams, and will certainly be enhanced by academic studies
to help everyone learn about the proposed causal connections that policy makers
aim to use to wield the power of government for the public welfare.

# The problem of a single study and current academic and policy responses.

A group of policy makers must make a policy and oversee its implementation in a
given place and time.^[I'm imagining a city council or other executive group in
this paper.] This policy is a change to some process that the policy makers hope
will improve some outcomes in their jurisdiction. For example, they might hope
to improve both the mental and physical health, comfort, and neighborhood
attitudes of urban neighborhoods by planting trees along the sidewalk. Or they
might hope to improve the kindergarten readiness of low income children by
funding a program to coach families in how to talk and read with their
toddlers. Or they might make all public transit free in their city in order to
reduce inequality and improve the economy. In each case they have choices about
how to pursue these outcomes.  And they also face trade-offs across different
areas.

Studies of the effects of coaching on kindergarten readiness or trees on
attitudes should, in principle, help policy makers. Or at least, many
researchers justify their research to themselves and others on the grounds of
policy relevance. And, to date, a fan of evidence-based policy and a proponent
of a new approach might say: "This is a promising approach that I heard about that
worked in City B." and then explaining, "The finding was statistically
significant. I think it was an RCT." And others then asking whether and how the
implementation of that approach might need to be adapted to City A and whether
the context of City A might cause the effect of the new approach (say, planting
trees, coaching the families of toddlers, or free public transportation) to have
different effects and consequences than those new approaches had in City B.

However, even as people with a priori reasons to be attracted to a given new
approach discuss implementation problems, they also know that researchers can
criticize the results of any single study on many grounds --- if the results do
not agree with the priors of some other group, such opponents might dismiss the
results if the analysis was not done in a transparent way (for example if the
analysis plan was not pre-registered or the code and data were not made public).
Or they might argue that even a $p < .01$ for a null hypothesis of no effects
merely means that a given result could be a rare event --- yes, surprising from
the perspective of the null hypothesis, but making an rare error doesn't change
the cost that error on the public. If the result arose in a study in a context
very different from the given city, critics might argue that, say, a positive
result in City B ought not be used as evidence on which to base a costly policy
change in City A.

Knowing about these criticisms, but still convinced that scientific research
should play a role in policy decision making, researchers have developed a
series of changes in practice. So, for example, a growing number of
evidence-based policy groups pre-register their analyses, carefully document the
complex flows of data files and code files that merge, clean, and analyze. These
groups also try to share as much of their data as possible and engage in internal
quality checks like blind re-analysis of results and/or code-reviews (where as
much as possible done so as to be available to the public). Since many of the
studies done by these groups involve randomization, they tend to rely on
design-based statistical tests so as to protect their statistical inferences
from false positive errors arising from statistical technique choices.

Although those efforts have increased the utility of the policy evaluations
those groups produce by reducing the plausibility of some criticisms, they have
still left the concerns about the surprisingly large result from a single study
arising by chance and the concerns that a large, positive causal effect in one context
might be small, or negative, in another context.

# The promise of coordinated randomized studies

Coordinated randomized studies aim to address the two remaining criticisms above and
provide some other benefits to scientific knowledge cumulation. I will
describe them briefly here but note below that, to be useful for a policy
decision in City A, even responding to all of the criticisms above is not
enough.

If two studies investigate the $Z \rightarrow Y$ relationship and measure both
$Z$ and $Y$ the same way, manipulate $Z$ in the same way, and occur in the same
context (place and time), then we can respond to the first set of concerns about
confusing chance events with causal effects.

If two studies occur in different contexts, but, as much as possible, coordinate
measurement and intervention, then we create information to address the second
set of concerns about heterogeneity of causal effects. Of course, differences in
detected causal effects between the two studies could also arise from chance and
not context.  So, adding more studies helps us distinguish between context-based
differences in effect and chance differences. (TODO: Elaborate on this a bit)

In these two kinds of coordinated experiments --- where effort goes into
coordinating measurement and intervention --- another benefit arises: an overall
causal effect of $Z$ on $Y$ can be estimated by combining the studies, thereby
increasing the statistical precision of the estimation of this causal effect
over that possible in any single study. For example, one can treat the multiple
experiments as a single block-randomized experiment and one can estimate an
average causal effect for the units in all the studies.^[If the causal effects
might vary greatly across blocks, say, from strongly negative to positive, the
average causal effect could be zero. This would be valid for that estimand. Of
course, one could also assess the $Z \rightarrow Y$ causal relationship using
other tools which would report a strong relationship in this case.]

TODO: Either side step or talk about observational studies where coordination
has yet more benefits in helping us manage the biases inherent in non-randomized
studies. See Rosenbaum's 2021 Replication and Evidence Factors in
Observational Studies.

So, if we can address all of the criticisms that opponents of a policy like
planting trees, coaching families, or free public transit using strong research
transparency and integrity practices combined with coordinated studies, should
the policy makers in City A now have an easier time making decisions than they
did before these developments?

# Challenges in the use of coordinated studies by policy makers

Yes. The evidence in the hands of the policy makers in City A is certainly more
useful if it arrives from the kinds of processes just described. Yet, the
criticisms and responses just described left out the political and human costs
of error on the part of the policy makers. They also ignored the concern that,
even if an intervention appeared powerful in multiple contexts, and even if it
was predicted to be powerful in City A using state of the art causal
extrapolation approaches, it might be too small to be worth doing given the
other policy options vying for attention and budget among the leaders of City A.

Here is a list of some of the challenges facing those aiming to influence the
kinds of outcomes listed above as examples in their use of the results of
coordinated studies. Two conversations with policy makers crystallized many of
these points for me, which I had also observed as I participated in the design
of a coordinated experiment across 5 cities on coaching and kindergarten
readiness. So, I write this list as questions and answers even even if this is
not a record of any single dialogue.

Q: What is the use of a coordinated study done in Cities B,C,D,E and F for City A?

A: If one or more of those cities is similar to City A, then the results **for
that or those cities** would be used if the policy intervention is realistic for
City A. Results in not-similar cities or cities where the intervention differed
from the possible intervention for City A would be ignored for fear that they
would be misleading in regards the possible effect in City A.

However, if an overall result, calculated using all of the cities, convinced a
philanthropic foundation to fund a not-harmful intervention in City A, then, as
long as the intervention did not face political opposition, City A would be
willing to try to create a locally relevant implementation of the intervention.

Q: What about state-of-the art extrapolation from the not-similar cities to City
A using covariates measured in both places?

A: Conditional on the intervention being politically and practically plausible
and covariates measured the same way, with the same meaning in both place, then
if such tools confirmed prior beliefs, then they would not be rejected.  Errors
are so costly that proponents of such tools have a lot of work to do to convince
policy makers of their utility, let alone to overcome the prior concerns about
the meaning and measurement of covariates.

Q: What would it mean to use a result?

A: A result inspires a discussion about how to adapt the approach in the other
places to the local context. If those implementing the new approach design a
randomized trial to evaluate its success, they will use measurements and
interventions that are easy for them and which help them interpret the causal
effect estimated in their context. For example, different school districts
measure verbal ability using different tests, and at different times in the life
of a child: some use Test A in Kindergarten, others Test B in 3rd grade. The
school districts have contracts with the makers of those tests and/or the tests
are chosen at the level of the U.S. State. To implement the same test at the
same time for thousands of children across districts dramatically increases the
cost of a study and provides unclear information within localities which have
processes already existing.

Q: What might prevent use of a result?

A: City A would need to be convinced that the kinds of people that the
intervention aims to help were not harmed and in fact benefited from the
intervention even if people benefited on average. For example, some
jurisdictions make racial equity a criteria for policy interventions. A finding
that, on average, people benefited but people of color did not benefit, would
prevent the use of the result.  Above and beyond the subgroup specific effects,
City A might also need to claim a kind of "no harm" expectation when building a
coalition to support the new policy.

The preceding fake conversation reveals that concerns about causal
models/mechanisms for interventions, concerns about distributional consequences,
and concerns about local implementation possibilities could all prevent the use
of a given piece of evidence by policy makers.

Policy makers have implicit (or explicit) causal models relating interventions
to outcomes. For example, Figure~\ref{fig:theory2} shows a stylized causal model
that a policy maker might have of kindergarten readiness in their own city (thus
no $\boxed{S}$ below). The coaching intervention might improve kindergarten
readiness, but so might addressing Family SES, Neighborhood Poverty, Teacher
Quality, or Classroom sizes.

\begin{figure}[H]
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

Before hearing about the coordinated coaching study, the policy makers in City A
might not have had the "Home Language Environment Quality" as a part of their
causal model. But upon hearing about the study, they might be willing to
elaborate their causal model to add new elements to it. For example, they might
be willing to believe that the intervention caused the outcome in the other
cities given the benefits of transparency and coordination mentioned earlier.

Once the new element is added to the causal model, questions about
implementation and distribution arise.  Should they implement the coaching
approach that appears promising from a study that ensured that all of the
coaching interventions were done the same way across multiple cities? City A
might do so only if they could imagine a plausible mode of implementing that
coaching intervention (where "plausible" means not creating political conflict,
and not costing more than intervening in any of the other parts of the causal
model). For example, if home visiting nurses were the coaches in the cities in
the coordinated study, and if City A had an active home visiting nurse program
for low income families, the implementation of the program in City A might
appear easier and plausible. However, if City A had decided long ago to not use
home visiting nurses, and provided similar services in a different way, then
City A might find the results of the coordinate study less relevant.

Imagine the City A did have a home visiting program that aimed to support low
income families --- in City A, imagine that these people were mostly
agricultural workers. But the coordinated study did not
report results for such people. City A would then wonder about whether the
positive result from the coordinated study would be useful for its population.

Further, imagine that results from the coordinated experiment were broken down
within each city by income and type of employment. The decision makers in City A
would ask whether coaching from nurses in City A would have the same kinds of
effects as they would in the other Cities. Would living in apartment buildings
change the effect? Or would home language matter? Would family structure matter?
Causal mechanisms operate in a context.

So, what is the benefit of the coordinated experiment for the policy makers in
City A? It appears to be mostly to encourage them to add an element to their
causal model. It could also encourage them to build their own intervention
inspired by the results of the coordinated experiment, and perhaps even to have
their own evaluation of their own new intervention. However, there are many
barriers between a report from a coordinated experiment and the implementation
of policy that appeared successful in other cities in City A.

# Discussion and next steps in evidence-based policy making

Coordinated studies and transparency practices help researchers add and remove
paths from their causal model. In turn, this kind of scientific consensus about
the nodes and paths of a model can help policy makers elaborate their own causal
models (often also known as "theories of change"). This appears to be one of the
most policy-relevant benefits of these studies from my current small set of
interviews and observations.

What else do policy makers need? Focused studies on key elements of the causal
model could help. They need not be coordinated, but should explicitly target a
causal pathway of interest to a policy-maker. Studies of variation in causal
effects across different contexts could also help policy makers judge the
relevance of any given finding for their jurisdiction.

What do we hope from the design of studies, coordinated or not? One hope is that
such studies would convince policy makers to update their prior beliefs. The
strongest such study would convince people who held beliefs that ran opposite to
the findings of the study. 



