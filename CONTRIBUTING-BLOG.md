# Contributing to Reproducibility for Everyone

There are numerous ways in which you can contribute to the Reproducibility for Everyone project. Here we describe how you can add a blog 
post via a pull request in Github. Other contribution options are available [on our website]({{site.url}}/pages/contribute.html).

## 1. Fork this site

Click on the `Fork` button at the top right hand corner of this page to make a copy of it in your own username space on Github.

_Notes: To be able to fork the repository, you will need a Github account which can be created at no cost. Vist [github.com](https://github.com) to create your account._

## 2. Create a new file to make your blog post

- After forking this repository, navigate to your copy of the repro4every repository. It will be at https://github.com/[your username]/repro4every.
- Click on the `_posts` folder 
- Click on `Create new file` which is near the top right of this page


## 3. File name

- The file name is very important for it to render correctly
- Name the file as follows:
  `YYYY-MM-DD-post_name.md`
  e.g. `2019-05-19-learning_to_blog.md`
  
## 4. Add header

- It is very important to add the following header to the very top of the file:

```---
   layout: post ## Don't change anything here
   title: "Add your blog title inbetween the double quotation marks" ## Edit this
   date: 2018-10-19 18:14:30 +0600 ## Edit this to change the date and time to the current date and time and time zone you are in
   tags: [tag1, tag2] ## Edit this to add up to 5 tags for your post. It can be phrases. Comma separated
   post_image: 2018-10-19.jpg ## Edit this to be the name of the image you would like to use as header image for the post. Leave empty if no image required
   author: Name1, Name2, Name 3  ## Edit this to add the comma seperated list of name(s) of author(s)
   ---```
