# What is this

This is a repository that hosts this website: [LandChad.net](https://landchad.net)

A site dedicated to turn web peasants into Internet LandChads.

Simple step-by-step text and image-based tutorials for creating websites, email servers, chat servers, server administration and everything else.

This site is compiled and organized with Hugo, using [this very simple theme](https://github.com/lukesmithxyz/lugo).

The original author, [Luke Smith](https://youtu.be/@LukeSmithxyz), discusses how to use Hugo [here](https://youtube.com/watch?v=ZFL09qhKi5l).

## Submission guidelines

- Guides should be made for the most recent stable version of Debian. (Now Debian 12.)
- Follow the general style of pre-existing articles.
- use the root user (i.e. no `sudo`) unless there is a specific need.
- do not preface commands with `$` or `#` or anything.
- use `.svg` files for icons/logos and for illustrative images favor webp, keep filesize low.
- Use `example.org` the example domain.
- Do not add Docker tutorials.
- Installable services must have the `service` tag and an `icon` set in the metadata so they properly appear in the service display.
- Server/sysadmin tips should have the `server` tag, so they appear in that list.

## What is Hugo?

The world's fastest framework, written in Go

The best way to start is with a template theme. Borrow the one from [Lugo](https://github.com/lukesmithxyz/lugo).

```bash
hugo new site ${DIR}
```

In the site directory, run `hugo` to build sites and insert them into the `public` directory.

```bash
hudo server
```


### directories

- archetypes
- data
- public
- themes
- layouts
- content
- static
- config.toml

#### themes

#### config.toml

Configuration information for site

Change the base URL, langague code, title, and other site-wide settings

```Markdown
theme = '${theme-name}'
```

#### content

Place markdown files in here

Hugo will generate the HTML pages from here

#### static

Contains all files that are not web pages, like css files, images, downloadable documents
