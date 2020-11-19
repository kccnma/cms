---
layout: page
thumbnail: /assets/img/uploads/placeholder-2x1.gif
title: About
permalink: /about/
mainnavitem: true
---
This is an **About** sub page.

This is a static site is generated using [Jekyll](https://jekyllrb.com/) and was initialized via a basic Jekyll starter site that uses the [Minima](https://github.com/jekyll/minima) theme. This is a dev test for a potentially new static static website for the KCC New Media Arts Program. It is set up to auto-deploy to Netlify via Github or via a Netlify CMS front-end admin interface (that uses Netlify Identity for authentication) for non-technical content creators. 

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

* See the [log page](https://kccnma.github.io/cms/log/).

### Tests

Links to sub pages currently being tested:

* [Log](../log/) page
* [Posts](../posts/) page (list of all posts)
* [Categories](../categories/) page (list of all posts with category associations)

Take a look at some basic content and it's default/current styling:

# Heading

## Heading

### Heading

#### Heading 4

##### Heading 5

###### Heading 6

This is a paragraph. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis ut fringilla ipsum, sed bibendum augue. Nullam euismod nec mauris elementum porta. Sed varius nisl eu lobortis fringilla. Morbi id elit sollicitudin, venenatis lacus id, cursus quam. Aliquam mollis orci vel enim fermentum adipiscing. Duis facilisis lorem a nulla porttitor sagittis.

This is a another paragraph. Suspendisse pulvinar bibendum laoreet. Suspendisse eget dignissim risus. Cras eget sodales enim. Phasellus accumsan dui metus, quis vulputate turpis congue at. Praesent rutrum consequat rhoncus. Maecenas adipiscing justo vitae massa porta pretium. In egestas orci vehicula, tempus lorem ut, facilisis metus.

This is a yet another paragraph. Vivamus eu mollis velit. Maecenas id massa libero. Aliquam accumsan mauris vulputate purus volutpat vestibulum. Phasellus sed tellus id tortor ornare molestie. Quisque massa sapien, elementum sed tortor vitae, suscipit congue massa. Curabitur tempor arcu eget leo placerat, a porta augue pharetra. Nulla velit nibh, laoreet at hendrerit sit amet, adipiscing eget dolor.

#### Unordered List:

* List Item
* List Item
  * Nested Unordered List:
    * List Item
    * List Item
  * Nested Ordered List:
    1. List Item
    2. List Item
    3. List Item
    4. List Item

#### Ordered List:

* List Item
* List Item
  * Nested Unordered List:
    * List Item
    * List Item
  * Nested Ordered List:
    1. List Item
    2. List Item
    3. List Item
    4. List Item

#### Links:

This is a [link](#).

#### Blockquotes:

> This is a blockquote. Donec sed rhoncus massa. Suspendisse rutrum viverra felis. Vestibulum augue lacus, ullamcorper non suscipit nec, ornare et mauris. Proin mattis fermentum nibh quis gravida.
>
> \- Source

#### Images

![Alt Text](https://kccnma.github.io/sitebase/examples/productsite/img/placeholder-1x1.gif)
