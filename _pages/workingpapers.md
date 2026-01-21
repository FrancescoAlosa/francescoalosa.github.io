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


**Optimal Public Good Provision and Taxation with Heterogeneous Risk Preferences**.  <br/>
<small>[ <a href="#/" onclick="visib('optimal-tax')">Abstract</a> | [**New Draft** - December 2025][Public Good] ]</small>


<div id="optimal-tax" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper develops a theory of optimal public good provision when individuals have heterogeneous risk preferences, and derives optimal tax conditions in terms of sufficient statistics. When the public good is privately provided,  the risk allocation between  private and public consumption is inefficient because people do not internalise the insurance gains that the public good provides to other agents who have different preferences for risk. Then,  I study the optimal taxation of earnings, as well as risky and riskless capital income, when the public good is publicly provided, and agents also have heterogeneous labour productivities. The public good risk profile  depends on a weighted average of agents' consumption volatility, as the different tastes for risk are balanced at the societal level. The progressivity of the labour income tax schedule and the desirability of taxing riskless savings crucially depend on whether the government prioritises redistribution towards low-income individuals or highly risk-averse individuals. Unless aversion to risk is negatively related to labour productivity and income, a tension between equity and insurance motives arises.
</small><br><br/></div>

[Public Good]:{{ site.baseurl }}{% link assets/Public_Good_Provision_with_Heterogeneous_Risk_Preferences_ALOSA.pdf %}

# <center> Work in Progress </center>

The Wage and Mobility Effects of Working from Home  <br/> 
(joint with L. Khoury (University Paris Dauphine-PSL) and Y. Souidi (Institut des Politiques Publiques))  <br/>

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
