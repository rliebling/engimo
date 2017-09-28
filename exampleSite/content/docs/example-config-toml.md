---
date: 2017-09-25T08:00:00+06:00
title: Example config.toml
authors: ["muniftanjim"]
categories:
  - others
tags:
  - config
slug: example-config-toml
---
Example `config.toml` configuration for Minimo:

```toml
baseURL = "http://www.example.com"
title = "Minimo"
# for smart copyright line, leave this blank and check [params.copyright]
copyright = ""

theme = "minimo"

disqusShortname = ""
googleAnalytics = ""

Paginate = 5
preserveTaxonomyNames = true

[params.info]
description = "Minimalist theme for Hugo"

[params.assets]
favicon = "favicon.ico"
customCSS = ["css/custom.css"]
customJS = ["js/custom.js"]

[params.copyright]
prefix = ""
holder = "MunifTanjim"
startYear = "2017"
suffix = ""

[params.settings]
# date & time format: https://golang.org/pkg/time/
dateFormat = "2006, Jan 2"
hideEntryNavigation = false
hideSocialMenu = false
showReadTime = true

[params.opengraph.facebook]
admins = [] # array of Facebook IDs
appID = ""
pageID = ""

[params.seo]
# Title Separator: - – — · • * ⋆ | ~ « » < >
titleSeparator = "•"

[params.social]
codepen = "MunifTanjim"
email = "contact@example.com"
facebook = "MunifTanjim"
github = "MunifTanjim"
instagram = "MunifTanjim"
twitter = "MunifTanjim"
linkedin = "muniftanjim"

[taxonomies]
author = "authors"
category = "categories"
tag = "tags"

[permalinks]
page = "/:slug/"

[[menu.main]]
name = "Repo"
weight = -70
identifier = "repository"
url = "https://github.com/MunifTanjim/minimo"

# Language Configuration
defaultContentLanguage = "en"

[languages]
# edit this block for your own language

[languages.en]
lang = "en"
languageName = "English"
weight = 1
```