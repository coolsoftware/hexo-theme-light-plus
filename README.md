# Light Plus

A simple theme for [Hexo](https://hexo.io/).

It has been forked from https://github.com/hexojs/hexo-theme-light

## Install

Execute the following command and modify `theme` in `_config.yml` to `light-plus`.

``` bash
git clone --depth 1 https://github.com/coolsoftware/hexo-theme-light-plus themes/light-plus
```

For basic installation and configuration instructions please refer to original repository.

## Demo

https://blog.coolsoftware.ru/

## New Widgets

3 widgets has been added: `archive`, `favoriteposts`, `contactlinks`. You can turn them on and configure in theme `_config.yml`:

``` yaml
widgets:
- archive
- favoriteposts
- contactlinks

contact_links:
-
  github: https://github.com/coolsoftware/
-
  mailto: emailme@gmail.com
-
  url: https://google.com/

favorite_posts:
-
  name: Useful Links
  url: tags/useful-links/
```

## Title Image

You can use image in the blog title. Place your image file (e.g, `title-image.png`) into `source/images` folder and add to `_config.yml`:

``` yaml  
title:
  image: images/title-image.png
```

## Archives Navigation

Blog archive navigation menu has been added. You can choose year and month:

![blog-archive-navigation](https://user-images.githubusercontent.com/1533483/152324256-978c2cbe-05e8-480c-8a34-75107d5125f4.png)

