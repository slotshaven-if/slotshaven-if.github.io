---
title: Informatik C
description: '- IT-kompetencer i en kompleks verden'
published: yes
permalink: /om
---
## Om faget
Følger.

## Faglige mål
Følger.

## Kernestof
Følger.

## Eksamen
[Læs mere om eksamen ↗️]({% link sider/eksamen.md %}).

## Læreplaner
Undervisningen følger Undervisningsministeriets læreplaner som kan findes her.

{% for item in site.data.links %}
{% if item.source == "uvm" %}

**{{ item.name }}** - {{ item.description }}\
[↗️ PDF]({{ item.link }}){:target="_blank" rel="noopener"}

{% endif %}
{% endfor %}

## Bogmærker
Se også [bogmærker]({% link sider/bogmaerker.md %}).
