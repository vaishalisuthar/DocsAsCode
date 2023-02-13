---
person: vaishali suthar
layout: templates
---

# Index File

Hello, I am {{page.person}} and trying to do handson using Markdown.

{% for item in site.data.chronology %}
- {{ item.name  }}, {{ item.year }}
{% endfor %}