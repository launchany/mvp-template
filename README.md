# Minimum viable documentation (MVD) template for API docs

This is a fill-in-the-blanks template for minimum API documentation. Replace all of the [prompts in brackets] with content that's specific to your API. When you've replaced all the bracketed prompts, you'll have the essentials documented sufficiently to help people use your API.

If something in this template doesn't make sense for your API, delete it! And likewise, add any sections you need based on your API's particulars. We hope our suggestions in this template will spark more ideas about documenting features of your API to help users consume it.

Most content is written in Markdown, although the homepage is written in HTML. The template itself is a Jekyll site that you can use with gh-pages. If you want to run your docs on gh-pages, here's a guide by Jonathan McGlone to help you get set up: [http://jmcglone.com/guides/github-pages/](http://jmcglone.com/guides/github-pages/).

## Clone this project

Clone this project to get a copy of the template that you can update and personalize.

```bash
git clone https://github.com/hillaryfraley/mvd-template.git
cd mvd-template
```

### Optional: Run a local copy

Here are GitHub's instructions for running a local copy: [https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)

## Files to update

These are the files to update with details about your own API.

#### /mvd-template/_config.yml

* Site settings: title, email, description, baseurl, url, git_address, git_edit_address
* Theme options: bootwatch theme you want to use to use
* `defaults`: schemas for pages (copy, paste, and update schemas as needed when you add or update pages and groups of pages)
* `collections`: schemas for pages (copy, paste, and update schemas as needed when you add or update pages and groups of pages)

#### /mvd-template/_about/index.md

Replace content with information about your API and documentation.

#### /mvd-template/_data/about.yml

List pages to include on About

#### /mvd-template/_data/docs.yml


#### /mvd-template/_config.yml



#### /mvd-template/_config.yml



#### /mvd-template/_config.yml


#### /mvd-template/_config.yml


# About the theme

This Jekyll documentation theme was developed by [Can Güney Aksakalli](https://aksakalli.github.io).

The GitHub repo for this documenation theme is [https://github.com/aksakalli/jekyll-doc-theme](https://github.com/aksakalli/jekyll-doc-theme). The demo is at [https://aksakalli.github.io/jekyll-doc-theme/](https://aksakalli.github.io/jekyll-doc-theme/).

The theme is released under [the MIT license](LICENSE).

