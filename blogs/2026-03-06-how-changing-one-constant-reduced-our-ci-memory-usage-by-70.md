---
title: "How Changing One Constant Reduced Our CI Memory Usage By 70%"
url: "https://coder.com/blog/how-changing-one-constant-reduced-our-ci-memory-usage-by-70percent"
date: "2026-03-06"
author: "Spike Curtis"
feed_url: "https://coder.com/api/rss.xml"
---
When you build developer infrastructure that thousands of engineers depend on, your own development environment has to hold up under pressure. At Coder, we use Coder to build Coder. That means our developers work on large shared machines with significant CPU and memory, and running Go's parallel test suite to shorten the inner code-test loop.
