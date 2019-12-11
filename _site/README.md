# Custom Jekyll + Netlify CMS Setup

This is the basic Jekyll starter site, with Netlify CMS integrated and using Netlify Identity for
authentication. You can learn more about Netlify CMS at [the netlify-cms GitHub
repo](https://github.com/netlify/netlify-cms). You can see the static generated site on [netlify](https://nma.netlify.com) and on [github pages](https://kccnma.github.io/cms/). 

## Instructions

### To develop the site and manage content locally:

* Install [Git](http://git-scm.com/) and [Jekyll](https://jekyllrb.com/) 
* Clone the [NMA CMS Repo](https://github.com/kccnma/cms)

When developing locally:
```
$ jekyll serve
```

When ready to deploy:
```
$ jekyll build
```

### To update the site and manage content remotely via CMS (admin UI):

* [Netlify CMS admin UI](https://nma.netlify.com/admin/)

### Testing:

* [GitHub Pages hosted static site](https://kccnma.github.io/cms/)
* [Netlify hosted static site](https://nma.netlify.com)

### Deployment:

* Locally: run `jekyll build` then committ + pushing to master branch
* Remotely:
  * On Publish via [Netlify CMS admin UI](https://nma.netlify.com/admin/)
  * Manually trigger via [Netlify App > Deploys](https://app.netlify.com/sites/nma/deploys)