---
layout: archive
title: ""
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
<small>[ <a href="#/" onclick="visib('bunching')">Abstract</a> | [Draft][Elasticity]  ]</small>


<div id="bunching" style="display: none; text-align: justify; line-height: 1.2" ><small>
Turnover is a key indicator of economic activity, but we know little about how much entrepreneurs adjust it as a response to taxation. This is because business taxation is usually based on profits, rather than turnover. This paper exploits the notch created by the eligibility cut-off of the preferential (turnover) tax regime for solo self-employed in Italy to study turnover responses to taxation. I find that solo self-employed bunch below the turnover threshold to be eligible for the preferential scheme. Effects are different in different sectors, with professionals and business intermediaries showing the largest responses. I estimate the turnover tax elasticity by focusing on the (last) marginal buncher. To do so, I adapt the models of Kleven and Waseem (2013) and Harju et al. (2019) to derive a modified indifference condition that fits the institutional set-up. 
</small><br><br/></div>


[Elasticity]:{{ site.baseurl }}{% link assets/WP1186.pdf %}

**Optimal Taxation and Public Good Provision with Heterogeneous Risk Preferences**.  <br/>
<small>[ <a href="#/" onclick="visib('optimal-tax')">Abstract</a> | [Draft][Public Good] ]</small>


<div id="optimal-tax" style="display: none; text-align: justify; line-height: 1.2" ><small>
People with different attitudes to risk  have different views on the  extent to which society should invest in certain (risky) projects. This paper presents a theory of optimal provision of a (risky) public good when individuals have heterogeneous preferences for risk. The public good has an insurance purpose as it allows individuals to shift risk from private to public consumption. On the one hand, private provision of the public good is inefficient because people do not internalise the insurance gains of the other agents. On the other, public provision might fail to achieve the (ex-ante) first best outcome if agents cannot be targeted and compensated when the policy does not reflect their specific risk preferences. With an application on capital income and endowment taxation, this paper shows it is possible to improve welfare by   exploiting the different choices of the agents with different risk preferences. 
</small><br><br/></div>

[Public Good]:{{ site.baseurl }}{% link assets/Public Good.pdf %}

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
