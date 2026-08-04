---
title: "The log-KDE method: Density estimates for positive data"
url: "https://blogs.sas.com/content/iml/2026/07/20/log-kde-positive-data.html"
date: "2026-07-20"
author: "Rick Wicklin"
feed_url: "https://blogs.sas.com/content/feed/"
---
A previous article discusses the problem of fitting a kernel density estimate (KDE) to data that are strictly positive. If you use a standard KDE, the resulting density curve might estimate non-zero probability for negative values. This is unsatisfactory because quantities like lengths and mass cannot be negative.
