---
layout: default
title: Ziqi Huang

publications:
  - title: "Graphon Mean Field Games with Control Constraints Dependent upon Network Control Mean Fields"
    authors: "Z. Huang and P. E. Caines"
    venue: "IEEE Conference on Decision and Control, April 2026 (Submitted)"

  - title: "Conformism-Individualism Trade-offs in LQG Graphon MFG with Control Mean Field Costs"
    authors: "Z. Huang and P. E. Caines"
    venue: "IFAC World Congress, Busan, Korea, August 2026 (Accepted)"
    pdf: "files/IFAC_20260519_m.pdf"
---

# Ziqi Huang 
I am a PhD student in the Department of Electrical and Computer Engineering at McGill University. 
My research interests include Graphon Mean Field Games (GMFG).  

## Publications

<ol>
{% for paper in page.publications %}
  <li value="{{ forloop.rindex }}">
    <strong>{{ paper.title }}</strong>
    {% if paper.pdf %}
      <a href="{{ paper.pdf | relative_url }}">[PDF]</a>
    {% endif %}
    <br>
    {{ paper.authors }}
    <br>
    {{ paper.venue }}
  </li>
{% endfor %}
</ol>

## Talks 
* Toward Graphon Mean Field Games with Control Couplings and Constraints
  <br> ISS Informal System Seminar, McGill University, Montreal, Canada, July 10, 2026 (Invited)

## Reviewer 
* Automatica
* IEEE Conference on Decision and Control (CDC) 
* IFAC Conference on Networked Systems (NecSys)

## Teaching Assistant 
* ECSE 509: Probability and Random Signal (Fall 2025)
* ECSE 501: Linear Systems (Fall 2025)
* ECSE 508: Multi-Agent Systems (Winter 2025)
