# LIVE ELECTION RESULTS


# How to Contribute

- STEP 1: Create a new markdown file for the given result and date following this format `2019-02-28-lagos-state-result.md"
	In the example given, the text preceded by `-` form the hyperlink of the post and is already available within the view

- STEP 2: Setup the Markdown page with frontMatter definition which looks like this


```
---
layout: post
title: Presidential | Ebonyi State Result
category: [presidential, election]
img: nigeria.jpg
alt: Nigeria Decides
description: Ebonyi State Collation for Presidential Elections
---

```

	- The : layout defines the structure of the page
	- Title : is the Title for the Page and Meta Tags
	- category : is an array of categories each feed falls into
	- img : references the image in /images folder used in the meta tags
	- description : Is the description for page excerpts and meta tags


- STEP 3 : Once you have been able to create a page for any result feed, you can now to post the results for that current category formatted in markdown


### EPIC

There is an inforgraphic presentation of the results using SVG charts which we implement using [ChartGo](https://www.chartgo.com/) and [Online Charts](https://www.onlinecharttool.com/graph)



### PR

- Send in Pull Request with verified source of entry (source for results, INEC Official, or Two Reputable Publishing Networks)
