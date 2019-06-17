# Contributing Tutorials via Github to Reproducibility for Everyone

There are numerous ways in which you can contribute to the Reproducibility for Everyone project. Here we describe how you can add a tutorial 
via a pull request in Github. Other contribution options are available [on our website](http://www.repro4everyone.org/pages/contribute.html).

## 1. Fork this site

Click on the `Fork` button at the top right hand corner of this page to make a copy of it in your own username space on Github.

_Notes: To be able to fork the repository, you will need a Github account which can be created at no cost. Vist [github.com](https://github.com) to create your account._

## 2. Create a new file to make your tutorial

- After forking this repository, navigate to your copy of the repro4every repository. It will be at https://github.com/[your username]/repro4every.
- Click on the `_docs` folder 
- Click on `Create new file` which is near the top right of this page


## 3. File name

- Don't put any spaces in the file name otherwise it will not render correctly, rather use `-` or `_` to separate words and 
make the filename more readable.
- You can call the tutorial something useful but short
  e.g. `reproducibility-dictionary.md`
- The file extension must be `.md` as this will be in the markdown format
  
## 4. Add header

- It is very important to add the following header to the very top of the file:

```
---
layout: doc                             ## Do not change this
title: "Add your title here"
description: "Add your oneliner description here. It will display in Google searches as metadata for the file"
date: 2018-12-08 8:14:30 +0600          ## Change this to reflect the date on which you submitted the file along with your timezone offset from UTC 
category_name: [Select one of the category names that suites best and delete the others: 1 Getting Started, 2 Referencing & Literature, 3 Planning Research, 4 Experimental Reproducibility, 5 Sharing & Collaborating, 6 Analysis & Computation, 7 Visualization & Images]    ## Delete category names that is not relevant - choose ONLY 1. Don't change the formatting of the category name 
category_slug: [Select the slug related to the category name you selected above: getting-started, referencing, planning, experiments, share-collaborate, analyse-compute, viz-image] ## Select only the slug that fits with the category name that you used above
---
```

## 5. Add content in markdown format 

- Markdown format tips and tricks can be found [online](https://www.makeuseof.com/tag/printable-markdown-cheat-sheet/) 

## 6. About links in the text

- If you want to add links to the text, please do as follows:
  - In the text where you want to add the linked text, surround the linked text with square brackets e.g. `find this on [our website]`
  - Then follow the square bracket enclosed linked text with a keyword in square brackets, which will be the shortcut to your URL e.g `find this on [our website][website]`
  - Now at the bottom of your blog post text file add all links and keywords as follows:
    ```
    [website]: http://www.repro4everyone.org
    [keyword2]: https://www.link2.com
    [keyword3]: http://link3.co.nz
    ```
    
## 7. About images

- Upload your content images if you have any to `https://github.com/your_user_name/repro4every/assets/images/blog` 

