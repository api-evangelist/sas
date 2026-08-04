---
title: "Registering the whole pipeline, not just the model"
url: "https://blogs.sas.com/content/sgf/2026/07/30/registering-the-whole-pipeline-not-just-the-model/"
date: "2026-07-30"
author: "Thomas Wileman"
feed_url: "https://blogs.sas.com/content/feed/"
---
Most machine learning models produce a probability, but many times logic is applied to that prediction to produce a decision. That last logic step often lives in a downstream script disconnected from the model it depends on, easy to lose when the model is refreshed. Using the home equity (HMEQ) dataset, this post walks through a practical alternative in SAS Model Studio.
