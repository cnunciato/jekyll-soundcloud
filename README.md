jekyll-soundcloud
=================

A Jekyll plug-in for embedding SoundCloud sounds in your Liquid templates.

## Usage:

  {% soundcloud_sound 12345 %}
  {% soundcloud_sound 12345 widgetname %}
  {% soundcloud_sound 12345 widgetname ffffff %}
  {% soundcloud_sound 12345 widgetname ffffff small %}

  ... where 12345 is the SoundCloud sound ID, and widgetname is the sound's visual representation.

# Available SoundCloud widgets:
 
  html5 (default)
  flash *
  mini *
  artwork *
  
    * Requires a paid SoundCloud tier
