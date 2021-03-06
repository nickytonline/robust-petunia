---
stackbit_url_path: posts/accessing-assetpath-in-webpacker-js-erb-pack-18g3
title: Accessing asset_path in webpacker *.js.erb pack
date: '2020-02-18T22:49:11.880Z'
excerpt: >-
  I’ve configured webpacker to be able to process ERBs (bundle exec rails
  webpacker:install:erb) becaus...
thumb_img_path: null
comments_count: 6
positive_reactions_count: 15
tags:
  - help
  - rails
canonical_url: >-
  https://www.iamdeveloper.com/posts/accessing-assetpath-in-webpacker-js-erb-pack-18g3/
template: post
---
I’ve configured webpacker to be able to [process ERBs](https://github.com/rails/webpacker# erb) (
`bundle exec rails webpacker:install:erb`
) because I need paths generated by Sprockets' 
`asset_path`
 at build time so that I get properly generated asset URLs.

The ERB integration works with the simple example that you get after installing ERB/Webpacker integration, but I’m wondering how to have access to 
`asset_path`
. From what I’ve found so far, it doesn’t appear to be possible, https://github.com/rails/webpacker/issues/284.

Does anyone know if it's possible? In the meantime, I will keep digging 😉

![Person slipping and sliding while attempting to shovel snow](https://media.giphy.com/media/ZIK2f5hBbnyyA/giphy-downsized-large.gif)

*[This post is also available on DEV.](https://dev.to/nickytonline/accessing-assetpath-in-webpacker-js-erb-pack-18g3)*


<script>
const parent = document.getElementsByTagName('head')[0];
const script = document.createElement('script');
script.type = 'text/javascript';
script.src = 'https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/4.1.1/iframeResizer.min.js';
script.charset = 'utf-8';
script.onload = function() {
    window.iFrameResize({}, '.liquidTag');
};
parent.appendChild(script);
</script>    
