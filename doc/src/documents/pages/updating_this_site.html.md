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
docpad install
```

You will probably want to make some changes and see them locally, but to do that you'll need to set the site URL with <code>docpad.cofee</code>:

```
site:
  # The production url of our website
  url: "http://localhost:9778"
  # url: "http://amilward.github.io/MDR"
```
Don't commit this, we'll roll this change back later!

Then to push the changes and deploy the site:

```bash
# reset the docpadd
git checkout -- docpad.cofee
git status
docpad deploy-ghpages --env static
git push
```