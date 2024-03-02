---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hello! My name is WeiQin (pronounced as WayChin) and I'm currently engaged as a post-doctoral researcher at the [Intelligent Automation Research Group](https://www.rmit.edu.au/about/schools-colleges/engineering/research/research-groups/intelligent-automation-research-group) at RMIT University, Australia. I received my Ph.D. in September 2022 from School of Engineering, RMIT University, mentored by [Prof. Alireza Bab-Hadiashar](https://www.linkedin.com/in/ali-bab-hadiashar-0a881a31/), [Prof. Reza Hoseinnezhad](https://www.linkedin.com/in/rezahn/) and [Dr Ruwan Tennakoon](https://www.linkedin.com/in/ruwan-tennakoon-923a3437/). My research focus on diverse areas including robust representation learning, domain adaptation and generalization, geometric computer vision, and more. I also contribute to the academic community as a reviewer for esteemed computer vision conferences and journals such as CVPR, ICCV, ECCV and IJCV.

<!-- My passion lies not only in advancing theoretical knowledge but also in applying these insights to solve real-world industrial challenges. This dual focus fuels my commitment to lifelong learning and continuous improvement in the realms of machine learning and computer vision. Outside the lab, I find joy in reading&#128214;, fishing&#127907;, and indulging in my love for coffee coffee&#9749;. -->

Thank you for stopping by to learn about my professional journey and interests. I'm always open to collaborative opportunities and discussions in the fields of ML and CV. Let's connect!



Publications
---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}