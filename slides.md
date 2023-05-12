---
theme: ./theme
title: "The Vue-niverse of SEO - Uncovering the Secrets"
website: lichter.io
handle: TheAlexLichter
favicon: https://lichter.io/img/me@2x.jpg
highlighter: shiki
lineNumbers: true
layout: intro
css: 'unocss'
transition: fade
---

---

<div class="text-center flex flex-col h-full items-center justify-center">

# <span class="text-orange-400">~8.6 billion</span> searches per day

<div class="mt-16" v-click>

## > 100k searches <span class="text-orange-400">per second</span>

</div>

</div>

---

<div class="text-center">

# But...

<div class="mt-18" v-click>

# What is the percentage of websites <br> that <span class="text-orange-400">actually get visitors</span> from Google?

</div>

<h1 v-click class="mt-18 font-bold !text-8xl v-click">
  Guess!
</h1>

</div>

---
transition: none
---

<div class="text-center">

# Not even <span class="text-orange-400">10%</span>!

<div v-click>

<img src="/ahrefs-study-content-organic-traffic.png" alt="Pie chart showing that more than 90% of all checked websites (> 1B) do not get any traffic from google" class="h-70 mx-auto">

[Source](https://ahrefs.com/blog/search-traffic-study/)

</div>

</div>

---
preload: false
---

<div class="text-center">

# Not even <span class="text-orange-400">10%</span>!

</div>

<img v-motion :initial="{x: 0, y: 0, scale: 1.0}" :enter="{x: -400, y: 400, scale: 8.0, transition: {delay: 250, duration: 750 }}" src="/ahrefs-study-content-organic-traffic.png" alt="Pie chart showing that more than 90% of all checked websites (> 1B) do not get any traffic from google" class="h-70 mx-auto">

---
layout: intro
---

# The <span class="text-[#41b883]"><logos-vue />ue</span>-niverse of SEO 🚀

## Uncovering the <span class="text-orange-400">Secrets</span>

### Vue.js Live 2023

<style>
  h1 {
    @apply !text-5xl;
  }

  h2 {
    @apply !text-3xl !mt-16 !mb-32;
  }

  h3 {
    @apply !text-base;
  }
</style>

---
layout: two-cols
heading: About me
---

<template v-slot:default>
<div class="flex flex-col justify-center items-center h-full">
<img
  class="w-75 rounded-full"
  src="https://lichter.io/img/me@2x.webp"
  />
  <h2 class="mt-4">Alexander Lichter</h2>
</div>
</template>

<template v-slot:right>
<VClicks class="space-y-2 mt-10 text-xl h-full">

* <mdi-account-check class="text-green-100" /> **Web Development Consultant**
* <mdi-microphone /> Speaker & Instructor
* <logos-nuxt-icon /> Nuxt.js Team
* <mdi-twitter class="text-blue-400" /> @TheAlexLichter
* <mdi-web /> [https://lichter.io](https://lichter.io)
* <mdi-github /> [manniL](https://github.com/manniL)

</VClicks>
</template>

---
layout: image
image: https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExOTQ3OTNkNDU5ZGI0MDY5OGE1ZTkxYmQ2NjU2NTI5MGVkODEzNDM5ZCZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/xT9IgusfDcqpPFzjdS/giphy.gif
---

<!--

Ready to Navigate through the cosmos of SEO?

-->

---
transition: none
---

# What is SEO?

* Rocket Science

---

# What is SEO?

* <span class="line-through">Rocket Science</span>

<VClicks>

* User-<span class="text-orange-400">focused</span>
* Easy to learn, hard to master
* Needs <span class="text-orange-400">continuous</span> improvements
* <span class="text-orange-400">Frequently</span> changing

</VClicks>

---

# When do I need SEO?

<VClicks depth="2">

* For the <span class="text-orange-400">public</span> parts of your project
    * Marketing pages, company & business sites
    * Forums, help databases & FAQs
    * Blogs / articles of any kind
* <span class="text-orange-400">Not relevant </span> for
    * Anything behind authentication
    * Short-lived content (less than a few days)


</VClicks>

---
transition: none
---

# SEO Galaxies

<div class="grid grid-cols-3 gap-4 mt-8">

<div class="mx-auto">

<VClick>

## On-page

</VClick>

<img v-click class="rounded-full h-32 my-8" src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExNzkzOTU3ZWQzY2I0MjJiMzhjYTVkOGRhMTYzYTdiY2IyMTZjMjdlZSZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/4ydWTcMBjimLbT1CHi/giphy.gif">

<VClicks>

* Content
* Keywords
* UX
* Meta tags

</VClicks>

</div>

<div class="mx-auto">

<VClick>

## Off page

</VClick>

<img v-click class="rounded-full h-32 my-8" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExZWQzMzQ1MTBjMmM4NTc2MjRhZDljMjcwNjIzODFhZjViYzYzMDZiNyZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/65Tr7aW4HJYdCHN082/giphy.gif">

<VClicks>

* Link building
* Social media
* Citations
* Authority

</VClicks>

</div>

<div class="mx-auto">

<VClick>

## Technical

</VClick>

<img v-click class="rounded-full h-32 my-8" src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMzMxYjQ0ZWEwN2RmYmNjN2RiYzYwMTNhMDJjMTgxOWQ3ZTM5MjkyYSZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/D35fOVm9gSQ91icJeR/giphy.gif">

<VClicks>

* Page Speed
* Security
* Broken Links
* Sitemap

</VClicks>

</div>

</div>

---
preload: false
---

# SEO Galaxies

<div class="grid grid-cols-3 gap-4 mt-8">

<div class="mx-auto">

## On-page

<img v-motion :initial="{x: 0, y: 0, scale: 1.0}" :enter="{scale: 8.0, transition: {delay: 250, duration: 750 }}" class="rounded-full h-32 my-8" src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExNzkzOTU3ZWQzY2I0MjJiMzhjYTVkOGRhMTYzYTdiY2IyMTZjMjdlZSZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/4ydWTcMBjimLbT1CHi/giphy.gif">

* Content
* Keywords
* UX
* Meta tags

</div>

<div class="mx-auto">

## Off page

<img class="rounded-full h-32 my-8" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExZWQzMzQ1MTBjMmM4NTc2MjRhZDljMjcwNjIzODFhZjViYzYzMDZiNyZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/65Tr7aW4HJYdCHN082/giphy.gif">

* Link building
* Social media
* Citations
* Authority

</div>

<div class="mx-auto">

## Technical

<img v-motion :initial="{x: 0, y: 0, scale: 1.0}" :enter="{ x: -300, scale: 16.0, transition: {delay: 1000, duration: 750 }}" class="rounded-full h-32 my-8" src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMzMxYjQ0ZWEwN2RmYmNjN2RiYzYwMTNhMDJjMTgxOWQ3ZTM5MjkyYSZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/D35fOVm9gSQ91icJeR/giphy.gif">

* Page Speed
* Security
* Broken Links
* Sitemap

</div>

</div>

<div class="absolute inset-0" v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 100, transition: { delay: 2000, duration: 20000 }}">
<div class="flex justify-center items-center h-full"> 
<logos-vue class="text-8xl" />
</div>
</div>

<!--

* Focus on 1 and 3
  * Why not Off-Page
    * Time
    * On-page Technical are easier to get started w/ for devs

-->

---

<div class="absolute inset-0">
  <div class="flex justify-center items-center h-full"> 
  <logos-vue class="text-8xl" />
  </div>
</div>

<!--

* Vue.js SPAs generate HTML through JS
* But what happens when there wouldn't be JavaScript or when it breaks?

-->

---

<div class="absolute inset-0 bg-black">
  <div class="flex justify-center items-center h-full"> 
  </div>
</div>

---

<div class="absolute inset-0 bg-black">
  <div class="flex justify-center items-center h-full"> 
<div class="lds-spinner"><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div></div>
</div>
</div>

<style>
.lds-spinner {
  color: official;
  display: inline-block;
  position: relative;
  width: 80px;
  height: 80px;
}
.lds-spinner div {
  transform-origin: 40px 40px;
  animation: lds-spinner 1.2s linear infinite;
}
.lds-spinner div:after {
  content: " ";
  display: block;
  position: absolute;
  top: 3px;
  left: 37px;
  width: 6px;
  height: 18px;
  border-radius: 20%;
  background: #fff;
}
.lds-spinner div:nth-child(1) {
  transform: rotate(0deg);
  animation-delay: -1.1s;
}
.lds-spinner div:nth-child(2) {
  transform: rotate(30deg);
  animation-delay: -1s;
}
.lds-spinner div:nth-child(3) {
  transform: rotate(60deg);
  animation-delay: -0.9s;
}
.lds-spinner div:nth-child(4) {
  transform: rotate(90deg);
  animation-delay: -0.8s;
}
.lds-spinner div:nth-child(5) {
  transform: rotate(120deg);
  animation-delay: -0.7s;
}
.lds-spinner div:nth-child(6) {
  transform: rotate(150deg);
  animation-delay: -0.6s;
}
.lds-spinner div:nth-child(7) {
  transform: rotate(180deg);
  animation-delay: -0.5s;
}
.lds-spinner div:nth-child(8) {
  transform: rotate(210deg);
  animation-delay: -0.4s;
}
.lds-spinner div:nth-child(9) {
  transform: rotate(240deg);
  animation-delay: -0.3s;
}
.lds-spinner div:nth-child(10) {
  transform: rotate(270deg);
  animation-delay: -0.2s;
}
.lds-spinner div:nth-child(11) {
  transform: rotate(300deg);
  animation-delay: -0.1s;
}
.lds-spinner div:nth-child(12) {
  transform: rotate(330deg);
  animation-delay: 0s;
}
@keyframes lds-spinner {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
  }
}

</style>

---
layout: intro
---

# No content when JavaScript is disabled or not loaded

---
layout: intro
---

# A problem for search engines?

<VClicks>

## Not anymore! <mdi-check class="text-green-500" />

## But there are caveats!

</VClicks>

<!-- 

SEs understand JavaScript

-->

---

# Crawling Caveats

<VClicks depth="2">

* <span class="text-orange-400">No interactions</span> during crawling
    * No button clicking
    * No permissions granted (e.g. camera)
    * No scrolling
* No data persistence (cookies/storage)
* Crawl Budget

</VClicks>

<!--
Links are treated as "new requests"
Also: * No generic timeout of e.g. 3 seconds
    * Still can lead to non-indexed content
-->

---

# SPA caveats

<VClicks>

* No preview (og images)
* Can be brittle due to JS (HTML is more forgiving)
* No fragment routing mode, "real" URLs needed
* => More work for multi-page applications

</VClicks>

---
layout: quote
---

# _Just because Google can index your page,<br>it does not mean it will rank well!_

<!--

Pure CSR might not be enough!

-->

---

# What else if not CSR?

<VClicks>

* Server Side Rendering!
* SSG / ISR / Dynamic SSR / mix them up

</VClicks>

<div v-click class="flex justify-center">
<logos-nuxt-icon class="text-8xl" />
</div>

<Code v-click>

```ts
export default defineNuxtConfig({
    // ssr: true, <- default
  routeRules: {
    '/blog/**': { swr: true },
    '/blog/**': { static: true }
  }
})
```

</Code>



<!--

* Reference: Alba's talk

-->

---

# Little spoiler 👀 


<Code v-click file="soon.vue">

```vue
<script setup lang="ts">
defineRouteRules({
  ssr: false
  prerender: true,
  headers: {
    'X-Test': 'defined within a page'
  },
})
</script>
```

</Code>

<VClick>

[A PR is up for this](https://github.com/nuxt/nuxt/pull/20391)

</VClick>

---
layout: intro
---

# Now, let's see what we need to achieve good seo!

---

# Feature/Task/...

<div class="flex justify-between items-center mt-4">
  <div>🌌 Type: Technical/On-page</div>
  <div>Effort: 🚀 - 🚀🚀🚀🚀🚀</div>
</div>

---


# Basic Security

<div class="flex justify-between items-center mt-4 mb-8">
  <div>🌌 Type: Technical/</div>
  <div>Effort: 🚀</div>
</div>

<VClicks>

* <span class="text-orange-400">Enable HTTPS</span>
* Set Security headers
* Use a Content Security Policy

</VClicks>

<!--

Creates trust for visitors!
HTTPS is a ranking factor

Low hanging fruit!

-->

---

# Mobile Friendliness

<div class="flex justify-between items-center mt-4 mb-8">
  <div>🌌 Type: Technical</div>
  <div>Effort: 🚀 - 🚀🚀🚀🚀🚀</div>
</div>

<VClicks>

* <span class="text-orange-400">Must-have</span> nowadays
* Google crawls with (emulated) mobile setup by default
* **Ranking factor!**

</VClicks>

---


# Core Web Vitals

<div class="flex justify-between items-center mt-4 mb-8">
  <div>🌌 Type: Technical</div>
  <div>Effort: 🚀 - 🚀🚀🚀🚀🚀</div>
</div>

<VClicks>

* "Essential metrics for a healthy site"
* **Ranking Factor**

</VClicks>

<div class="flex justify-around">
<img class="h-64 w-64" src="https://web-dev.imgix.net/image/tcFciHGuF3MxnTr1y5ue01OGLBn2/ZZU8Z7TMKXmzZT2mCjJU.svg">
<img class="h-64 w-64" src="https://web-dev.imgix.net/image/tcFciHGuF3MxnTr1y5ue01OGLBn2/iHYrrXKe4QRcb2uu8eV8.svg">
<img class="h-64 w-64" src="https://web-dev.imgix.net/image/tcFciHGuF3MxnTr1y5ue01OGLBn2/dgpDFckbHwwOKdIGDa3N.svg">
</div>

---

# Core Web Vitals

<div class="flex justify-between items-center mt-4 mb-8">
  <div>🌌 Type: Technical</div>
  <div>Effort: 🚀 - 🚀🚀🚀🚀🚀</div>
</div>

* <span class="text-orange-400">FID will be replaced by INP soon!</span>

<div class="flex justify-around">
<img class="h-64" src="/inp.jpg">
</div>

---

# Text Compression

<div class="flex justify-between items-center mt-4 mb-8">
  <div>🌌 Type: Technical</div>
  <div>Effort: 🚀</div>
</div>

<VClicks>

* Also a **must have** for every page out there
* GZIP comes usually by default
* Brotli is faster and leads to smaller files
* Use e.g. [Brotli.pro](https://www.brotli.pro/) to check your site
* **Improves page speed**
* Nuxt (Nitro) already supports compression for static assets
* "On the fly" is usually the job of your web server or platform provider

</VClicks>

---

# Broken links and redirects

<div class="flex justify-between items-center mt-4 mb-8">
  <div>🌌 Type: Technical</div>
  <div>Effort: 🚀 - 🚀🚀🚀</div>
</div>

<VClicks>

* Make sure that you <span class="text-orange-400">don't link to broken pages</span>
* Check for broken links to your page
    * Setup <span class="text-orange-400">redirects</span> for them
* Avoid redirect chains (/a -> /b -> /c)
* Redirects possible through web server / platform provider
* Also through Nuxt's `routeRules` or server middleware

</VClicks>

---

# Canonical Links

<div class="flex justify-between items-center mt-4 mb-8">
  <div>🌌 Type: On-page</div>
  <div>Effort: 🚀</div>
</div>

<VClicks>

* Set a canonical link for <span class="text-orange-400">every page</span>
* It represents the preferred link/version of the page
* Use the same URL for pages with duplicate content
* Great for trailing slash enforcement

</VClicks>

<Code v-click file="index.html">

```html
<link rel="canonical" href="https://abc.com/shoes/...">
```

</Code>

<VClicks>

* `https://abc.com/shoes/nike-air-max/`
* `https://abc.com/specials/nike-air-max/`

</VClicks>

---

# Canonical Link Conversion

<div class="grid grid-cols-2 gap-4">
<VClicks>

* The webserver should handle:
    * `http://www.example.com`
    * `http://example.com`
    * `http://example.com/`
    * `http://www.example.com/`
    * `https://www.example.com/`
    * `https://www.example.com`

</VClicks>

<VClicks>

* The frontend should handle:
    * `https://example.com`
    * `https://example.com/`
    * `https://example.com/?foo`
    * `https://example.com/#ab`
    * `https://example.com/`

</VClicks>
</div>


<VClicks class="mt-8">

* The canonical should be set to `https://example.com/`
* Can also be www and have no trailing slash
    * Be <span class="text-orange-400">consistent</span>!

</VClicks>

<!--

* HTTP / HTTPS handling
* www / non-www handling

-->

---

# Asset optimizations

<div class="flex justify-between items-center mt-4 mb-8">
  <div>🌌 Type: Technical</div>
  <div>Effort: 🚀 - 🚀🚀</div>
</div>

<VClicks>

* Optimized responsive images via `<picture>`
* Mind the format and size
    * Remove metadata, compress lossy
    * Load lazily
* Improve JS via code-splitting, lazy-loading & treeshaking
* Cache all static assets, use hashes/fingerprinting
* Use descriptive file names for images!

</VClicks>

---

# URL Structure

<div class="flex justify-between items-center mt-4 mb-8">
  <div>🌌 Type: Technical</div>
  <div>Effort: 🚀🚀 - 🚀🚀🚀🚀</div>
</div>

<div class="grid grid-cols-5 gap-4">

<div class="col-span-2">
<VClicks>

* Use short and descriptive URLs
* Remove stop words (and, the, a, ...)
* Enforce trailing slashes or remove them
* Place keywords inside
* Avoid query params
* Use hyphens as delimiters
* non-www or www

</VClicks>
</div>

<div class="col-span-3">
<VClicks>

* https://abc.com/?id=129310231 🤮
* https://abc.com/129310231.html 😢
* https://abc.com/blog_post-about_benefits_of-nuxt.html 🙁
* https://abc.com/blog/post-about-benefits-of-nuxt.html 🙂
* https://abc.com/blog/benefits-of-nuxt/ 🤩

</VClicks>
</div>
</div>

---

# Meta Tags

<div class="flex justify-between items-center mt-4 mb-8">
  <div>🌌 Type: On-page</div>
  <div>Effort: 🚀 - 🚀🚀🚀🚀🚀</div>
</div>

<img class="h-32 mb-8" src="/brotli-pro-metatags.jpg">

<VClicks>

* Set UTF-8 charset as well as the initial viewport
* Find the ideal <span class="text-[#fe3eff]">title</span> and <span class="text-[#fcf74e]">meta description</span> for each page
* Testing will be necessary but is worth it
* Use OG tags to improve link previews

</VClicks>

---

# Meta Tags in Nuxt

```html
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
```

<VClicks class="mt-16">

* Charset and viewport are already set by default in Nuxt
* All meta tags can in any component via `useHead`
* Let's have a look!

</VClicks>

---

# There is more
But not enough time 😢

<VClicks>

* Semantic HTML
* Alt Tags
* Page Structure
* Sitemap
* Structured Data
* Robots.txt
* hreflang
* Anchor texts
* and so on!

</VClicks>

---

# Lifehack: Use [`nuxt-seo-kit`](https://github.com/harlan-zw/nuxt-seo-kit)

The all-in-one SEO module for Nuxt 3

<VClicks>

* 📖 nuxt-simple-sitemap - Sitemap.xml Support
* 🤖 nuxt-simple-robots - Manage site crawling
* 🔎 nuxt-schema-org - Generate Schema.org JSON-LD for SEO
* △ nuxt-unhead - Experimental SEO meta features
* 🖼️ nuxt-og-image - Generate dynamic social share images
* ✅ nuxt-link-checker - Check for broken links

</VClicks>

<div class="flex flex-col items-center justify-center" v-click>
<img src="https://avatars.githubusercontent.com/u/5326365?v=4" alt="Harlan Wilton" class="h-32 rounded-full">
Maintained by Harlan Wilton
</div>

---
layout: intro
---

# Thanks a lot to my sponsors!
<img src="https://raw.githubusercontent.com/manniL/static/main/sponsors.svg" class="h-80 mx-auto" alt="My GitHub sponsors">

---
layout: two-cols
heading: Thank you for your attention!
---

<template v-slot:default>
<div class="flex flex-col justify-center items-center h-full">
<img
  class="w-75 rounded-full"
  src="https://lichter.io/img/me@2x.webp"
  />
  <h2 class="mt-4">Alexander Lichter</h2>
</div>
</template>

<template v-slot:right>

* <mdi-account-check class="text-green-100" /> **Web Development Consultant**
* <mdi-microphone /> Speaker & Instructor
* <logos-nuxt-icon /> Nuxt.js Team
* <mdi-twitter class="text-blue-400" /> @TheAlexLichter
* <mdi-web /> [https://lichter.io](https://lichter.io)
* <mdi-github /> [manniL](https://github.com/manniL)

</template>

<style>
  ul {
    @apply space-y-2 mt-10 text-xl h-full;
  }
</style>

---
layout: intro
---

# Slides & Repo

## [https://lichter.link/vl-2023/](https://lichter.link/vl-2023/)

<img src="/qr-code-slides.png" class="h-75 mx-auto mt-4" role="presentation" />