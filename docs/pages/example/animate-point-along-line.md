---
title: Animate a point
description: Animate the position of a point by updating a GeoJSON source on each frame.
topics:
  - Layers
  - Sources
thumbnail: animate-point-along-line
contentType: example
layout: example
language:
- JavaScript
products:
- Mapbox GL JS
prependJs:
- "import Example from '../../components/example';"
- "import html from './animate-point-along-line.html?code';"
- "import iframe from './animate-point-along-line.html?iframe';"
---

This example animates the position of a point by updating a GeoJSON source on each frame.

It first defines the animation as a GeoJSON object. Then it adds a [GeoJSON source](/mapbox-gl-js/style-spec/sources/#geojson) referring to that GeoJSON, and adds a [circle layer](/mapbox-gl-js/style-spec/layers/#circle) that uses that source. 

Finally, it starts the animation with the JavaScript [`window.requestAnimationFrame()`](https://developer.mozilla.org/en-US/docs/Web/API/window/requestAnimationFrame) method to continuously update the GeoJSON object, resulting in a moving circle on the map.

{{ <Example html={html} iframeSrc={iframe} {...this.props} /> }}
