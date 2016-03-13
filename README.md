
# Air

Air theme for [Hexo] based on [light] theme.


## Donating

Support this project and [others by hustcer][gratipay] via [gratipay][].

[![Support via Gratipay][gratipay-badge]][gratipay]

[gratipay-badge]: https://raw.githubusercontent.com/hustcer/htmldemo/master/gittip.png
[gratipay]: https://gratipay.com/hustcer/

Follow:  <a href="http://www.weibo.com/hustcer"><img src="http://img.t.sinajs.cn/t6/style/images/global_nav/WB_logo.png" height="20" width="70" vertical-align="top" ></a>

## Demo

[Demo Blog](http://topdna.org/)

## Install

Execute the following command and modify `theme` in `_config.yml` to `air`.

```
git clone git@github.com:hustcer/hexo-theme-air.git themes/air
```

## Update

Execute the following command to update air.

```
cd themes/air
git pull
```

## Config

Default config:

``` yaml
menu:
  Home: /
  Archives: /archives

widgets:
- search
- category
- tag
- twitter

excerpt_link: Read More

twitter:
  username:
  show_replies: false
  tweet_count: 5

addthis:
  enable: true
  pubid:
  facebook: true
  twitter: true
  weibo: true
  linkedin: true
  google: true
  pinterest: true

fancybox: true

google_analytics:
rss:
```

- **menu** - Main navigation menu
- **widget** - Widgets displaying in sidebar
- **excerpt_link** - "Read More" link text at the bottom of excerpted articles
- **twitter** - Twitter widget config
  - **username** - Twitter username
  - **show_replies** - Enable displaying replies
  - **tweet_count** - Tweets display in widget
- **addthis** - Share buttons at the buttom of articles (Powered by [AddThis])
  - **enable** - Enable share buttons
  - **pubid** - Profile ID of [AddThis]
  - **facebook** - Enable Facebook button
  - **twitter** - Enable Twitter button
  - **weibo** - Enable Sina Weibo button
  - **linkedin** - Enable Linkedin share button
  - **google** - Enable Google+ button
  - **pinterest** - Enable Pinterest button
- **fancybox** - Enable [Fancybox]
- **google_analytics** - Google Analytics ID
- **rss** - RSS subscription link (change if using Feedburner)


[Hexo]: https://hexo.io/
[light]: https://github.com/hexojs/hexo-theme-light
[AddThis]: https://www.addthis.com
[Fancybox]: http://fancyapps.com/fancybox/
