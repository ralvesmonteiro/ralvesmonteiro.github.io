---
permalink: /
title: ""
output: 
  html_document:
    includes:
       in_header: /_includes/GA_Script.html
---

## About me

I am an Economist (EP) at the IMF Institute for Capacity Development. 

My fields of interest are Macroeconomics, International Economics and International Finance.

I earned my PhD in economics from the University of Minnesota in 2024.

Disclaimer: This is my website. The views expressed herein are my own and do not necessarily reflect those of the International Monetary Fund, its Executive Board, or its management.

## Research

My Research Statement is available [here](/assets/papers/Research.pdf).

### Working Papers

{% for pub in site.data.WP_co %}
  **[{{pub.title}}]({{pub.link}}){:target="_blank"}** \
  (with {% for author in pub.coauthors %} {% if author.link %}[{{ author.name }}]({{ author.link }}){:target="_blank"}{% else %}{{ author.name }}{% endif %}{% unless forloop.last %}, {% endunless %}{% endfor %}) \
  *{{ pub.publication }}* 
  <!-- This applies apply the no-margins class to prev paragraph to remove margins -->
  {: class="no-margins"}
  <details>
      <summary>Abstract (click to expand)</summary>
      {{ pub.abstract }}
  </details>

  <!-- This creates line break to space out items; need the no-margins class also since this gets automatically wrapped with a <p> which by default has extra margins -->
  <br/>
  {: class="no-margins"}
{% endfor %}

{% for pub in site.data.WP %}
  **[{{pub.title}}]({{pub.link}}){:target="_blank"}** \
  *{{ pub.publication }}* \
  {% if pub.journal_link %}[Link]({{ pub.journal_link }}){:target="_blank"}{% endif %}
  <!-- This applies apply the no-margins class to prev paragraph to remove margins -->
  {: class="no-margins"}
  <details>
      <summary>Abstract (click to expand)</summary>
      {{ pub.abstract }}
  </details>

  <!-- This creates line break to space out items; need the no-margins class also since this gets automatically wrapped with a <p> which by default has extra margins -->
  <br/>
  {: class="no-margins"}
{% endfor %}

### Publications

{% for pub in site.data.publications %}
  **[{{pub.title}}]({{pub.link}}){:target="_blank"}** \
  (with {% for author in pub.coauthors %} {% if author.link %}[{{ author.name }}]({{ author.link }}){:target="_blank"}{% else %}{{ author.name }}{% endif %}{% unless forloop.last %}, {% endunless %}{% endfor %}) \
  *{{ pub.publication }}* \
  {% if pub.journal_link %}[Link]({{ pub.journal_link }}){:target="_blank"}{% endif %}
  <!-- This applies apply the no-margins class to prev paragraph to remove margins -->
  {: class="no-margins"}
  <details>
      <summary>Abstract (click to expand)</summary>
      {{ pub.abstract }}
  </details>

  <!-- This creates line break to space out items; need the no-margins class also since this gets automatically wrapped with a <p> which by default has extra margins -->
  <br/>
  {: class="no-margins"}
{% endfor %}

### Work in Progress

- Multiplicity in Discriminatory Price Auctions (with Stelios Fourakis)

- Demand Elasticity in Sovereign Debt Models

- Demand Elasticities and the Maturity Choice of Sovereign Debt

- The Case for Joint Debt (with Daniel Belchior)

---
## Teaching

### University of Minnesota, Twin Cities 
- ECON 4721 Money and Banking, Instructor: Summer 2023, [Syllabus](/assets/teaching/syllabus_4721.pdf)
- ECON 4261 Introduction to Econometrics, TA: Spring 2023
- ECON 4821 Public Economics, Instructor: Fall 2021, [Syllabus](/assets/teaching/syllabus_4821.pdf)
- ECON 1101 Introduction to Microeconomics, Instructor: Summer 2020
- ECON 8108 Macroeconomic Theory, TA: Spring 2020, [Materials](https://sites.google.com/view/ricardo-alves-monteiro/teaching/econ-8108?authuser=0) 
- ECON 8107 Macroeconomic Theory, TA: Spring 2020, [Materials](https://sites.google.com/view/ricardo-alves-monteiro/teaching/econ-8107?authuser=0)
- ECON 8106 Macroeconomic Theory, TA: Fall 2019, [Materials](https://sites.google.com/view/ricardo-alves-monteiro/teaching/econ-8106?authuser=0)
- ECON 8105 Macroeconomic Theory, TA: Fall 2019, [Recitation Notes](/assets/teaching/Notes_8105.pdf)

### Teaching in Lisbon
- Fall 2017 - Lead Instructor for Fundamentals of Financial Economics at ISEG - Lisbon School of Economics and Management, [Syllabus](/assets/teaching/syllabus_ISEG.pdf)
- 2012 - 2018: Teaching Assistant at Catolica Lisbon School of Business and Economics

## Contact

**E-mail** \
ralvesmonteiro [at] imf [dot] org \
ricardoalvesmonteiro [at] gmail [dot] com \
alves030 [at] umn [dot] edu 

**Twitter/X** \
[@RAlvesMonteiro](https://twitter.com/RAlvesMonteiro)

**Mailing Address** \
International Monetary Fund \
1900 Pennsylvania Ave., N.W. \
Washington, DC 20431
