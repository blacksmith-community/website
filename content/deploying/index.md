---
date: 2016-06-23T19:49:00-04:00
title: Deploying Blacksmith
---

## BOSH-lite

Deploying to BOSH-lite requires using cloud config

```
bosh target 192.168.50.4
https://github.com/cloudfoundry-community/blacksmith-boshrelease
cd blacksmith-boshrelease
templates/make_manifest
```