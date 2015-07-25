# Garulab - My theme for Hugo


## Installation

    mkdir themes
    cd themes
    git clone https://github.com/brunohenrique/hugo-theme-garulab garulab

## Configuration

**config.toml**

``` toml
BaseUrl= "http://example.com/"
LanguageCode= "en-US"
Title= "My blog is awesome"
paginate = 5
DisqusShortname = "YOUR_SHORT_NAME_HERE"
Copyright = "All rights reserved - 2015"
canonifyurls = true

[params]
  description = "this is my description"
  cover = true
  author = "Bruno Henrique"
  authorlocation = "Natal/RN, Brazil"
  authorwebsite = "http://garulab.com"
  bio= "my bio"
  logo = "images/logo.png"
  googleAnalyticsUserID = "LL-NNNNN-NN"
  # Optional RSS-Link, if not provided it defaults to the standard index.xml
  RSSLink = "http://feeds.feedburner.com/..."
  githubName = "brunohenrique"
  twitterName = "garucosta"
  # set true if you are not proud of using Hugo (true will hide the footer note "Proudly published with HUGO.....")
  hideHUGOSupport = false

```

### Thanks
 - [Valere JEANTET](https://github.com/vjeantet) - For the base Caper Hugo theme
 - [Dan Leatherman](https://github.com/dleatherman) - For canvas particle experiment (JS Cover)

