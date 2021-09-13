---
title: Title
---

# Introduction and Overview and Motivation

How can a policy decision maker use causal inferences reported from studies done in the past, in places dissimilar to her own jurisdiction?

More specifically, we ask, does coordination of studies help her? Should she prefer one study done in her own city (perhaps more or less recently) over studies done elsewhere (in cities like her own or unlike her own, in recent or more distance times, carefully coordinated in design and execution or more loosely summarized in a literature review)?

If current approaches to building the scientific consensus do not seem to directly benefit policy deciders, then what would? How might we make changes to the processes of policy evaluation and learning to help those who will design new policy interventions based on current scientific consensus (i.e. currently most well supported theories of change, explanations for causal mechanisms)?

We think that this focus on helping a decision maker (or a group of them) who are trying to make the best decision for a specific place and moment in time, helps not only improve the connection between academia and practitioners but also highlights some perhaps subtle changes in how academics themselves might reorient their own understanding about what a single study provides to knowledge and how coordinated studies might improve or accelerate such learning.

How can we help people improvise, create new policies well? How can we help people add to shared knowledge when they evaluate within their own cities?

# What we know so far about "transportability"

A fast growing body of work demonstrates what it takes to believe that the average causal effect of a treatment estimated in one place and time is a good inference about not only the true average causal effect at that place and time but at another place and time (cites to Baremboim, review article by Rose, Hartman work, etc..). This work has also been extended to cover the question of how to combine information from multiple studies using the same treatment and outcome and measuring the same covariates (cite at least to Baremboim and Pearl). Our overly brief summary of this literature is as follows. The question is what a city council or a mayor would do with this information when trying to make a decision:

Imagine that the theory of change for a given outcome can be drawn as a graph.  Here we are using the example where city leaders have decided to try to improve the kindergarten readiness of low income children.^[Note here the larger context. City leaders could focus on this task this year. Or another task. They probably focus on multiple tasks, but not every task. One would hope that a set of studies would be available for them to engage with most such tasks, a set built from the decades of work on a given general topic across academia, across the world.] A literature review enables them to sketch this theory of change as a graph with causal drivers of the outcome relating to one another as well as background factors that may or may not moderate the effects or change the distribution of the outcome in the city. 

GRAPH

The literature on transportability, with or without using the $do$-calculus, imagines that a causal driver, $Z$, was manipulated in city A, leading to an estimate, $\hat{\bar{\tau}}_A$ of the true average effect, $\hat{\tau} = (1/N) \sum_i \tau_i$ in city A (where the average effect is the average of the all of the individual level causal effects). We know that $\hat{\bar{\tau}}_A$ is a good estimate of $\bar{\tau}_A$ in city A, what does it tell us about city B? Baremboim and Pearl provide "transportability formulas" that enable us to convert the estimate from one city to another depending on differences in the graphs that determine both the causal mechanisms in both cities but also the processes by which the distributions of key variables differ between the cities. So, for example, the average effect of pre-school teacher training might differ between cities because, say, in one city the pre-school population is 3 and 4 years old while in another city it ranges from 2 to 3: this is because the $\tau_i$ for older children might be larger than the $\tau_i$ for younger children --- better teachers have a bigger impact on them (for example, hypothetically speaking). In such a case, the transportability formula would involve taking the estimated average effect in city A and reweighting by age distribution in city B. In that literature (and broadly others which involves perhaps non-parametric appraoches to using covariates measured in both city A and city B to predict how $\tau_i$ would differ between places and then average over the resulting predicted $\tau_i), the key is to have a sense for how covariates could change the treatment to outcome relationship and also how the distributions of the values of treatment, covariaets, and outcomes differ between the cities. 

So, that is one literature that aims to make better predictions about how a policy intervention might work out in a City B given information from a City A (or even from a series of studies done in multiple cities).

Another literature aims to tell us more directly about something like effect in theory: this is a literature most vividly shown by the EGAP metaketa initiative, where the same theoretically relevant graph is investigated using RCTs in different context where the outcome measurement and treatment mode is as similar as possible.

Coordinated experiments have the benefit of increasing precision about the estimation of a theoretical estimand --- and estimand that does not describe in detail the causal mechanism in any given place and time, but perhaps informs us about the sign or rough magnitude (big or small) of a relationships should a policy be implemented in a given place.

When does this help the decision maker?








 


