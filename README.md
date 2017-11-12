# Northeastern Climbing Website

## Preview

http://northeasternclimbing.github.io

## Summary

A Jekyll site that acts as the official resource for climbing at
Northeastern. The site is configured with HTML, SASS, and Jekyll,
but its content can easily be modified by editing markdown files which
require no knowledge of web developement.

## Project Structure

    northeasternclimbing.github.io/
    ├── _data/            Contains YML data accessible from pages and layouts
    │   ├── landing.yml   Data on tabs for landing page
    │   ├── nrc.yml       Data on tabs for NRC pages
    │   └── team.yml      Data on tabs for team pages
    │
    ├── _layouts/         Contains all HTML layouts for site pages
    │   ├── blank.html    Base layout containing HTML boilerplate code and footer
    │   ├── tabbed.html   A generic tabbed layout. Inherits from blank.html
    │   ├── landing.html  Layout for the landing page. Inherits from tabbed.html
    │   ├── nrc.html      Layout for NRC pages. Inherits from tabbed.html
    │   └── team.html     Layout for team pages. Inherits from tabbed.html
    │
    ├── _sass/            Contains stylings for the "contrast" theme. Generally
    │                     dont' edit this folder. Edit index.sass instead
    ├── fonts/            Contains site's fonts
    ├── images/           Contains site's images
    ├── nrc/              Contains markdown files for all NRC pages
    ├── team/             Contains markdown files for all team pages
    ├── _config.yml       Jekyll configuration file for site
    ├── index.md          Landing page
    └── index.sass        Stylings for site


## How to do Stuff

### How do I edit a page?

To edit the content of the landing page, edit the top level `index.md`
file.

To edit a team page, edit the `.md` files in the `team/` directory.

To edit an NRC page, edit the `.md` files in the `nrc/` directory.

### How do I add a new page?

To add a new page, simply create a new `.md` file. The file's name
will become the URL of that page. If the file is in a directory, that
directory's name will also become part of the URL (i.e.: /team/)

### How do I edit the tab bar?

To edit a the tab bar, edit the data files in the `_data/` directory.

## Local Developement

I find this easiest to do on Linux.

### Installation

1. [Install Jekyll](https://jekyllrb.com/docs/installation/)
1. Clone this repository to your computer using Git
1. Enter repository directory and run `bundle exec jekyll serve`

## Help

Feel free to reach out to Alex Crist at alexecrist@gmail.com for any
questions.
