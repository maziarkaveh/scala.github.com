---
layout: overview-large
title: Roadmap

disqus: true

partof: macros
num: 10
outof: 10
languages: [ja]
---

<span class="label warning" style="float: right;">EXPERIMENTAL</span>

**Eugene Burmako**

| Feature                                                                           | Scala 2.10         | [Macro Paradise](/overviews/macros/paradise.html)                                         | Scala 2.11   |
|-----------------------------------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------|--------------|
| [Blackbox/whitebox separation](/overviews/macros/blackbox-whitebox.html)          | No                 | No                                                                                        | No           |
| [Def macros](/overviews/macros/overview.html)                                     | Yes                | Yes                                                                                       | Yes          |
| [Macro bundles](/overviews/macros/bundles.html)                                   | No                 | No                                                                                        | Yes          |
| [Implicit macros](/overviews/macros/implicits.html)                               | Yes (since 2.10.2) | Yes                                                                                       | Yes          |
| [Fundep materialization](/overviews/macros/implicits.html#fundep_materialization) | No                 | Yes                                                                                       | Yes          |
| [Quasiquotes](/overviews/macros/quasiquotes.html)                                 | No                 | Yes                                                                                       | Yes          |
| [Type macros](/overviews/macros/typemacros.html)                                  | No                 | [Discontinued](http://scalamacros.org/news/2013/08/05/macro-paradise-2.0.0-snapshot.html) | No           |
| [Untyped macros](/overviews/macros/untypedmacros.html)                            | No                 | [Discontinued](http://scalamacros.org/news/2013/08/05/macro-paradise-2.0.0-snapshot.html) | No           |
| [Macro annotations](/overviews/macros/annotations.html)                           | No                 | Yes                                                                                       | No           |

At the moment, macro paradise is only available for 2.10.x compilers, but immediately after the official release of Scala 2.11.0, a version that supports 2.11.0 will be published.