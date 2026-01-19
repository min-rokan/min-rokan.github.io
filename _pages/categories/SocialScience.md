---
  title: "SocialScience"
  layout: archive
  permalink: categories/SocialScience
  author_profile: true
  sidebar_main: true
  ---
  
  { assign posts = site.categories.SocialScience }
  { for post in posts } { include archive-single.html type=page.entries_layout } { endfor }