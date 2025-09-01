---
layout: single
title: "Professional Experience"
permalink: /experience/
author_profile: true
---

{% for job in site.data.professional_experience.work %}
### {{ job.position }} — {{ job.company }}
**Location:** {{ job.location }}  
**Years:** {{ job.startDate }} – {{ job.endDate }}  

{{ job.summary }}

{% endfor %}
