---
layout: splash
title: Playing with Jekyll
header:
    overlay_image: '/assets/img/purple-marble.jpg'
---


# Building and Testing a Jekyll Website

## Introduction

[Jekyll](https://jekyllrb.com/) is a simple, blog-aware, static site generator perfect for personal, project, or organization sites. It's straightforward to use and works well with GitHub Pages. In this article, we'll go through the basics of setting up and testing a Jekyll website.

## Prerequisites

Before you begin, make sure you have the following installed:
- Ruby version 2.5.0 or higher, including all development headers
- RubyGems
- GCC and Make

## Step 1: Installing Jekyll

First, install Jekyll and bundler gems.

```bash
gem install jekyll bundler
```

## Step 2: Creating a New Jekyll Site

To create a new site, run:

```bash
jekyll new my-awesome-site
```

Replace `my-awesome-site` with your project name.

## Step 3: Building the Site

Navigate to your new directory and build the site:

```bash
cd my-awesome-site
bundle exec jekyll serve
```

This command builds your site and serves it locally.

## Step 4: Customizing Your Site

Now, you can start customizing your site. Edit the `_config.yml` file to change the title, author, and other settings. You can also create new posts in the `_posts` directory.

## Step 5: Testing Your Site

Testing is crucial. Jekyll comes with a built-in development server that rebuilds your site each time a file changes. You can also write tests for your Jekyll site using frameworks like [HTMLProofer](https://github.com/gjtorikian/html-proofer).

## Conclusion

Jekyll is a powerful tool for creating simple websites and blogs. With its easy-to-use structure and compatibility with GitHub Pages, it’s a great choice for static site generation.