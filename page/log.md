---
layout: page
title: Log
permalink: /log/
---
## Updates/changes:

* 11-18-2020
  * Fixed build error (removed collections meta)

* 04-16-2020 (?)
  * Upon content change via CMS, the [Netlify hosted static site](https://nma.netlify.com) is not auto-updating (NEED TO RETEST AGAIN), although the [github repo](https://github.com/kccnma/cms/) files are updating, along with the [github pages hosted static site](https://kccnma.github.io/cms/).
    * Netlify-hosted static site currently requires a manual deploy (via netlify admin interface). This was not always the case.
    * This could be interpreted as a good thing, if we use the gh-pages site as a staging server and the netlify site as the production server.
  * New posted are not working when added via Netlify CMS interface.
    * Old posted can be modified OK.
    * New posts are able to be added/created OK (via the admin cms interface), but they are not viewable via the static generated site.
      * Observation: new posted do not get a date time-stamp at the beginning of the md file name.

* 12-11-2019
  * Fixed auto-deployment issues (build and web hooks)
  * Fixed Netlify CMS created posts (added date info to post slug name via config file)
  * Added Permalink and Add-to-Main-Nav fields for Netlify CMS admin created pages 
