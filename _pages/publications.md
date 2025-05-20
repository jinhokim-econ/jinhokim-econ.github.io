---
layout: page
permalink: /research/
title: Research
description: 
nav: true
nav_order: 2
---

<style>
h2 {
  margin-top: 40px;
  margin-bottom: 20px;
}
.accordion-content {
  margin-bottom: 30px;
  display: none;
  padding: 10px;
  border-top: 1px solid #ccc; /* 또는 그냥 지워도 됨 */
}
.accordion-button {
  background-color: transparent;
  color: var(--global-accent);
  padding: 10px;
  width: 100%;
  text-align: left;
  border: none;
  outline: none;
  cursor: pointer;
  font-size: 20px;
}
.accordion-button.active + .accordion-content {
  display: block;
}

</style>

<div class="accordion">

<h2> Working Papers</h2>

<div class="accordion-item">
  <button class="accordion-button"> Refinancing Inequality and Monetary Policy Implications (2024)</button>
  <div class="accordion-content">
      <em>Abstract:</em>
    I investigate the heterogeneous mortgage refinancing propensity across income groups and its effect on the refinancing channel of monetary policy. I document that low-income households refinance significantly less than high-income earners, a pattern referred to as “refinancing inequality.'' This suggests that the refinancing channel does not effectively serve households that are most likely to be liquidity constrained. Despite its importance, this pattern and its effect on the policy channel have been understudied in the literature. I demonstrate refinancing inequality by expanding the time scope and incorporating control variables previously unconsidered in existing studies. On average, the bottom quintile households exhibit less than half the probability of refinancing compared to the top quintile. I also highlight refinancing inequality in terms of timing, revealing that lower-income households face greater delays. The estimated potential savings through refinancing are substantial, particularly for low-income households, amounting to more than 10% of their income. Furthermore, I show that as household income decreases, refinancing activity in response to monetary policy shocks significantly declines. These results suggest that the aggregate effect of expansionary policy could be larger if refinancing frictions were mitigated.
  </div>
</div>

<div class="accordion-item">
  <button class="accordion-button"> The Effect of Mortgage Burdens on Households Consumption Response (2023)</button>
  <div class="accordion-content">
      <em>Abstract:</em>
I empirically examine the impact of liquidity constraints on household consumption responses, focusing on the role of mortgage burdens. Using data from the American Community Survey since 2005, I identify distinct responses among mortgagors—households characterized as “wealthy hand-to-mouth”—to monetary policy shocks. This identification leverages regional heterogeneity in mortgage-ownership ratios, which serve as a proxy for households likely constrained by liquidity and exhibiting a higher marginal propensity to consume. The findings reveal that U.S. metropolitan areas with higher mortgage-ownership ratios experience significantly larger consumption responses to monetary shocks but smaller housing wealth effects than other regions.
  </div>
</div>

<!-- 추가 워킹페이퍼 항목이 있다면 여기에 계속 추가 -->

<div style="margin-bottom: 30px;"></div>
<h2> Work in Progress</h2>

<div class="accordion-item">
  <button class="accordion-button">
    The Effect of Age on Expectations Bias and the Housing Cycle <br>
    <small style="font-size: 90%;">(with Yoonku Jo, Hyunseo Park, Jaeyoung Yoo)</small>
  </button>
  <div class="accordion-content">
    <em>Abstract:</em>
    We find that U.S. regions with a higher share of young people exhibit larger housing price cycles—a pattern also evident in international historical data. To explain this, we focus on how age shapes diagnostic expectations. Using data from the Michigan Survey, we show that the pattern of initial underreaction and subsequent overreaction in housing price growth expectations, as documented by Adam et al. (2024), is more pronounced among younger generations. We assess how this behavioral pattern amplifies housing market fluctuations and explore its macroeconomic implications in the context of demographic change
  </div>
</div>

<!-- 추가 워크 인 프로그레스 항목이 있다면 여기에 계속 추가 -->

</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const buttons = document.querySelectorAll(".accordion-button");
  buttons.forEach(btn => {
    // Always set accordion as active
    btn.classList.add("active");
    const content = btn.nextElementSibling;
    content.style.display = "block";

    // Add toggle on click
    btn.addEventListener("click", () => {
      btn.classList.toggle("active");
      const content = btn.nextElementSibling;
      content.style.display = content.style.display === "block" ? "none" : "block";
    });
  });
});
</script>