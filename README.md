# 🧗 Northeastern Climbing Website

> The official website for climbing at Northeastern. Uses Jekyll to serve content from easily editable markdown files.

## 🏔 Preview

http://northeasternclimbing.github.io

## 🏛 Project Structure

    northeasternclimbing.github.io/
    │
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
    │                     don't edit this folder. Edit index.sass instead
    │
    ├── fonts/            Contains site's fonts
    ├── images/           Contains site's images
    ├── nrc/              Contains markdown files for all NRC pages
    ├── team/             Contains markdown files for all team pages
    ├── _config.yml       Jekyll configuration file for site
    ├── index.md          Landing page
    └── index.sass        Stylings for site


## 🛰 How to do Stuff

### How do I edit a page?

- To edit the content of the landing page, edit the top level `index.md`
file.
- To edit a team page, edit the `.md` files in the `team/` directory.
- To edit an NRC page, edit the `.md` files in the `nrc/` directory.

### How do I add a new page?

- To add a new page, simply create a new `.md` file. The file's name
will become the URL of that page. If the file is in a directory, that
directory's name will also become part of the URL (i.e.: /team/)

### How do I edit the tab bar?

- To edit a the tab bar, edit the data files in the `_data/` directory.

## 🛠 Local Developement

### Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [jekyll](https://jekyllrb.com/docs/installation/)

### Cloning this Repository

- `git clone https://github.com/NortheasternClimbing/northeasternclimbing.github.io.git`

### Installing Dependencies

- `bundle install`

### Starting the Developement Server

- `bundle exec jekyll serve`
- go to `localhost:4000`

## 💩 Help

Feel free to reach out to Alex Crist at alexecrist@gmail.com for any
questions.
