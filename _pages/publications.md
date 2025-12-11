---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* Wang H, Guan, T., and Shang H. (2025), Interpretable additive model for analyzing high-dimensional functional time series, Journal of Multivariate Analysis. Accepted.


* Chakraborty, A. K., Miry, R., Greiner, R., Lewis, M. A., Wang, H., Guan, T., and Ramazi P. (2025), Deep Learning for Disease Outbreak Prediction: A parallel LSTM-CNN model, Journal of the Royal Society Interface}. In Press.


* Yan, Y., Vuong, Q., Metcalfe, R. K., Guan, T., Shi, H., and Park J.J. (2025), Target Aggregate Data Adjustment Method for Transportability Analysis Utilizing Summary-Level Data from the Target Population, Pharmaceutical Statistics. In Press.


* Yan, Y., Lin, R., Guan, T., Shi, H., and Lin, X. (2025), A Generalized Phase I/II Dose Optimization Trial Design With Multi‐Categorical and Multi‐Graded Outcomes,  Statistics in Medicine, 44 (7) e70049. 


* Cameron, R., Guan, T., Shi, H., and Lin, Z. (2025), Penalized Functional Regression Using R Package PFLR, Journal of Applied Statistics, 1 - 15. 


* Jia, S., Shi, H., and Guan, T. (2025), Function-on-Function Regression Models with Nonlinear Dynamic Effect and Linear Concurrent Effect, Statistics and Computing, 35 (2), Article 42.


* Guan, T., Ho, J., Krider, R., Cao, J., and Fogg, A. (2024). How Are Pre-Launch Online Movie Reviews Related to Box Office Revenues? Annals of Applied Statistics 18(2), 1686 - 1708.

* Guan, T., Sarkar S., and Swartz, T. (2024). Comparison of Individual Playing Styles in Football.  Journal of Quantitative Analysis in Sports. https://doi.org/10.1515/jqas-2024-0041.


* Guan, T. and Swartz, T. (2024). Acceleration and Age in Soccer. International Journal of Sports Science \& Coaching 19(3).


* Guan, T., Cao, J., and Swartz, T. (2023) Parking the Bus. Journal of Quantitative Analysis in Sports 19(4), 263 - 272.

* Guan, T., Nguyen, R., Cao, J., and Swartz, T. (2022). In-Game Win Probabilities for the National Rugby League. Annals of Applied Statistics 16 (1), 349 - 367.

* Guan, T., Lin, Z., Groves, K., and Cao, J. (2022). Sparse Functional Partial Least Squares Regression with Locally Sparse Slope Function. Statistics and Computing 32 (2), 30, 1-11.

* Xun, X., Guan, T., and Cao, J. (2022). Sparse Estimation of Historical Functional Linear Models with a Nested Group Bridge Approach.
The Canadian Journal of Statistics 50 (4), 1254 - 1269.

* Guan, T., Lin, Z., and Cao, J. (2020). Estimating Truncated Functional Linear Models with a Nested Group Bridge Approach. Journal
of Computational and Graphical Statistics 29 (3), 620 - 628. An R package *ngr* has been developed for implementing the proposed method.
ter

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
 {% include archive-single.html %}
{% endfor %}
