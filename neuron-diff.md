---
date: 2020-07-03
---

# Differences from neuron

Cerveau uses [neuron v1](https://neuron.zettel.page/) underneath and as such behaves the same as neuron. However, there are also some differences you should be aware of:

* **Raw HTML** is unsupported. For security reasons, Cerveau will show the raw HTML in your zettel file as-is, without rendering it.
* v2 features unsupported
  * Only top-level Markdown files will be processed (not sub-directories)
  * [Plugins](https://neuron.zettel.page/plugins.html) are unsupported.

See also [[known-issues]] for some differences not listed here.
