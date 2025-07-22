---
title: 'Concurrency vs Parallelism - They are not the same!'
date: 2025-07-22
permalink: /posts/2025/06/blog-post-1/
tags:
  - cool posts
  - category1
  - category2
---


**Concurrency:**

Concurrency means an application is making progress on multiple task at the same time. While a single CPU core can handle only one task at a time, it achieves concurrency by rapidly switching between tasks.

Example: Listening to music while writting code. The CPU quickly switches between these task so efficiently that it feels like both are happening at once.

The primary goal of concurrency is to maximize CPU utilization by minimizing idle time.

**Parallelism:**

Parallelism means executing multiple task at the same time.

To achieve parallelism, task are broken down into smaller independent subtask and processed at the same time across multiple CPUs, cores, or GPUs.

Example: Training a deep learning model by splitting the data set into batches and processing each batch simultaneously across multiple GPUs.

The goal of parallelism is to boost processing speed by executing multiple task in parallel.

**They are not mutually exclusive**

-You can have concurrency without parallelism.

-You can have parallelism without concurrency.

-Or you can have both together for high performance system.


![conpa](https://github.com/user-attachments/assets/6841e335-dab7-4f15-b95a-d75a0fab02ae)
