---
permalink: /
title: ""
---

## About me

I am a PhD candidate in economics at the [University of Minnesota](https://cla.umn.edu/economics){:target="_blank"}.

My fields of interest are Macroeconomics, International Economics and Public Finance. My advisors are [Manuel Amador](https://manuelamador.me){:target="_blank"} and [Tim Kehoe](http://users.econ.umn.edu/~tkehoe/){:target="_blank"}.

My CV is available [here](/assets/papers/CV_current.pdf).


## Research

### Working Papers


Marginal vs. Multiple: Debt Auctions with Strategic Interactions \
with [Stelios Fourakis](https://www.steliosfourakis.com){:target="_blank"}

{% for pub in site.data.WP %}
  **[{{pub.title}}]({{pub.link}}){:target="_blank"}** \
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

### Publications

{% for pub in site.data.publications %}
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

### Work in Progress

- The Case for Joint Debt (with Daniel Belchior)

- Demand Elasticity in Sovereign Debt Models

- Demand Elasticities and the Maturity Choice of Sovereign Debt

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
alves030 at umn dot edu \
ricardoalvesmonteiro  at gmail dot com

**Mailing Address** \
4-101 Hanson Hall \
1925 Fourth Street South \
Minneapolis, MN 55455
