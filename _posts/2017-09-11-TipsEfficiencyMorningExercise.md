\---

layout:  post

title:  体能 不能落 · 杂记

category:  murmur

\---

\

# When running the site in a subdirectory (e.g. domain.tld/blog), remove the leading slash (/archives -> archives)

menu:

  home: /

  \#categories: /categories

  archives: /archives

  notes: category/#/notes

  technology: category/#/technology

  vocational: category/#/vocational

  murmur: category/#/murmur

  about: /about

  \#tags: /tags/

  \#sitemap: /sitemap.xml

  \#commonweal: /404.html







\# Enable/Disable menu icons.

\# Icon Mapping:

\#   Map a menu item to a specific FontAwesome icon name.

\



#   Key is the name of menu item and value is the name of FontAwesome icon. Key is case-senstive.

\#   When an question mask icon presenting up means that the item has no mapping icon.

menu_icons:

  enable: true

  \#KeyMapsToMenuItemKey: NameOfTheIconFromFontAwesome

  home: home

  about: user

  categories: th

  schedule: calendar

\# tags: tags

  archives: archive

\# sitemap: sitemap

\# commonweal: heartbeat

  notes: angle-double-right

  technology: angle-double-right

  murmur: angle-double-right

  vocational: angle-double-right