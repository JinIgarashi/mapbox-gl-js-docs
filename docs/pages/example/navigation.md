---
title: Display map navigation controls
description: Add zoom and rotation controls to the map.
topics:
  - Controls and overlays
thumbnail: navigation
contentType: example
layout: example
language:
- JavaScript
products:
- Mapbox GL JS
prependJs:
- "import Example from '../../components/example';"
- "import html from './navigation.html?code';"
- "import iframe from './navigation.html?iframe';"
---

Use [`addControl`](/mapbox-gl-js/api/map/#map#addcontrol) to add zoom and rotation controls to the map.

{{ <Example html={html} iframeSrc={iframe} {...this.props} /> }}
