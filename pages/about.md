---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
#credits: true
# featured-image value can be one objectid for a photo object in this collection, a relative path to an image in this project, or a full url to any image. If left blank, no featured image will appear at top of About page.
about-featured-image: demo_031
# set background-position for featured image, "center", "top", "bottom"
position: bottom
# major heading to display over featured image
heading: The Collection
# paragraph text below heading in featured image
sub-heading: 
# additional padding added to the feature to increase size. Give value in em or px, e.g. "5em".
padding: 6em
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---
# About The Allie Bellew Collection

See [My Website](https://alexjberinger.com) for detailed information about my book.

{% include feature/image.html objectid="alliebellew_002" width="75" %} 

{% include feature/accordion.html title1="This is an example of accordion" text1=example1 title2="Section two" text2=example2 title3="Section three" text3=example3 %}
{% include feature/image.html objectid="demo_001" %}

<!-- IMPORTANT!!! DELETE this comment and the include below when you are finished editing this page for your collection. The include below introduces about page features. They will show up on your collection's about page until you delete it.  -->
{% include feature/alert.html text="This is an alert as an example" color="warning" align="center" %}
{% include cb/about_the_about.md %} 
