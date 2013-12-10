---
title: Updating this docpad
layout: page
tags: ['intro','page']
pageOrder: 1
---
The contents of this docpad are published at http://amilward.github.io/MDR/.

To get up and running with a local instance, try this:

```bash
git clone git@github.com:OxBRCInformatics/ModelCatalogueDocumentation.git
cd ModelCatalogueDocumentation
git remote add target git@github.com:amilward/MDR.git
# do some cool stuff and commit it
```

Then to push the changes and deploy the site:

```bash
git status
docpad deploy-ghpages --env static
git push
```