# Fuse Core Theme for Jekyll - Settings
# https://github.com/tsjensen/fuse-core

markdown: kramdown
permalink: pretty
exclude: ['README.*', 'LICENSE.txt']
sass:
    style: expanded


# CAUTION
# When modifying this file, take care to preserve the indentation. This is YAML ...

# Main Headline, name required, subtitle optional
name: Artis
#subtitle:
subtitle: 

# Title attribute of HTML Page, uses 'name' from above if empty
title: Artis

# Information for web crawlers / Google, all of them optional
# 'description' and 'keywords' simply set the corresponding meta tags,
# 'crawl' is the 'Robots' tag http://www.robotstxt.org/meta.html
robots:
    description: One line of text describing the content of the page in less than 140 characters.
    keywords: foo, bar, baz
    crawl: index,follow

# website address when deployed, also given as canonical link
url: https://thorny66.github.io

# The 'baseurl' is prepended to all website-internal links.
# 'baseurl' will often be '', but for a project page on gh-pages, it needs to be the project name.
# If not empty, be careful to keep the leading slash, and don't add a slash at the end.
#baseurl: ''
baseurl: '/thorny66.github.io'

# Enable Google Analytics. Leave empty (just "ga:" with subitems commented out) to disable.
# In order to comply with EU cookie law, enable 'cookieconsent' to show a little popup asking users to acknowledge the GA cookies.
# Also, some places require you to anonymize the users' IPs, which can be enabled via 'anonymizeip' below. You normally want that.
# https://support.google.com/analytics/answer/2763052
#ga:
ga:
    account: 'UA-120960520-1'
    cookieconsent: true
    anonymizeip: true

# Plausible.io Analytics (alternative to Google Analytics that does not need cookies -> no cookie consent required)
# A config setting is required in plausible to enable tracking of the outbound links. Details described here:
# https://plausible.io/docs/outbound-link-click-tracking
# Leave empty (just "plausible:" with subitems commented out) to disable.
#plausible:
plausible:
    domain: 'tsjensen.github.io'


# A picture of you, square(!), at least 180x180 pixels, more is better. Recommended file size < 100 KB.
# Leave empty for generic placeholder image.
# You can use your GitHub image:
avatar: "https://avatars0.githubusercontent.com/u/8897534"
#avatar: "images/jonathan_doe.jpg"
#avatar:


# All the social media and other sites that we want to link to. The 'show' flag determines if the link is shown.
# The order of this list controls the order of the links on the page. Feel free to add.
links:
  - xing:
      name: Xing
      show: false
      href: https://www.xing.com/profile/YOUR_XING_USERNAME/
      icon: fab fa-xing
  - linkedin:
      name: LinkedIn
      show: true
      href: https://www.linkedin.com/company/107156667/admin/dashboard/
      icon: fab fa-linkedin
  - googleplus:
      name: Google+
      show: false
      href: https://plus.google.com/+YOUR_GOOGLEPLUS_USERNAME
      icon: fab fa-google-plus
  - twitter:
      name: Twitter
      show: false
      href: https://twitter.com/YOUR_TWITTER_USERNAME
      icon: fab fa-twitter
  - weibo:
      name: 微博
      show: false
      href: https://weibo.com/YOUR_WEIBO_USERNAME
      icon: fab fa-weibo
  - vine:
      name: Vine
      show: false
      href: https://vine.co/YOUR_VINE_USERNAME
      icon: fab fa-vine
  - facebook:
      name: Facebook
      show: false
      href: https://facebook.com/YOUR_FB_USERNAME
      icon: fab fa-facebook
  - vkontakte:
      name: ВКонтакте
      show: true
      href: https://vk.com/YOUR_VK_USERNAME
      icon: fab fa-vk
  - instagram:
      name: Instagram
      show: true
      href: https://instagram.com/artis.sf
      icon: fab fa-instagram
  - flickr:
      name: Flickr
      show: false
      href: https://flickr.com/photos/YOUR_FLICKR_USERNAME
      icon: fab fa-flickr
  - steam:
      name: Steam
      show: false
      href: http://steamcommunity.com/id/YOUR_STEAM_CUSTOM_ID
      icon: fab fa-steam
  - soundcloud:
      name: Soundcloud
      show: false
      href: https://soundcloud.com/YOUR_SOUNDCLOUD_USERNAME
      icon: fab fa-soundcloud
  - lastfm:
      name: Last.fm
      show: false
      href: http://www.last.fm/user/YOUR_LASTFM_USERNAME
      icon: fab fa-lastfm
  - github:
      name: GitHub
      show: false
      href: https://github.com/tsjensen
      icon: fab fa-github
  - codepen:
      name: CodePen
      show: false
      href: https://codepen.io/YOUR_CODEPEN_USERNAME
      icon: fab fa-codepen
  - stackoverflow:
      name: Stack Overflow
      show: false
      href: https://stackoverflow.com/users/YOUR_SO_USERNAME/
      icon: fab fa-stack-overflow
  - reddit:
      name: Reddit
      show: false
      href: https://reddit.com/user/YOUR_REDDIT_USERNAME
      icon: fab fa-reddit
  - medium:
      name: Medium
      show: false
      href: https://medium.com/@YOUR_MEDIUM_USERNAME
      icon: fab fa-medium
  - tumblr:
      name: Tumblr
      show: false
      href: https://YOUR_TUMBLR_USERNAME.tumblr.com/
      icon: fab fa-tumblr
  - blog:
      name: Blog
      show: false
      href: http://host.domain/your_blog
      icon: fas fa-book-open
  - email:
      name: Email
      show: true
      href: mailto:art.is@artissf.com
      icon: fas fa-envelope
  - publickey:
      name: PGP Key
      show: false
      href: https://pastebin.com/raw/YOUR_PUBLIC_KEY
      icon: fas fa-key


# Extra HTML which will be displayed below the links. Keep it short. Leave empty to disable.
#extra_html:
extra_html: >
    Any (multiline) text containing simple HTML,
    such as links or ... lorem ipsum.

#EOF

