---
layout: challenges
---
# {{ site.challenges }}
## Test your expertise and learn new tricks with these challenges

<!--
<div class="challenge-item">
  {% include_relative challenges/question1.md %}

  <details class="challenge-solution">
    <summary>💀 Solution</summary>
    {% include_relative challenges/solution1.md %}
  </details>
</div>
-->

<div class="challenge-item">
  {% capture question1 %}
    {% include_relative challenges/question1.md %}
  {% endcapture %}
  {{ question1 | markdownify }}

  <details class="challenge-solution">
    <summary>Solution</summary>
    {% capture solution1 %}
      {% include_relative challenges/solution1.md %}
    {% endcapture %}
    {{ solution1 | markdownify }}
  </details>
</div>