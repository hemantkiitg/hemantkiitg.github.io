---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}
{% else %}
  {% assign author = site.author %}
{% endif %}

{% if author.googlescholar %}
  You can also find my articles on <a href="{{author.googlescholar}}">my Google Scholar profile</a>.
{% endif %}

{% include base_path %}

<h1>Publications</h1>

<ul>
  <li>
    <a href="https://doi.org/10.1016/j.jbc.2021.101353" target="_blank" rel="noopener">
      Engineered variants of the Ras effector protein RASSF5 (NORE1A) promote anti-cancer activities in lung adenocarcinoma
    </a><br>
    <em>Journal of Biological Chemistry</em>, 2021.<br>
    A. Singh, A. Erijman, A. Noronha, <strong>H. Kumar</strong>, Y. Peleg, Y. Yarden, J.M. Shifman
  </li>

  <li>
    <a href="https://doi.org/10.1080/07391102.2021.1938683" target="_blank" rel="noopener">
      Structural and functional role of invariant water molecules in matrix metalloproteinases: a data-mining approach
    </a><br>
    <em>Journal of Biomolecular Structure and Dynamics</em>, 2021.<br>
    <strong>H. Kumar</strong>, S.K. Mandal, P. Gogoi, S.P. Kanaujia
  </li>

  <li>
    <a href="https://doi.org/10.1142/9789811211874_0006" target="_blank" rel="noopener">
      Chapter 6: Mutational effects
    </a><br>
    In: <em>Protein Interactions: Computational Methods, Analysis and Applications</em>, World Scientific, 2020.<br>
    <strong>H. Kumar</strong>, J.M. Shifman
  </li>
</ul>
