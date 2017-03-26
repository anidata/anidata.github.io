# anidata.github.io

Anidata Web Page

## Adding blog posts to [our blog](http://anidata.org/blog/index.html)

 1) Add a markdown file to the [_posts](_posts) directory with the format `year-month-day-title.md`

 2) The top portion of the file added should contain:
```
---
layout:     post
type: 		'blog' for a blog post or 'project' for a project post
title:      Descriptive title
date:       Date of post
summary:    Short summary of the post
media:		'false' if there is no image or the name of the image
---
```

The rest of the file is just a standard markdown document. Just remember to add any images used in the post to [/images](images).


## Adding a bio to the About page

  1) Go to the [_data](_data) directory.

  2) Edit the staff.yml file by adding in the following information:
  ```
---
position:	The position of the person at Anidata
name:		The person's name
image:		The image to use 
bio:		A short bio
---
```

Just remember to add any images used to [/images](images).
