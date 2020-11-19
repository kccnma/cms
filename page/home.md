---
layout: page
title: Home
permalink: /
mainnavitem: false
---
# NMA Static Generated Test Site w/ Netlify CMS

### Build and Auto-Deploy Using Jekyll, Github, + Netlify

This is a dev test for a potentially new static generatid website for the KCC New Media Arts Program. Built using [Jekyll](https://jekyllrb.com/), it is setup to auto-deploy to Netlify via Github or via a Netlify CMS front-end admin interface (that uses Netlify Identity for authentication) for non-technical content creators. Last updated December 2019 with Melissa.  

### Links

* [NMA CMS Github Repo](https://github.com/kccnma/cms)
* [NMA CMS Admin Login](https://nma.netlify.com/admin/)

### Instructions

#### To develop the site and manage content locally:

* Clone the [NMA CMS Repo](https://github.com/kccnma/cms) via Github
* Use your Terminal/CLI to cd to the the project directory and run Jekyll locally 

When developing locally:

```
$ jekyll serve
```

When ready to deploy:

```
$ jekyll build
```

#### To manage content online via the Admin CMS:

* Login to the [NMA CMS](https://nma.netlify.com/admin/) via your Netlify Identity

  * No Login? Create an account at [Netlify](https://app.netlify.com) then contact NMA for access.
* Edit Existing Pages/Posts or Create New Ones via Your Browser

### Log:

* Upon content change via CMS, the [Netlify hosted static site](https://nma.netlify.com) is not auto-updating (NEED TO RETEST AGAIN), although the [github repo](https://github.com/kccnma/cms/) files are updating, along with the [github pages hosted static site](https://kccnma.github.io/cms/).

  * Netlify-hosted static site currently requires a manual deploy (via netlify admin interface). This was not always the case.
  * This could be interpreted as a good thing, if we use the gh-pages site as a staging server and the netlify site as the production server.
* New posted are not working when added via Netlify CMS interface.

  * Old posted can be modified OK.
  * New posts are able to be added/created OK (via the admin cms interface), but they are not viewable via the static generated site.

    * Observation: new posted do not get a date time-stamp at the beginning of the md file name.
* Further testing needed (added to to-do list)

  * need to address home page front-matter showing up (need to generate the home page correctly instead of an include)
  * HOLD - need to re-link netlify and github repo? 
  * DONE - ~~need to manually add/create/edit netlify webhook?~~ 

    * The fix:

      * new Netlify build hook created via Netlify App on 12-11-19
      * old GitHub webhook updated (url) on 12-11-19 (to match the new Netlify build hook)
      * NEW SETUP TESTED + WORKED on 12-11-19