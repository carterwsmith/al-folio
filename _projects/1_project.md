---
layout: page
title: Bad Luck Metric
description: quantifying matchup inequalities in fantasy football
img: assets/img/ekeler.jpeg
importance: 1
category: code
---

**See the full project and source code on <a href="https://github.com/carterwsmith/ffl-badluck">GitHub</a>.**

My 2021 fantasy football season was one for the books. Over 1900 points scored over 14 weeks, the most in the league, with no trades made. The result: a ninth place finish. **Out of ten.**

<div class="row">
    <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/allen.jpeg" title="Josh Allen" class="img-fluid rounded z-depth-1"%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ekeler2.jpeg" title="Austin Ekeler" class="img-fluid rounded z-depth-1"%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/godwin.jpeg" title="Chris Godwin" class="img-fluid rounded z-depth-1"%}
    </div>
</div>
</div>
<div class="caption">
    <i>Thank you to these three studs for keeping me out of last place and allowing me to keep my hair.</i>
</div>

If you have never played fantasy football, especially in a league of highly competitive friends, you will not understand my pain. Still, I encourage you to keep reading.

This motivated me to find mathematical proof that I was being disproportionately screwed out of a championship-caliber season. I was lead to create an algorithm with a simple goal in mind–to quantify each team's 'luck' with the randomly assigned matchups each week.

<div class="row justify-content-sm-center">
        {% include figure.html path="assets/img/metric.png" title="OG Metric" class="img-fluid rounded z-depth-1" %}
</div>
<div class="caption">
    <i>The first (not final) draft of the metric.</i>
</div>

This turned from a simple equation into an extensible Python library, complete with visualizations, usable on any year of any ESPN fantasy football league. 

And, what do you know, a normalized distribution of my 'bad luck metric' revealed that I was in fact among the 100th percentile. 😅