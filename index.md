---
layout: default
title: AI Coding Manifesto
description: Best Practices for AI-Assisted Contributions in Open Source
---

{% capture manifesto %}{% include_relative AI_MANIFESTO.md %}{% endcapture %}
{% assign cleaned_content = manifesto | remove: '# AI Coding Manifesto' | remove: '### Best Practices for AI-Assisted Contributions in Open Source' %}
{{ cleaned_content | markdownify }}
