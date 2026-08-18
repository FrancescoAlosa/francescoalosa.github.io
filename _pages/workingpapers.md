---
layout: archive
title: "Research"
permalink: /workingpapers/
author_profile: true
---

{% if author.googlescholar %}
 You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

# <center> Working Papers </center>
- - -

**Estimating the Elasticity of Turnover from Bunching: Preferential Tax Regimes for Solo Self-employed in Italy**.  <br/>
[SIEP Prize 2023](http://www.siepweb.it/siep/wp/en/premio-siep/)  <br/>
<small>[ <a href="#/" onclick="visib('bunching')">Abstract</a>  | [Draft][Turnover Elasticity] ]</small>


<div id="bunching" style="display: none; text-align: justify; line-height: 1.2" ><small>
To stimulate entrepreneurship, several countries adopt size-dependent regimes that tax businesses on the basis of turnover rather than profits. This paper investigates to what extent such regimes can affect sales turnover by exploiting a discontinuity in the tax schedule of Italian solo self-employed.  I consider the notch created by the eligibility cut-off of the preferential turnover tax scheme. I find substantial and significant bunching below the turnover threshold, as some solo self-employed choose the turnover tax scheme over the profit-based tax regime. The effects of the turnover tax scheme on bunching are heterogeneous across sectors, with professionals, business intermediaries and retailers having the largest observed responses. For these three sectors, I estimate the turnover tax elasticity by exploiting a new theoretical framework that fits the  institutional set-up and rationalises the observed responses to it. The baseline estimates for the two most productive sectors, professionals and business intermediaries, are 0.071 and 0.058 respectively.  Lower compliance costs in the turnover tax regime explain less than half of these responses, therefore highlighting the key role of low taxation for bunching behaviour in high-value-added sectors.
</small><br><br/></div>

[Turnover Elasticity]:{{ site.baseurl }}{% link assets/Estimating_the_elasticity_of_turnover_april2025.pdf %} 

**The Wage and Mobility Effects of Remote Work**  <br/> 
joint with Laura Khoury (University Paris Dauphine-PSL)   <br/>
<small>[ <a href="#/" onclick="visib('wfh')">Abstract</a> | [**New** - February 2026][wfh] ]</small>

<div id="wfh" style="display: none; text-align: justify; line-height: 1.2" ><small>
The shift to remote work, with roots predating Covid-19, marks a major transformation of labor markets. This paper investigates its medium-run impact on workers' labor market outcomes, exploiting plant-level variation in remote work agreements implemented between 2014 and 2017 in France. Using an event study design and rich administrative data, we find that access to remote work yields moderate wage increases and facilitates geographical mobility with increases in commuting distance. Examining mechanisms, we find that workers moving to new plants that also have adopted remote work experience larger increases in commuting distance, along with upward occupational mobility. This pattern suggests that remote work options alleviate job search constraints, allowing workers to seek higher-paying and possibly higher-ranked jobs. Our analysis further reveals that plant-level remote work agreements raise firm productivity, benefiting both incumbent and newly hired workers. Overall, our results underscore how remote work reshapes labor market trajectories through its effects on mobility, job search, and productivity. 
</small><br><br/></div>

 [wfh]:{{ site.baseurl }}{% link assets/Projet_WFH.pdf %} 
 
**Optimal Public Good Provision and Taxation with Heterogeneous Risk Preferences**.  <br/>
<small>[ <a href="#/" onclick="visib('optimal-tax')">Abstract</a> | [**New Draft** - July 2026][Public Good] ]</small>


<div id="optimal-tax" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper develops a theory of optimal public good provision and taxation when individuals differ by their labour productivities and risk preferences. Under private provision of public goods, there is an inefficient allocation of aggregate risk between private and public consumption, as individuals fail to internalize the insurance spillovers provided to agents with different risk attitudes. I then derive sufficient-statistic tax formulas under public provision. The optimal non-linear labour tax and the riskless return tax redistribute, respectively, across income levels and across risk aversion levels conditional on income, while internalizing fiscal externalities on capital tax bases. Both the progressivity of the labour income tax schedule and the sign of the riskless return tax depend on the joint distribution of income and risk preferences, and on the welfare weights used to compare agents with different risk preferences. A linear tax on risky excess returns plays an insurance role, balancing the different tastes for risk at the societal level. Finally, I characterize an alternative non-linear tax schedule on expected capital income: distorting portfolio choices can provide an additional margin for screening unobserved risk preferences.
</small><br><br/></div>

[Public Good]:{{ site.baseurl }}{% link assets/Optimal_taxation_and_Public_good_provision_july2026.pdf %}

# <center> Work in Progress </center>


Big-box Stores, Local Employment and City Shape  <br/> (joint with L. Khoury (University Paris Dauphine-PSL) and A. Lapierre (University Paris Dauphine-PSL)) <br/>

A Criterion to Evaluate Social Welfare when Risk Preferences are Heterogeneous.  <br/>

[//]: This java script is the button to show abstract
<script>
 function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>

[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>
