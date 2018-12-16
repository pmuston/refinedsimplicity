---
title: "Creating This Blog"
date: 2018-12-16T11:46:00+02:00
draft: false
featuredImg: ""
tags: 
  - hugo
  - netlify
---

So I created the simple blog you are reading, using Hugo and the hermit theme.
My initial snaffu was that I didn't read to copy the config.toml from the themes example site. There was quite a bit of config in there. An easy start to view locally.

I deployed it to netlify. Added a new site from Git. I had problem building the site as the build couldn't find the theme, I'd used the git submodule style of adding a theme in Hugo. I didn't investigate too far as I was in a hurry. I just nuked the git submodule, and made it a simple subdiectory of the site's theme in the same repository. I will explore git submodules in my next site - I am not familiar with them. To nuke the submodule I'd recreated the repository I had to recreate the site too. Success!

I added a custom domain by using netlify's nameservers to use the ANAME method (GoDaddy didn't seem to support them). It worked and resolved quickly. I also added HTTPS easily through Netlify's use of Let's Encrypt. Probably due to DNS changes that didn't happened immediately, but was ulitimately successfully after letting it resolve overnight.

After updating the baseURL and pushing changes to github the site updated nicely within a minute.

Well done Netlify, so far a wonderful experience.
