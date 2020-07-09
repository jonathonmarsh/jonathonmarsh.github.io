---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_5.jpg
widget1:
  title: "About"
  url: '/about/'
  image: Widget2.jpg
  text: 'About this website'
widget2:
  title: "Running across islands"
  url: '/islands/'
  image: Widget2.jpg
  text: 'Photos from my trips across various islands around Britain.'
widget3:
  title: "Blog"
  url: '/blog/'
  image: Widget3.jpg
  text: 'Read the latest updates - mostly just books I've read'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

