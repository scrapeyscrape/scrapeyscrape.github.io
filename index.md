# Welcome!

The web is full of public data that can be easily extracted. On this page I will show you how through my own real-life scraping tasks. If these don't cover your needs, you can [contact me](mailto:hello@scrapeyscrape.com) for bespoke scraping jobs.


## Scraping reviews from [ratemds.com](ratemds.com)
Recently a friend was considering having back surgery done by Dr. Michael Nikolakis. I wanted to do some research on Dr. Nikolakis and came across ~80 reviews on [ratemds.com](https://www.ratemds.com/doctor-ratings/958209/Dr-Michael-Nikolakis-New+Westminster-BC.html).

### Content
The website provides a simple listing of reviews like this:
![ratemds_reviews](./img/ratemds_reviews.jpg)
I wanted to extract the following fields:
- The overall rating in stars;
- Individual ratings for Staff, Punctuality, Helpfulness, and Knowledge;
- The content of the review itself;
- The date of the review.

### Pagination
Hovering over the navigation links at the bottom of the pages revealed the simple pagination structure:
![ratemds_pagination](./img/ratemds_pagination.jpg)
The top-level link is `https://www.ratemds.com/doctor-ratings/958209/Dr-Michael-Nikolakis-New+Westminster-BC.html` and each page adds a suffix `?page=PAGENUMBER`.




```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/scrapeyscrape/scrapeyscrape.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
