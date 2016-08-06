# Modernist

> Theme for [Hexo]. Based on Hexo default light theme, forked from [modernist theme].  

[Demo the Theme]

## Install

Execute the following command and modify `theme` in `_config.yml` to `modernist`.

```
git clone git@github.com:bruce-sha/hexo-theme-modernist.git themes/modernist
```

## Update

Execute the following command to update Modernist.

```
cd themes/modernist
git pull
```

## Config

Default config:

``` yaml
menu:
  Home: /
  Archives: /archives

excerpt_link: Read More
archive_yearly: false

widgets:
  - category
  - tag
  - tagcloud
  - recent_posts
  - blogroll

blogrolls:
  - bruce sha's hexo blog: http://ibruce.info

fancybox: true

duoshuo_shortname:

google_analytics:
rss:
```

- **menu** - Main navigation menu
- **excerpt_link** - "Read More" link text at the bottom of excerpted articles
- **archive_yearly** - Enable archives grouped by year, only for nonpaged (set the pagination config: `archive: 1`)
- **widgets** - Widgets displaying in sidebar
- **blogrolls** - Blogrolls displaying in `blogroll` widget
- **fancybox** - Enable [Fancybox]
- **duoshuo_shortname** - [Duoshuo] ID
- **google_analytics** - Google Analytics ID
- **rss** - RSS subscription link (change if using Feedburner)

[Hexo]: http://zespia.tw/hexo/
[modernist theme]: http://github.com/heroicyang/hexo-theme-modernist
[Demo the Theme]: http://ibruce.info
[Duoshuo]: http://duoshuo.com
[Fancybox]: http://fancyapps.com/fancybox
[Busuanzi]: http://busuanzi.ibruce.info