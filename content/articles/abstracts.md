---
title: abstracts
date: 2022-10-25
description: "Abstract-Blöcke bestehen aus einem Abstract-Titel und dem Abstract selbst."
---
- [Auszeichnung](#auszeichnung)
  - [Abstract-Titel](#abstract-titel)
    - [ts\_abstracts\_heading](#ts_abstracts_heading)
  - [Abstract](#abstract)
    - [ts\_abstracts](#ts_abstracts)
- [Mapping](#mapping)
  - [PDF](#pdf)
  - [TeX](#tex)
  - [HTML](#html)
  - [EPUB](#epub)
  - [BITS (XML)](#bits-xml)
  - [TEI (XML)](#tei-xml)
  - [Atypon (XML)](#atypon-xml)
  - [Manifold](#manifold)

# Auszeichnung

Abstract-Blöcke bestehen aus einem [Abstract-Titel](/articles/ts_abstracts_heading) und dem [Abstract](/articles/ts_abstracts) selbst.

## Abstract-Titel
### ts\_abstracts\_heading
Der Paragraph, in dem der Abstract-Titel steht, wird mit **ts\_abstracts\_heading** ausgezeichnet.

Ihm folgt der Paragraph, in dem das Abstract steht.
![Tagging - ts_abstracts_heading](/forms/img/tagging-ts_abstracts_heading.jpg)

## Abstract
### ts\_abstracts
Das Abstract wird mit **ts\_abstracts** ausgezeichnet:
![Tagging - ts_abstracts](/forms/img/tagging-ts_abstracts.jpg)

# Mapping
## PDF
![PDF - ts_abstracts](/forms/img/pdf-ts_abstracts.jpg)
## TeX
```tex
\tpAbstractTitle{Abstract-Titel}
\tpAbstract{Abstract mit Hervorhebungen}
```
## HTML
```html
<h2 class="tsabstractsheading">Abstract-Titel</h2>
<p class="tsabstracts">
    Abstract <em>mit</em> <strong>Hervorhebungen</strong>
</p>
```
## EPUB
```html
<h2 class="tsabstractsheading">Abstract-Titel</h2>
<p class="tsabstracts">
    Abstract <em>mit</em> <strong>Hervorhebungen</strong>
</p>
```
## BITS (XML)
```xml
<abstract>
    <title>Summary</title>
    <p>
        Abstract <italic>mit</italic> <bold>Hervorhebungen</bold>
    </p>
</abstract>
```
## TEI (XML)
## Atypon (XML)
## Manifold