[![Netlify Status](https://api.netlify.com/api/v1/badges/dcf3d5d0-a4a4-486f-bd9a-64b612392aad/deploy-status)](https://app.netlify.com/sites/brave-bell-c85a34/deploys)

# Research lab website template

This website is built with [Jekyll](https://jekyllrb.com/).
It is derived from the great template provided by the
[Allan Lab](https://www.allanlab.org/aboutwebsite.html), at Leiden University.

## Setup

``` bash
brew install ruby
gem install bundler jekyll
```

Clone this repository, then install the dependencies:

``` bash
bundle install
```

## Run

Run the local webserver with:

``` bash
bundle exec jekyll serve
```

## Contribute

### Add a new member

New members are stored as markdown files under
[_pages/team/_posts](_pages/team/_posts).

Each new member `.md` file must look like this:

``` yaml
---
layout: member
category: staff
title: Researcher Name
image: researcher.png
role: Lab Director
permalink: 'team/researcher-name'
social:
    twitter: https://twitter.com/
    linkedin: https://www.linkedin.com/
    google-scholar: https://scholar.google.fr/
    github: https://github.com/
    website:
    orcid: https://orcid.org/
    research-gate: https://www.researchgate.net/
education:
 - Education
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit
esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
cupidatat non proident, sunt in culpa qui officia deserunt
mollit anim id est laborum.
```

