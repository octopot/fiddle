---
code: null
id: I_kwDOIVugFs5VLLJQ
databaseId: 1428992592
number: 1
url: https://github.com/octopot/fiddle/issues/1
title: "core: concept"
issueType: null
labels:
  - "type: feature"
  - "scope: code"
  - "impact: high"
  - "effort: medium"
assignees:
  - kamilsk
milestone: null
parent: null
issueFields: {}
state: OPEN
stateReason: null
duplicateOf: null
createdAt: 2022-10-30T19:36:35Z
updatedAt: 2022-10-30T19:36:35Z
lastEditedAt: null
closedAt: null
---

# core: concept

**Motivation:** Feedly has an excellent paid feature - RSS Builder. It is helpful for me, and I want to make a proof of concept of something similar but publicly available.

<img width="1552" alt="image" src="https://user-images.githubusercontent.com/1165416/198897788-41d07a40-dccb-4a3e-a19a-9dd644e9e90b.png">

**Concept**

1. make static rss from https://blog.dopt.com/
    1. use github.com/PuerkitoBio/goquery as html parser
    2. define rss.yml as config
    3. dump rss to dist
4. define html with rss: fiddle.octolab.org/dopt/, etc
5. automate it by github action and add some checks
