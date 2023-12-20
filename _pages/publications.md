---
title: ""
permalink: /publications/
author_profile: true
---
**J: Journal; C: Conference**

_Any publications currently under review without a preprint provided will be available in peer-reviewed manuscripts or preprints after the reviewing process, as per the submission requirements by the venues._

## 2023 ##
<ul>
  <li>(Under Review) [J1] <b>Qiangeng Yang</b>, Yoo Jin Chung, Juliana Fernandes, Daniela Oliveira<br>
    <b>Does Social Media Labeling Help with Content Moderation? An Analysis of State-Affiliation and Sentiment Labels on Twitter</b><br>
    <i>Mass Communication and Society</i>, 2023
    <ul>
      <li>Subject: the effects of sentiment labels and state-affiliation labels on the recognition and behavior of users on Twitter.</li>
      <li>Methods: user study, controlled experiments, ANOVA test</li>
      <li>Takeaways:<br>
        <ul>
          <li>State-affiliation labels and negative sentiment labels are more likely to cause negative effects on young people.</li>
          <li>Positive sentiment labels are more likely to have positive effects on the general population.</li>
        </ul>
      </li>
    </ul>
  </li>
  
  <li>(Under Review) [C1] Tess Christensen, Mirela Silva, Shlok Gilda, <b>Qiangeng Yang</b>, Daniel Capecci, Daniela Oliveira<br>
    <b>The Use of Social, Behavioral, and Economic Theories in Human Factors Phishing Research</b><br>
    <i>ACM Computing Surveys</i>, 2023
      <ul>
        <li>Subject: the level to which the existing publications regarding phishing leveraged the theories of behavioral science.</li>
        <li>Methods: systematic literature review, qualitative coding and analysis</li>
        <li>Takeaways:<br>
          <ul>
            <li>Only a fifth of phishing studies leveraged SBE theories.</li>
            <li>More significant theories that may be crucial for developing anti-phishing solutions (e.g., decision-making and deception detection) were not paid enough attention to by researchers.</li>
          </ul>
        </li>
      </ul>
  </li>
</ul>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
