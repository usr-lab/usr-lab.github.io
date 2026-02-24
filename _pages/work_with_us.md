---
permalink: /work_with_us/
title: Work with us!
layout: splash

header: 
  overlay_color: "#000"
  overlay_image: "assets/images/group_picture_2022.jpg"
  overlay_filter: "0.5"
---

# Open positions
We are looking for a Postdoc in social robotics with focus on child-robot interaction: [Apply here](https://www.uu.se/en/about-uu/join-us/jobs-and-vacancies/job-details?query=903579) (last date to apply: 15th of April)

---

# Master's projects
The following is a list of project that our lab offers that can be expanded into e.g. a master thesis or an internship at the lab. More project may be available by contacting each member separately.

{% for collection in site.master-projects %}
  <h2> {{ collection.title }} </h2>
  {{ collection.description }}

  [More information and Apply]({{ collection.url }}){: .btn .btn--inverse}
{% endfor %}


<!-- ## Other projects
Additionally, feel free to contact any of the following members if you're intersted in doing a project in their research area. -->

