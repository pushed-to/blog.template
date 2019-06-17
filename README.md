# blog.template

This is a template for a [pushed.to](http://pushed.to) blog.

## Get Started

Fork this repository into your own GitHub user or organization space. When forked you can visit [pushed.to/GIT_USERNAME/GIT_PROJECT_NAME](http://pushed.to/GIT_USERNAME/GIT_PROJECT_NAME).

## .blog Reference

The `.blog` contains configurations for your blog. The template\`s `.blog`-file contains the following settings:

```json
{
  "title": "Blog Title",
  "dateFormat": "MMMM DD, YYYY",
  "postPerPage": 3,
  "description": "This is a sample blog template. You may not define any description at all. But, you can do here...",
  "topics": [
    "topic-a",
    "topic-b",
    "topic-c"
  ],
  "social": {
    "twitter": "someTwitterHandle",
    "linkedin": "https://www.linkedin.com/in/some-name-0000000"
  },
  "analyticsId": "UA-2075101-7",
  "disqusId": "pushed-to"
}
```

* **title** - This is the printed title of your blog.
* **dateFormat** - Is the format of how dates are formatted on your blog (e.g. posted at date).
* **postPerPage** - Number of posts per page in the blog\`s landing page and history.
* **description** - Optional. Is a short description of your blog, it will be displayed on the landing page of your blog.
* **topics** - A list of topics your blog contains. The topics are shown on the landing page and posts can be filtered based on these topics.
* **social** - A list of social accounts:
    * **twitter** - Optional. Your twitter handle (without the @).
    * **linkedin** - Optional. Your linkedin profile url.
* **analyticsId** - Your own tracking id for [Google Analytics](https://analytics.google.com/analytics/web/).
* **disqusId** - Your own project id from [Disqus](https://disqus.com/), if not set a default id will be used to render comments section.

## Writing Posts

Every markdown file you place in the repository is considered to be a post (except `README.md`).