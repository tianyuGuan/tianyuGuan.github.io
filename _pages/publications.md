---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

1. Guan, T., Ho, J., Krider, R., Cao, J., and Fogg, A. (2024). How Are Pre-Launch Online Movie Reviews Related to Box Office Revenues? Annals of Applied Statistics 18(2), 1686 - 1708.

2. Guan, T., Sarkar S., and Swartz, T. (2024). Comparison of Individual Playing Styles in Football.  Journal of Quantitative Analysis in Sports. https://doi.org/10.1515/jqas-2024-0041.


3. Guan, T. and Swartz, T. (2024). Acceleration and Age in Soccer. International Journal of Sports Science \& Coaching 19(3).


4. Guan, T., Cao, J., and Swartz, T. (2023) Parking the Bus. Journal of Quantitative Analysis in Sports 19(4), 263 - 272.

5. Guan, T., Nguyen, R., Cao, J., and Swartz, T. (2022). In-Game Win Probabilities for the National Rugby League. Annals of Applied Statistics 16 (1), 349 - 367.

6. Guan, T., Lin, Z., Groves, K., and Cao, J. (2022). Sparse Functional Partial Least Squares Regression with Locally Sparse Slope Function. Statistics and Computing 32 (2), 30, 1-11.

7. Xun, X., Guan, T., and Cao, J. (2022). Sparse Estimation of Historical Functional Linear Models with a Nested Group Bridge Approach.
The Canadian Journal of Statistics 50 (4), 1254 - 1269.

8. Guan, T., Lin, Z., and Cao, J. (2020). Estimating Truncated Functional Linear Models with a Nested Group Bridge Approach. Journal
of Computational and Graphical Statistics 29 (3), 620 - 628. An R package *ngr* has been developed for implementing the proposed method.
ter

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
 {% include archive-single.html %}
{% endfor %}
