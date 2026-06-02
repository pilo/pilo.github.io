---
layout: default
title: Home
---

# Hi, I'm Pilo

## F&B Procurement Manager | Operations Strategist | AI & Automation Expert

Specializing in automation, operational optimization, and AI application development for the food & beverage industry.

---

## Core Competencies

- **Procurement & Supply Chain**: Strategic sourcing, supplier management, cost reduction
- **Automation**: Python, purchase order scripts, API integrations
- **AI & Machine Learning**: NLP, predictive analytics, LLM integration
- **Operations**: Process optimization, data analysis, dashboard creation

---

## Featured Projects

{% for project in site.projects limit: 3 %}
### [{{ project.title }}]({{ project.url }})
{{ project.description }}
{% endfor %}

[View all projects]({{ site.baseurl }}/projects/)

---

## Contact

- **Email**: [your-email@example.com](mailto:your-email@example.com)
- **LinkedIn**: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)
- **GitHub**: [github.com/pilo](https://github.com/pilo)
- **Substack**: [your-substack.substack.com](https://your-substack.substack.com)
