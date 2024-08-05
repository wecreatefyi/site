---
# <meta name="author" content="{{ if .Params.author }}{{ .Params.author }}{{ else }}{{ range .Site.Author }}{{ . }} {{ end }}{{ end }}">
# <meta name="description" content="{{ if .IsHome }}{{ .Site.Params.homeSubtitle }}{{ else }}{{ if .Params.Description }}{{ .Params.Description }}{{ else }}{{ .Summary | plainify }}{{ end }}{{ end }}" />
# <meta name="keywords" content="{{ .Site.Params.keywords }}{{ if .Params.tags }}{{ range .Params.tags }}, {{ . }}{{ end }}{{ end }}" />s
title: "Hello World"
date: 2024-08-04T22:26:00-05:00
lastmod: 2024-08-05T22:18:59Z
draft: false
toc: false
author: test
---

Hello, world! We are WeCreate, a Hack Club centered in Oshkosh, Wisconsin. As we get started with our meetings, we will continue to update this site with chronicles of our adventures as a club!

<!-- ***
Written by Michael H, co-founder of WeCreate -->