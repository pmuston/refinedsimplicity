---
title: "Experiences of the Top Static Site Generators"
date: 2019-01-02T17:43:00+02:00
draft: true
featuredImg: ""
tags: 
  - gatsby
  - hugo
  - hexo
  - nuxt
  - jekyll
---
A friend sent me a link to [10 Best Static Site Generators](https://www.creativebloq.com/features/10-best-static-site-generators). I had read this page several months ago, but it was good to revisit it as my journey with Static Site Generators has progressed significantly since.
I played with Jekyll a lot of years ago when I was interested in Ruby. I also played with Hexo a couple of years ago when I happened to be exploring the MEAN stack.
My interest at that time was while exploring my thoughts around rapid markup for learning management systems with interactive content.

I worked with Hugo for a couple of weeks during December. I'd been recreating a framework and page examples for someone else to fill in the bulk of the content.
There is a draft blog post on this topic waiting on publication of the sites.
I think I have explored pretty much all of Hugo during this time. It is great for templates + markdown + meta data. I mainly gave it a chance because it was based on Go, which is high on my "want to do more with" list. The project was being developed as a Django WebApp with some of the content expressed as Markdown. I switch Hugo after a high productive weekend experiment reusing the existing markdown, I also found that many of the other pages could be expressed in Hugo's markdown due to custom shortcodes.
I got productive in Hugo extremely quickly.

I know this a continuum rather than a classification, but Hugo is more a static HTML site generator - generating HTML pages. Gatesby and Nuxt are more static single page app generators. rather than Javascript bundles.
I think I can do almost things with it for the "most pages are different" content based website - even adding some custom VueJS components for some of the pages.
One great advantage it has was the custom tags within markdown idea which i used for YouTube and SlideShare resources.

Gatsby and Nuxt are for creating more statically generated single page applications.
I want to explore Gatsby as I see it becoming the Goto tool for the next generation of the JAMStack.
I have played with Nuxt. I've fond VueJS the best compromise for creating interactive interfaces.
However, I've found React(JSX)+GraphQL having the cleaner interface for generating documents from data.
This is because React is just Javascript, no other template languages involved.
Also because of Gatsby 2.0's unification of GraphQL - plugging GraphQL provides at every possible layer, including the folder/document hierarchy.