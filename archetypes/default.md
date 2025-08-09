---
title: "{{ replace .Name "-" " " | title }}"
description: "{{ .Name | humanize }} — concise 1–2 sentence summary for SEO & LLMs."
date: {{ .Date }}
draft: true
tags: []
categories: []
series: []
authors: ["State of Algorithms"]
outputs: ["HTML", "TXT", "JSON"]

# PaperMod options
ShowToc: true
TocOpen: false
ShowBreadCrumbs: true
ShowShareButtons: true
comments: false

# Social previews / Open Graph & Twitter
images: []
cover:
  image: ""
  alt: ""
  caption: ""
  relative: false

# Canonical URL if cross-posted
# canonicalURL: ""
---