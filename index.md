---
layout: default
title: Home
markdown: kramdown
---


# Causal Inference with Large-scale Observational Data in Practice: Industrial Tooling and Use Cases at Snap and Airbnb

## Abstract
Product launches and iterations are a critical driver of business success and growth, but understanding their causal impact can be challenging when randomized controlled trials (RCTs) are not an option due to the limitation and restrictions posed by, for example, marketing, privacy, user agreement and sometimes engineering. Even when it is possible to run RCTs, issues like interference and compliance often lead to designs with low statistical power and prohibitively costly RCT. As a result, we face a growing need for applying causal inference methods and tooling to isolate the signal from noise, both in combination with quasi-experimental data and observational data.

Causal inference beyond randomization has a long history in academia. However, there are two significant challenges in applying observational causal inference methods from statistics and econometrics in industry: scalability and democratization. To overcome these challenges, scalable tooling and clear guidelines are required. This tutorial aims to cover observational causal inference methods and their applications at Airbnb and Snap, as well as the challenges involved in applying these methods in tech companies in general. The tutorial will also discuss the deployed ecosystems at Airbnb and Snap. Additionally, this tutorial will use real-world use cases to demonstrate how to formulate business questions within a causal inference framework and how such questions are tackled by using the in-house scalable tools that Snap and Airbnb have built.

Audience of this tutorial will learn a wide range of concepts and techniques for observational causal inference and quasi-experiments from matching, balancing, weighting, instrument variable to Bayesian regression and structural time series methods. Audience will also get familiar with engineering solutions to democratize and make causal inference scalable and approachable to business stakeholders beyond data scientists and researchers. Case studies in Airbnb and Snap would inspire the audience with challenging business problems, novel applications and real business impact.


## Outline

1. Introduction Causal inference with observational data methods at Airbnb and Snap (30min)
2. Deployed System at Airbnb (20min)
3. Airbnb Case Study (40min)
4. Deployed System at Snap (20min)
5. Snap Case Study (40min)
6. Panel Discussion and Q&A (30min)


## Speaker Bio

### Airbnb

__Anna Matlin__ is a data scientist on the Core Data Science team at Airbnb. Prior to Airbnb, Anna obtained a BSE from Princeton in Operations Research and Financial Engineering in 2017. Anna’s research interests lie at the intersection of causal inference and machine learning. Since joining Airbnb, Anna’s primary areas of focus have included observational causal inference tooling, experimentation for search ranking experiments, and optimizing cloud spend.

__Yufei Wu__ is a data scientist on the Marketing Technology Team at Airbnb, where she specializes in measuring marketing effectiveness through causal inference methods, in combination with both quasi-experimentation and observational data. She received her Ph.D. in Economics from MIT. Prior to Airbnb, Yufei worked as an economic consultant at Cornerstone Research, where she conducted structural modeling and econometric analysis to support high-profile antitrust litigation and merger review, such as the T-Mobile/Sprint Merger. Yufei’s research interests encompass a range of topics in causal inference and economic modeling, with a current focus on geo-based experimentation and Bayesian structural modeling.


__Alex Deng__ is on the Core Data Science team at Airbnb, focusing on causal inference, data science tooling and infra, as well as ML and Algorithm experimentation and measurement. Prior to Airbnb he worked on Microsoft Analysis and Experimentation and Azure Machine learning. His research interests span many areas of causal inference, online experimentation, Bayesian optimization, reinforcement learning, recommender systems and high throughput distributed computing. He regularly published his work in conferences like KDD, theWebConf(WWW), WSDM.


### Snap

__Meng Xu__ works on the Applied Research team at Snap Inc., focusing on causal inference with observational data. She received her Ph.D. from the Department of Economics, University of California at Los Angeles in 2018, and subsequently joined Snap Inc.. Her research interests lie in causal inference with an emphasis on balancing approaches for binary and continuous treatment, synthetic control, causal mediation analysis, causal machine learning, selection problem in randomized control trials, quantile regression, and variance reduction.

__Xi Zhang__ is a software engineer on the Applied Research team at Snap Inc., focusing on building quick prototypes and tooling for research scientists in a scalable fashion. Before joining the Applied Research team, she was one of the early team members on the experimentation platform at Snap Inc. and specializes in large-scale data processing pipelines.

__Sicheng Lin__ is an applied data scientist on the Applied Research team at Snap Inc. His research interest is scalable causal inference and ML tooling, adaptive experimentation and user modeling. At Snap, he has worked on scalable balancing approaches, multi-armed bandit for AB testing and user behavior sequential modeling, etc. He received his Ph.D. from the Department of Physics, New York University.

__Xiaolin Shi__ is Head of Applied Research at Snap Inc., where she leads a team of scientists and engineers with expertise in causal inference, statistics, data mining and scalable machine learning. Prior to Snap, Xiaolin worked at Microsoft Bing, Microsoft Research and Yahoo Research. Her research interests span areas including causal inference, experimentation, user modeling and network science.


<!-- <div class="posts">
  {% for post in paginator.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div> -->

<!-- <div class="pagination">
  {% if paginator.next_page %}
    <a class="pagination-item older" href="{{ site.baseurl }}page{{paginator.next_page}}">Older</a>
  {% else %}
    <span class="pagination-item older">Older</span>
  {% endif %}
  {% if paginator.previous_page %}
    {% if paginator.page == 2 %}
      <a class="pagination-item newer" href="{{ site.baseurl }}">Newer</a>
    {% else %}
      <a class="pagination-item newer" href="{{ site.baseurl }}page{{paginator.previous_page}}">Newer</a>
    {% endif %}
  {% else %}
    <span class="pagination-item newer">Newer</span>
  {% endif %}
</div> -->

