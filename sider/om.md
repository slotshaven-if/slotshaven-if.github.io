---
title: Informatik C
description: '- IT-kompetancer'
published: yes
permalink: /om
---
## Indledning

## Om faget
Følger.

## Eksamen
[Læs mere om eksamen ↗️](sider/eksamen.md)

## Lokaler
Undervisning foregår i lokale 73 og nogle gange i værkstedet i kælderen.

## Læreplaner
Undervisningen følger Undervisningsministeriets læreplaner som kan findes her.

{% for item in site.data.links %}
{% if item.source == "uvm" %}

### {{ item.name }}

{{ item.description }}

[↗️ PDF]({{ item.link }}){:target="_blank" rel="noopener"}

{% endif %}
{% endfor %}

## Bogmærker
Se også [bogmærker]({% link sider/bogmaerker.md %}).
