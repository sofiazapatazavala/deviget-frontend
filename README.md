# Readme: Front-end Test

This file describes the developer's answer to the code challenge of showing Reddit's 50 top posts right now.

## Installation

- Clone this repo.
- Upload the folder to any static or dynamic hosting service.
- There's no step 3. Every piece of code is contained in the HTML file, so it should work.

## Demo
.
A working version of this repo is available at https://szz.cl/deviget-frontend/.

## Usage

- Click on "Get posts" to get the posts.
- Each post will be shown in a card. You can check the thumbnail, title, author, comments, and local submission date. When clicking the thumbnail you will see the full-sized media or link.
- When pressing "List of posts", you will see a list of all 50 posts. When clicking one of the titles, you will see the full-sized media or link.
- To close one card, just click on the x button. If you want to get that one card again, you will have to click on the "get posts" button and reload every post.
- To close all cards, press the button "close all posts". This will remove all posts, and it's irreversible. You will have to reload the page to get all posts again.

## Additional notes

- This repo is using Bootstrap as a front-end framework. There are reasons for this: It doesn't interfere with what's being tested (the developer's Javascript skills), no Javascript functions were used (just the grid and some components, cards and offcanvas), and this version (Bootstrap 5) was developed in native Javascript, so this repo still doesn't have any dependencies.
- Those photos or videos that are marked as NSFW are not shown in this page. When clicking on the thumbnail, the marked media will be shown.
- Posts without a thumbnail will include a "link" image. Clicking on it will show the respective post.

## Licenses

- [Bootstrap is released under the MIT license and is copyright 2021 Twitter](https://getbootstrap.com/docs/5.0/about/license/). Used under the terms of this license.
- Images use graphics from Twemoji. [Copyright 2019 Twitter, Inc and other contributors](https://github.com/twitter/twemoji). Graphics are licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/) and are used under these terms.
