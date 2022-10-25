---
title: keywords
date: 2022-10-25
---
- [Auszeichnung](#auszeichnung)
  - [Keyword-Titel](#keyword-titel)
    - [ts\_meta\_keywords\_heading](#ts_meta_keywords_heading)
  - [Keywords](#keywords)
    - [ts\_meta\_keyword](#ts_meta_keyword)
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

Keyword-Blöcke bestehen aus einem Keyword-Titel und den Keywords selbst.

## Keyword-Titel
### ts\_meta\_keywords\_heading
Der Paragraph, in dem der Keyword-Titel steht, wird mit **ts\_meta\_keywords\_heading** ausgezeichnet.

Ihm folgt der Paragraph, in dem die Keywords stehen.
![Tagging - ts_meta_keywords_heading](/forms/img/tagging-ts_meta_keywords_heading.jpg)

## Keywords
### ts\_meta\_keyword
Die Keywords werden mit **ts\_meta\_keyword** ausgezeichnet:
![Tagging - ts_meta_keyword](/forms/img/tagging-ts_meta_keyword.jpg)

# Mapping
## PDF
![PDF - ts_meta_keyword](/forms/img/pdf-ts_meta_keyword.jpg)
## TeX
```tex
\tpKeywordsTitle{Keyword-Titel}
\tpKeywords{Open Science Principles, Open Access, Digital Methods, Open Software, Open Source}
```
## HTML
```html
<h2 class="tsmetakeywordsheading">Keyword-Titel</h2>
<p class="tsmetakeyword">
    Open Science Principles, Open Access, Digital Methods, Open Software, Open Source
</p>
```
## EPUB
```html
<h2 class="tsmetakeywordsheading">Keyword-Titel</h2>
<p class="tsmetakeyword">
    Open Science Principles, Open Access, Digital Methods, Open Software, Open Source
</p>
```
## BITS (XML)
```xml
<kwd-group>
    <kwd>Open Science Principles</kwd>
    <kwd>Open Access</kwd>
    <kwd>Digital Methods</kwd>
    <kwd>Open Software</kwd>
    <kwd>Open Source</kwd>
</kwd-group>
```
## TEI (XML)
## Atypon (XML)
## Manifold