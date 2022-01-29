---
title: 'Setup your own academic homepage from scratch'
date: 2022-01-29
permalink: /posts/2022/01/setup-homepage/
tags:
  - homepage
---

I write this blog post to record how I setup my [personal homepage](https://fyy10.github.io/).

# Choose a template

While surfing the internet, I discovered an academic homepage template developed by [Prof. Stuart Geiger](http://stuartgeiger.com/) that greatly meets my needs. The contents are well-organized and I can post some blogs. Moreover, the website can be deployed with [GitHub Pages](https://pages.github.com/), which means it is free (at least for now) and I don't have to stick with complicated front-end designing, *e.g.*, JS, CSS, and HTML, that I'm not familiar with. You can find the template [here](https://github.com/academicpages/academicpages.github.io).

# Deploy the template

Use this [repo](https://github.com/academicpages/academicpages.github.io) as the template.

Fork the repo and rename it as `(username).github.io`, in my case, `Fyy10.github.io`.

Wait for some minutes and then you can see that the page is published at `(username).github.io`, and mine is [here](https://fyy10.github.io/).

# Customize

Please refer to [this page](https://academicpages.github.io/markdown/) for more details.

## Basic setting

The basic settings are in file `_config.yml`, which is pretty straight-forward.

## Customize top bar

Modify `_data/navigation.yml` to change top bar contents, *i.e.*, choose the types of stuffs you want to show up on your homepage.

## Page view and meta data

The contents of the pages are organized in markdown files and each top bar has it's own directory of files or a single file. On the top of each markdown file, some meta data are provided in YAML to describe the file. For top bars whose contents are generated from single files, the markdown files are in folder `_pages`.

Here are some files that you may want to modify in the `_pages` folder:

- `about.md`: the main page for a brief self-introduction
- `404.md`: notification for page not found
- `cv.md`: resume

## Markdown Generator

Generate markdown files for publications from `.tsv` files (tab-separated values). Use jupyter notebook `publications.ipynb` or python script `publications.py` in the `markdown_generator` folder.

# Serve locally

It is very useful to debug locally before committing to the GitHub repo.

## Install dependencies

```bash
sudo apt install ruby-dev ruby-bundler nodejs
```

## Clean up the directory

```bash
bundle clean
```

Do not use `--force`.

## Install ruby dependencies

```bash
bundle install
```

If errors prompt, delete `Gemfile.lock` and retry.

## Generate HTML and start service

```bash
bundle exec jekyll liveserve
```

Now you can access the website locally at [http://localhost:4000](http://localhost:4000).

> Note: If you want to access a link in the local website, remember to replace the prefix of the address with http://localhost:4000, otherwise you will goto the online page, not the local one. For example, in my case, I replace https://fyy10.github.io/foo with http://localhost:4000/foo to view my local page `foo`.

# Other stuffs

I'm still trying to figure out how to elegantly show images (physically well-organized) in the posts and I will try adding some pictures in the following ones to make them more readable. I apologize for the lack of vivid image in this blog post.