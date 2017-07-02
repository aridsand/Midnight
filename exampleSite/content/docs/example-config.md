+++
title = "Example Config"
date = "2017-06-30T23:49:34-07:00"
categories = ["Documentation"]
enable_toc = true
[menu.main]
  weight = 1
  parent = "docs"
+++

```
languageCode = "en-us"
title = "My Example Site"
baseurl = "https://example.com/"
theme = "BluestNight"

paginate = 10             # Number of posts to show before paginating
enableRobotsTXT = true    # Suggested, enable theme robots.txt file
SectionPagesMenu = "main" # Enable menu system for lazy bloggers

[Params]
    tagline = "My example site subtitle"           # Subtitle of your site
    description = "Generic description of my site" # Description of your site
    # See the documentation on the Authorbox for more on setting it up
    # https://themes.gohugo.io/theme/BluestNight/docs/pages/authorbox/
    authorbox = true                               # Show the Authorbox by default
    author = "Michael Bryant"                      # The name of the person to serve as default author (optional)
    post_navigation = false                        # Enable "Next/Previous in Section" links
    # See the documentation on commenting for how to set up HashOver or Muut commenting
    # https://themes.gohugo.io/theme/BluestNight/docs/pages/comments/
    #hashover = true                               # Enable HashOver comments
    #muut = "muut-community-name"                  # Enabled Muut comments by providing the name of your Muut community

# Uncomment this section to use a background image on your site
# https://themes.gohugo.io/theme/BluestNight/docs/site/appearance/
#[Params.background]
#    src = "/images/background.png"
#    fit_width = true
#    tile = false

# The values here are the colors that the theme defaults to if none is provided
# For more on what each color is for:
# https://themes.gohugo.io/theme/BluestNight/docs/site/appearance/
[Params.color]
    page_background = "#000000"
    main_background = "#000000"
    alt_background  = "#252525"
    main_text       = "#e2e2e2"
    alt_text        = "#ffffff"
    accent          = "#2c8cef"
    accent_text     = "#000000"

# See the documentation for social icons for more services to link to
# https://themes.gohugo.io/theme/BluestNight/docs/site/social-icons/
[Params.social]
    linkedin = "mylinkedinusername"
    github = "mygithubusername"

[Params.widgets]
    search = true                 # Enable a search bar widget
    recent_articles = true        # Enable "Recent arcticles" widget
    categories = true             # Enable "Categories" widget
    tags = true                   # Enable "Tags" widget
    patreon = "mypatreonusername" # Enable "Patreon" widget

[outputs]
    # HTML and CSS are require for the theme to work.
    # RSS is needed to have a site RSS feed.
    # JSON is required to use search
    home = ["HTML", "CSS", "RSS", "JSON"]
    # This line needed only to enable per-section RSS feeds
    section = ["HTML", "RSS"]
    # This line needed only to enable per-taxonomy (tags, etc.) RSS feeds
    taxonomy = ["HTML", "RSS"]
```