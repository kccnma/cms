---
layout: page
thumbnail: /assets/img/uploads/placeholder-2x1.gif
title: Home
---
# NMA Static Generated Test Site w/ Netlify CMS

### Build and Auto-Deploy Using Jekyll, Github, + Netlify

This is a temporary dev test for a potentially new static generatid website for the KCC New Media Arts Program. Built using [Jekyll](https://jekyllrb.com/), it is setup to auto-deploy to Netlify via Github or via a Netlify CMS front-end admin interface (that uses Netlify Identity for authentication) for non-technical content creators.  NMA Intern David, make this kick ass please.

### Links

* [NMA CMS Github Repo](https://github.com/kccnma/cms)
* [NMA CMS Admin Login](https://nma.netlify.com/admin/)

### Instructions

#### To develop the site and manage content locally:

* Clone the [NMA CMS Repo](https://github.com/kccnma/cms) via Github
* Use your Terminal/CLI to cd to the the project directory and run Jekyll locally 


```
$ jekyll serve
```

#### To manage content online via the Admin CMS:

* Login to the [NMA CMS](https://nma.netlify.com/admin/) via your Netlify Identity
  * No Login? Create an account at [Netlify](https://app.netlify.com) then contact NMA for access.
* Edit Existing Pages/Posts or Create New Ones via Your Browser

#### Log:

* Upon content change via CMS, [Netlify hosted static site](https://nma.netlify.com) not updating, although the [github repo](https://github.com/kccnma/cms/) files are updating, along with the [github pages hosted static site](https://kccnma.github.io/cms/).
  * Manual deploy needs further testing (via nma admin interface)
  * Further testing needed (added to to-do list)
