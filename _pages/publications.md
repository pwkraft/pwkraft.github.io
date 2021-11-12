---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Dissertation

**Tell Me What You Think: Leveraging Open-Ended Measures in Political Psychology**\\
_Committee_: Jennifer Jerit (chair), Stanley Feldman, Yanna Krupnikov, Michael Peress, Arthur Spirling (external member)

Though verbally expressing attitudes is one of the most ubiquitous ways people engage in politics, this basic feature of political life is rarely studied directly. Building on recent advances in automated text analysis, I develop new measures to systematically examine verbatim political attitude expression. By analyzing how citizens describe their beliefs and discuss them with peers, my research advances previous theoretical insights on the nature of political sophistication as well as the role of morality in politics and persuasion. The first part of the dissertation shows that the complexity with which people discuss political preferences, or their discursive sophistication, is a better predictor of political competence than factual knowledge alone. My measure of discursive sophistication furthermore suggests that---in contrast to previous findings in the literature---women are by no means less politically sophisticated than men. In the second part, I examine ideological differences in the contents of expressed attitudes. The analyses reveal systematic variation in the use of moral language between liberals and conservatives when talking about politics, a finding that is consistent with previous research in moral psychology. However, the reliance on morality is influenced by the degree to which people are exposed to moral rhetoric in the media. The third part of the dissertation investigates how the expression of moral considerations affects persuasion and attitude change in the context of online discussions. While moral appeals do not change people's minds across the board, those who hear arguments that are morally congruent with their preexisting attitudes are more likely to be persuaded. Overall, the dissertation advocates for a greater use of text-as-data and open-ended measures in the area of political psychology.

# Software

**ArfimaMLM: Arfima-MLM Estimation For Repeated Cross-Sectional Data** \\
R package version 1.3. ([Github](http://github.com/pwkraft/ArfimaMLM), [Documentation](../files/articles/ArfimaMLM-documentation.pdf)).
<!-- [CRAN](https://CRAN.R-project.org/package=ArfimaMLM) -->