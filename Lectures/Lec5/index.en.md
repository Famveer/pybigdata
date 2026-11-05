---
lang: en
page_id: lec5
permalink: /Lectures/Lec5/
title: Lec5
parent: Lectures
nav_order: 5
layout: default
---

# Lecture 5: How Spark Runs: Partitions and Joins
{: .no_toc }

{: .summary}
>In this lecture, we will learn:
>
>* How Catalyst compiles a query: rules, cost and physical plan
>* Narrow and wide dependencies: predicting stages and tasks
>* A time model for a stage, and fault tolerance
>* Anatomy and cost of the shuffle, and partial aggregation
>* How many partitions: the read formula, repartition and coalesce
>* Join algorithms: cost, limits and how Spark chooses


### Slides

* <a href="./slides/teoria.html" target="_blank">**Slides**</a>
