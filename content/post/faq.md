+++
title = "FAQ"
description = ""
date = "2015-09-29"
categories = [ "example", "faq" ]
tags = [ "example", "faq" ]
+++

## What's this?

This is our very own digital corner of the internet. It's a [debian](https://debian.org/) VPS from [linode](https://linode.com/) running an [nginx](http://nginx.org/) reverse proxy to a [hugo](https://gohugo.io/) application server. More importantly, it's a space where we can publish content free of exploitation and censorship!

<!--more-->

## How do I start publishing content?

* Create content in [markdown](https://guides.github.com/features/mastering-markdown).
* Hugo markdown files start with [front matter](http://gohugo.io/content/front-matter/). For example:

```
+++
title = "FAQ"
description = ""
date = "2015-09-29"
categories = [ "example", "faq" ]
tags = [ "example", "faq", "blog" ]
+++
```

* Push content to our [git repo](https://github.com/nbdt/sensorium.space) in the /content/post directory.
* The web server will automatically pull the change and generate HTML.
