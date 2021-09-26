---
title: |
 | "Explanation, Generalization, Decision"
author:
 - Jake Bowers^[<jwbowers@illinois.edu> Thanks to Jim Kuklinski (University of
   Illinois), Carrie Cihak
   (King County, WA),
   James Diossa (The Policy Lab @ Brown)]
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

# What about politics?

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
readiness.




 two discussions with policy makers, I highlighted some efforts to
coordinate studies so as to increase scientific confidence in, say, the sign and
rough magnitude of some policy intervention.



# How might a single study help the city council?

## A single study done in a different context (different in place and/or time and/or covariates)?

## A single study done in a similar context (similar in place and/or time and/or covariates)?

## A single study done in a the same context (similar in place and/or time and/or covariates)?

# How might a coordinated study help the city council?



# Discussion and Additional Considerations



What else would policy makers like to know?

 - What is the evidence that the kinds of people I care about were not harmed by
   your intervention even if people benefited on average?
 - What is the evidence that the kinds of people I care about benefited from the
   intervention even if you detected no average effect?



I don't think they need an estimated
average treatment effect and confidence interval from a combined analysis of
multiple coordinated studies. Nor do I think they need the same kind of
information produced via some prediction or transportability function (where the
average treatment effect in one or more studies done in other places and times
are weighted using covariate information from the given place and given time so
as to predict how the average treatment effect would be estimated if the same
experiment(s) were executed there and then.) I do think that a scientific
consensus about the "theory of change" or causal mechanisms relevant to their
decision can help them. And I also think that evidence about the different paths
in the causal graph that represents this theory helps them: this is where
coordinated experiments come in. Coordinated studies help scientists to
establish a consensus about an mechanistic explanation for an outcome of
concern.^[Ideally, scientists and policy makers care about the same outcome and
have agreed on aspects of conceptualization and measurement of it.]

