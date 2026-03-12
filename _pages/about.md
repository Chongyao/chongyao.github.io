---
permalink: /
title: "Chongyao Zhao / 赵崇遥"
author_profile: true
---

<div class="sidebar sticky">
  {% include author-profile.html %}
</div>

<div class="page__inner-wrap">
  <section class="page__content" itemprop="text">
    <h2 id="publications">Publications</h2>
    
    <!-- Component Modes Synthesis Paper -->
    <p>
      <img width="178" align="left" src="{{ '/images/papers/component-modes.png' | relative_url }}" />
      <strong>Component Modes Synthesis Method with Multiple Partitions for Large-scale Eigenvalue Problem</strong><br />
      <strong>Chongyao Zhao</strong>, Junzhou Yin, Hujun Bao, Jin Huang<br />
      <em>SIGGRAPH 2026 Journal track (ACM Transactions on Graphics)</em><br />
      <!-- Add PDF links when available -->
    </p>
    
    <!-- Local Element Aggregation Paper -->
    <p>
      <img width="178" align="left" src="{{ '/images/papers/element-aggregation.png' | relative_url }}" />
      <strong>Local element aggregation for badly-shaped elements</strong><br />
      <strong>Chongyao Zhao</strong>, Junxi Zhang, Hujun Bao, Jin Huang<br />
      <em>ACM Transactions on Graphics (Under Revision)</em><br />
      <!-- Add PDF links when available -->
    </p>
    
    <!-- Cosserat Rods Paper -->
    <p>
      <img width="178" align="left" src="{{ '/images/papers/cosserat-rods.png' | relative_url }}" />
      <strong>Efficient and Stable Simulation of Inextensible Cosserat Rods by a Compact Representation</strong><br />
      <strong>Chongyao Zhao</strong>, Jinkeng Lin, Tianyu Wang, Hujun Bao, Jin Huang<br />
      <em>Pacific Graphics 2022 (Computer Graphics Forum)</em><br />
      <!-- Add PDF links when available -->
    </p>
    
  </section>
</div>
permalink: /
title: "Publications"
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}