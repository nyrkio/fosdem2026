# WIP: Continuous Performance Engineering

## Slides and material for Henrik's talk at Fosdem 2026 - Continuous Performance Engineering HowTo

Update: Uploaded 99% ready materials for tomorrows talk. Thanks to everyone for the feedback and encouragement.

Also uploaded a longer version which cannot possibly fit into 30 minutes. Will do some kind of "directors cut" or maybe a series of webinars after Fosdem.

Fosdem verision: https://github.com/nyrkio/fosdem2026/blob/main/Fosdem%202026_%20Continuous%20Performance%20Engineering%20HowTo%20(bw%20short).pdf

Directors cut version: https://github.com/nyrkio/fosdem2026/blob/main/Continuous%20Performance%20Engineering%20HowTo%20(bw)%20-%20Long%20Directors%20Cut.pdf


If you are reading this you are welcome to help. Communication channels:

* This repository.
   * Pull requests, issues, discussions are enabled
* Social
   * https://twitter.com/h_ingo
   * https://www.linkedin.com/in/heingo/?_l=en_US


## The talk

The talk is on Sunday in the Software Performance devroom: https://fosdem.org/2026/schedule/event/YNB7KR-continuous-perf-engineering/

Abstract:

In the past 30 years we've moved from manual QA testing of release candidates to Continuous Integration and even Continuous Deployment. But while most software projects excel at testing correctness, the level of automation of performance testing is still near zero. And while it's a given that each developer writes tests for their own code, Performance Engineering remains the domain of individual experts or separate teams, who benchmark the product with custom tools developed in house, often focusing on beta and release candidates, with zero performance tests happening in the Continuous Integration work stream.

This talk is your guide to Continuous Performance Engineering, aka Continuous Benchmarking. We will cover standard benchmarking frameworks and how to automate them in CI, automating deployments of large end-to-end environments, how to tune your infrastructure for minimum noise and maximum repeatability, and using change point detection to automatically alert on performance regressions with a minimal amount of those annoying false positives.


## Credits

Social media image: https://www.flickr.com/photos/fcrippa/9174011399/ Francesco Crippa

