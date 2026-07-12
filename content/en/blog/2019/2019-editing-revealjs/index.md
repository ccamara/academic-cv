---
title: Editing revealjs from markdown
summary: ""
date: 2019-03-08
draft: true

# Featured image for cards/social
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: "Streets devoted to men and women in Barcelona. Source: Las calles de las mujeres, a Geochicas' project."

cover:
  image: ""
  position:
    x: 50
    y: 40
  overlay:
    enabled: true
    type: "gradient"
    opacity: 0.4
    gradient: "bottom"
  fade:
    enabled: true
    height: "80px"
  icon:
    name: "✨"

# Authors are matched to profiles in content/authors/
authors:
  - me

tags:
  - reveal.js
  - reports
  - markdown
  - Data Science

content_meta:
  trending: false
---

<!-- Tip: open with the why, then show results, code, and next steps. -->

In my previous post I explained...

In this one I will focus only one of the options: reveal.js and I will compare several ways to end up creating a nice presentation using reveal.js from a markdown text.
So with those requirements I continued my research and I got to know Reveal.js, which quoting from their repo is a

>A framework for easily creating beautiful presentations using HTML. Check out the live demo.
>
>reveal.js comes with a broad range of features including nested slides, Markdown contents, PDF export, speaker notes and a JavaScript API. There's also a fully featured visual editor and platform for sharing reveal.js presentations at slides.com.


## Reveal.js built-in markdown

Even though strictly speaking reveal.js file format is an html, it is also possible to use markdown for authoring content by adding a `data-markdown` attribute to any section, like this:

```
<section data-markdown>
	<textarea data-template>
		## Page title

		A paragraph with some text and a [link](http://hakim.se).
	</textarea>
</section>
```
Source: https://github.com/hakimel/reveal.js#markdown

However,

## Reveal.js built-in markdown (2)

In order to prevent very long files where configuration and content is mixed up, it is also possible to embed

## Reveal-md


## Hugo + Academic theme


Pros:



Cons:

* Does not allow

## Hugo + Reveal-hugo theme


## Reveal + Knitr
