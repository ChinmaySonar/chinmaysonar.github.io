---
layout: page
title: Master's Thesis
meta-title: Chinmay Sonar - Thesis
---

### Problems in Computational Social Choice on Restricted Domains

<a href= "https://chinmaysonar.github.io/Research/MTech_Thesis.pdf" target = "_blank">PDF</a> - <a href= "https://chinmaysonar.github.io/Research/MTech-Thesis-slides.pdf" target = "_blank">Slides</a>

<details open>
<summary>Abstract</summary>
<br>
Social Choice is the formalized study of the aggregation of individual preferences towardscollective decision making. The task of checking the feasibility of the preference aggregationschemes  in  the  real  world  context  comes  under  Computational Social Choice (COMSOC).In this thesis, we consider the problems from the three pillars of COMSOC - Voting,  FairDivision, and Matching under Preferences. 
<br>
<br>
Several appealing aggregation schemes turn out to be computationally hard.  The work fromthis thesis largely focuses on studying problems in these areas in the context of domain re-strictions.  We consider popular notions of domain restrictions such as Single-Peaked (SP), Single-Crossing (SC), and Euclidean preference domains.  The motivation for studying structured domains is to explore if certain properties that are elusive for in the general case can be achieved by considering appropriate and practically relevant domain restrictions.  For instance, some voting rules that are hard to compute in general become tractable on restricteddomains. Another illustration is that some domains admit mechanisms that are not vulnerableto strategic behavior.  We often find that simply projecting mechanisms for general domainsto structured domains does not give us enough leverage, so the quest is usually to design newmechanisms that take advantage of the specific structure of the domain under consideration.  
<br>
<br>

    - **Voting**: Our work in voting mainly focuses on the Chamberlin Courant (CC) voting rule. Several fundamental problems such as winner determination has been shown to be hard on for CC rule. We focus on the restricted and nearly restricted domains for this problem. Our work provides a fine-grained analysis of the boundary between tractability and intractability using parametric analysis. We also consider the effect of small perturbations in election instance formally captured by the concept of the robustness radius and provide an XP algorithms along with the matching hardness results.

    - **Stable Matching**: For many hard matching problems, we show that the hardness persists even the domain restrictions. We also provide an interesting addition to a class of instances which admit a unique stable matching (marriage for the bipartite case). We introduce a new variant of the matching problem called ’Matching Critical Sets’ and pin down the complexity of the same. Finally, we work on the special cases of (a,b)-supermatch. We also analyze the performance of the Gale-Shapley mechanism on instances with restricted domains through simulations.

    - **Fair Division**: We study fair allocation of indivisible items arranged on a path under the constraint that only connected subsets of items may be allocated to the agents. We study the problem for both Envyfreeness (EF1) and Equitability (EQ1). We show that achieving EF1 or EQ1 in conjunction with well-studied measures of efficiency (such as Pareto optimality, non-wastefulness, maximum egalitarian or utilitarian welfare) is computationally hard even for binary valuations. On the algorithmic side, we show that for any fixed ordering of agents, an Eq1 allocation with the highest egalitarian welfare among all consistent allocations can be efficiently computed. For structured binary valuations, we obtain polynomial-time algorithms for non-wasteful and pareto optimal EF1 and EQ1 allocations.
<br>

</details>

<!-- <Abstract open>

Social Choice is the formalized study of the aggregation of individual preferences towardscollective decision making. The task of checking the feasibility of the preference aggregationschemes  in  the  real  world  context  comes  under  Computational Social Choice (COMSOC).In this thesis, we consider the problems from the three pillars of COMSOC - Voting,  FairDivision, and Matching under Preferences.\

<br>

Several appealing aggregation schemes turn out to be computationally hard.  The work fromthis thesis largely focuses on studying problems in these areas in the context of domain re-strictions.  We consider popular notions of domain restrictions such as Single-Peaked (SP),Single-Crossing (SC), and Euclidean preference domains.  The motivation for studying structured domains is to explore if certain properties that are elusive for in the general case can be achieved by considering appropriate and practically relevant domain restrictions.  For instance, some voting rules that are hard to compute in general become tractable on restricteddomains. Another illustration is that some domains admit mechanisms that are not vulnerableto strategic behavior.  We often find that simply projecting mechanisms for general domainsto structured domains does not give us enough leverage, so the quest is usually to design newmechanisms that take advantage of the specific structure of the domain under consideration.
<br>

</Abstract> -->