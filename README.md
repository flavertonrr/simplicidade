# flavertonrr/simplicidade [![Build Status](https://travis-ci.com/flavertonrr/simplicidade.svg?branch=master)](https://travis-ci.com/flavertonrr/simplicidade)

For example, see:

* [flaverton.com](https://flaverton.com)

## Podcast

To add podcast support, the [Plyr](plyr.io) player is used with familiar audio controls in podcast players. This support is added through the `PLAYER_ENABLE` variable.

The `CDN_AUDIO_URL` variable is the base URL for the CDN, which should hold all audio files in `mp3` and `ogg` format, preferably at the same folder level (all in the same)

```python
PLAYER_ENABLE=True
CDN_AUDIO_URL = 'https://cdn.flaverton.com/audio'
```

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
