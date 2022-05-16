---
layout: layouts/home.njk
title: Home
date: 2016-01-01T00:00:00.000Z
permalink: /
eleventyNavigation:
  key: Home
  order: 0
---

# Welcome - {{ locale }}

{% component 'Counter.svelte',
hydrate = true %}

This is a (modified)<sup>1, 2</sup> template for building a simple blog website with the [Eleventy static site generator](https://www.11ty.io), with deployment to [Netlify](https://www.netlify.com).

Includes [Netlify CMS](https://www.netlifycms.org) for WYSIWYG content editing, and [Netlify Forms](https://www.netlify.com/docs/form-handling) for processing your site's form data.

For more info on installation and usage, view the [original project repo]({{ pkg.repository.url }}) on GitHub, and find the [i18n-mod by @fubits here](https://github.com/fubits1/11ty-multilang-i18n).

---

> <sup>1</sup> In this fork, I only added the multi-language logic to the template.
> <sup>2</sup> This mod has been extended to show-case [Slinkity](https://slinkity.dev/)
