# flavertonrr/simplicidade [![Build Status](https://travis-ci.com/flavertonrr/simplicidade.svg?branch=master)](https://travis-ci.com/flavertonrr/simplicidade)

For example, see:

* [flaverton.com](https://flaverton.com)

## Sitemap.xml

Add `sitemap.xml` based on template `sitemap.html`, you need add `sitemap` value in `DIRECT_TEMPLATES` to render. 

```python
DIRECT_TEMPLATES = ('index', 'tags', 'categories', 'archives', 'sitemap')
SITEMAP_SAVE_AS = 'sitemap.xml'
```

## Site.json

Add support to [Typo Shot](https://github.com/flavertonrr/typo-shot) based on template `sitejson.html`, you need add `sitejson` value in `DIRECT_TEMPLATES` to render. 

```python
DIRECT_TEMPLATES = ('index', 'tags', 'categories', 'archives', 'sitejson')
SITEJSON_SAVE_AS = 'site.json'
```
