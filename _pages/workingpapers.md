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
**(Job Market Paper)** [2023 SIEP Prize]( {% /http://www.siepweb.it/siep/wp/en/premio-siep/ %} ) <br/>
<small>[ <a href="#/" onclick="visib('bunching')">Abstract</a> | [Draft][Turnover Elasticity] ]</small>


<div id="bunching" style="display: none; text-align: justify; line-height: 1.2" ><small>
Turnover is a key indicator of economic activity, but we know little about how much entrepreneurs adjust it as a response to taxation. This paper exploits a discontinuity in the Italian tax schedule of solo self-employed to study turnover responses to taxation. I consider the notch created by the eligibility cut-off of the preferential turnover tax scheme. I find substantial and significant bunching by solo self-employed below the turnover threshold. The effects of the tax scheme on bunching are heterogeneous across sectors, with professionals, business intermediaries and retailers having the largest observed responses. I estimate the turnover tax elasticity in these three sectors by focusing on the  marginal buncher. To do so, I build on Kleven and Waseem (2013) to develop a theoretical framework that fits the institutional set-up and rationalises the observed responses to it. Professionals have the largest turnover elasticity (0.066). Difference in compliance costs across regimes explains less than half of the observed responses, therefore highlighting the key role of low taxation for the observed bunching behaviour.
</small><br><br/></div>

[Turnover Elasticity]:{{ site.baseurl }}{% link assets/JMP_ALOSA.pdf %} 


**A Theory of Public Good Provision with Heterogeneous Risk Preferences**.  <br/>
<small>[ <a href="#/" onclick="visib('optimal-tax')">Abstract</a> | [Draft][Public Good] ]</small>


<div id="optimal-tax" style="display: none; text-align: justify; line-height: 1.2" ><small>
People with different attitudes to risk  have different views on the  extent to which society should invest in certain (risky) projects. This paper presents a theory of optimal provision of a (risky) public good when individuals have heterogeneous preferences for risk. The public good has an insurance purpose as it allows individuals to shift risk from private to public consumption. On the one hand, private provision of the public good is inefficient because people do not internalise the insurance gains of the other agents. On the other, public provision might fail to achieve the (ex-ante) first best outcome if agents cannot be targeted and compensated when the policy does not reflect their specific risk preferences. With an application on capital income and endowment taxation, this paper shows it is possible to improve welfare by   exploiting the different choices of the agents with different risk preferences. 
</small><br><br/></div>

[Public Good]:{{ site.baseurl }}{% link assets/Public_Good_Provision_with_Heterogeneous_Risk_Preferences_ALOSA.pdf %}

# <center> Work in Progress </center>

Estimating the Revenue Effects of Preferential Tax Regimes in Italy. <br/>
Social Choices with Heterogeneous Risk Preferences.  <br/>

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
