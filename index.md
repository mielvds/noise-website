---
layout: page
title: Home
weight: 1
permalink: /
---
<div class="blog-index">  
{% assign post = site.posts.first %}
{% assign content = post.content %}
<div class="entry-title"><a href="{{ root_url }}{{ post.url }}">{{ post.date | date: "%b %-d, %Y" }} | {{ post.title }}</a></div>
</div>

Every Semantic Web researcher has been there: you spend days of work, but the results just don’t give the answer you were hoping for. The work ends up, like so many, part of the **File Drawer Effect**: they **never get reported** because of **negative or inconclusive outcome**. This occurs as a result of a publication bias towards positive results in Semantic Web, as in other fields. However, **negative or inconclusive results** are **fundamental** to the research process and can be as **valuable as positive results**.

This workshop provides a forum for such attempted approaches, methodologies, or implementations. Researchers are urged to report **null, disappointing or inconclusive attempts** in the Semantic Web and Linked Open Data research field. We specifically target sound approaches and, scientifically and technically relevant contributions, that produced negative or inconclusive experimental results.

We welcome submissions in, but not limited to, the following categories:

- **Applied research methodology** in the context of the Semantic Web and Linked Data that produces **unexpected, inconclusive, non-confirmatory or negative results**.
- **Mismatches between theoretical designs** (or properties) and **experimental results**.
  - Theoretical sound approaches that fail at implementation level, or
  - Approaches with wrong assumptions regarding Semantic Web technologies
- **Generality limitations** of solutions that help to advance the state of the art.
  - Solutions that only outperform the state-of the-art in a very specific context.
  - Papers that verify or refute results published in the past
  - Verified hypotheses from other areas (e.g., Databases, AI) that cannot be verified or equally good replicated using Semantic Web technologies
- **Novel groundbreaking ideas** related to Semantic Web technologies whose **implementation risks can not be estimated**.

Important Dates:

- Submission deadline: <del>March 15, 2015</del> March 22, 2015
- Notifications: April 14, 2015
- Camera ready version: April 20, 2015
- Workshop: June 1, 2015
