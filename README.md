# topass.github.io
# Site settings
baseURL = "//example.org"
languageCode = "en-US"
title = "Split - HTML Template Demo"
theme = "hugo-split-theme"
disableKinds = ["section", "taxonomy", "taxonomyTerm", "RSS", "sitemap"]

# Enter your tracking code to enable Google Analytics
googleAnalytics = ""

# Copyright
copyright = "&copy;2018 Tony Teo"

[params]

  # Metadata for search engines and social sharing
  author = "Jenny Jones"
  description = "Split is a centrally-divided layout for a professional online presence with a big image or video left with alongside content."
  shareImage = "images/social.jpg"
  twitterHandle = "onepagelove"

  # Favicon
  favicon = "favicon.ico"

  # Section - Visual
  [params.visual]

    # Image
    [params.visual.image]
      enable = true
      file = "images/background.jpg"
      position = "center center"

    # Video
    [params.visual.video]
      enable = false
      mute = true
      file = "videos/background.mp4"
      # youtubeId = "dk9uNWPP7EA"

  # Links
  #
  # Links List #1
  [[params.links]]
    [params.links.list1]
      heading = "Connect"

      [[params.links.list1.link]]
        text = "Blog"
        url = "#"

      [[params.links.list1.link]]
        text = "Email"
        url = "#"

      [[params.links.list1.link]]
        text = "Newsletter"
        url = "#"

  # Links List #2
  [[params.links]]
    [params.links.list2]
      heading = "Social"

      [[params.links.list2.link]]
        text = "Twitter"
        url = "#"

      [[params.links.list2.link]]
        text = "Instagram"
        url = "#"

      [[params.links.list2.link]]
        text = "Dribbble"
        url = "#"

  # Links List #3
  [[params.links]]
    [params.links.list3]
      heading = "Network"

      [[params.links.list3.link]]
        text = "Link One"
        url = "#"

      [[params.links.list3.link]]
        text = "Link Two"
        url = "#"

      [[params.links.list3.link]]
        text = "Link Three"
        url = "#"

  # The original template is released under the Creative Commons Attribution 3.0 License.
  # Please keep the original attribution link when using for your own project.
  # If you'd like to use the template without the attribution, you can check out
  # the license option via the template author's website: https://onepagelove.com/split
