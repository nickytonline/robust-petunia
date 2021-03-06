---
stackbit_url_path: posts/evaluating-the-new-microsoft-edge-4m1j
title: Evaluating the new Microsoft Edge
date: '2019-11-23T02:25:44.000Z'
excerpt: >-
  About a month ago I Tweeted that I was going to take the new MS Edge browser
  for a tour....
thumb_img_path: >-
  https://res.cloudinary.com/practicaldev/image/fetch/s--ORlH7LDT--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://thepracticaldev.s3.amazonaws.com/i/tz6e8mu5mw2o2rx66egy.png
comments_count: 10
positive_reactions_count: 50
tags:
  - browsers
canonical_url: 'https://www.iamdeveloper.com/posts/evaluating-the-new-microsoft-edge-4m1j/'
template: post
---


About a month ago I Tweeted that I was going to take the new MS Edge browser for a tour.


<iframe class="liquidTag" src="https://dev.to/embed/twitter?args=1180654867850903552" style="border: 0; width: 100%;"></iframe>



<iframe class="liquidTag" src="https://dev.to/embed/twitter?args=1181245028280213504" style="border: 0; width: 100%;"></iframe>


So the first thing I did was [grab the Edge Beta](https://www.microsoftedgeinsider.com/en-ca/) since there is currently no official release yet. I am using a Mac, so all the following applies to Mac usage.

Once installed, I enabled sync by logging in with my Microsoft account. This is pretty standard browser stuff. FireFox and Chrome do this as well. I guess the one caveat is that if you do not have a Microsoft account, you will need to create one if you wish to sync your settings.

So far so good. The next thing was to install all the Chrome extensions that I had installed on Chrome and Brave browser. Once again, this process was fairly easy. The only thing that was required was to allow extensions to be installed from an external source, i.e. the Chrome Web Store.

After a month of usage, I can say that it pretty much behaves as I would expect a Chromium-based browser to work. The one thing I do not like, and maybe this is just because it is a beta build for the time being, but having to go through the Microsoft update application is annoying. I would rather it just auto-update like Chrome or Brave does. This is minor, but this is a review. 😉

For mobile, it was pretty easy to find and install in the Apple App Store. I have not tried it on an Android device, but I imagine it's just as easily available from the Google Play Store.

![Install MS Edge for iOS](https://www.iamdeveloper.com/img/install_edge_ios.png "Install MS Edge for iOS")

I started to use it daily on my phone. Overall, I did not notice any issues except for one on GitHub. It does not seem able to load contributor graphs or the GitHub feed. I have no idea why and did not take the time to investigate. I am sure this will get sorted, but it is worth a mention. Perhaps other sites have similar issues, but for the life of a software developer, this appeared to be the only site that I experienced this.

![MS Edge on iOS not loading GitHub feed](https://www.iamdeveloper.com/img/ms_edge_ios_issues_loading_github_feed.png "MS Edge on iOS not loading GitHub feed")

Another odd thing that I experienced on Github was that it was reporting Edge as an outdated version of Safari. Maybe this is a user agent thing. I am not sure.

![MS Edge on iOS warning about being an old version of Safari on GitHub site](https://www.iamdeveloper.com/img/ms_edge_ios_github_not_supporting_old_safari.png "MS Edge on iOS warning about being an old version of Safari on GitHub site")

The one thing that I do not understand is why they provide a continue browsing later feature if it is not supported on macOS and Linux, since the feature clearly states to have the latest version of Windows installed on your PC. Once again, the browser is currently in BETA, so I imagine, this will get sorted out.

![MS Edge Browse Later Screen on iOS](https://www.iamdeveloper.com/img/ios_browse_later.png "MS Edge Browse Later Screen on iOS")

![MS Edge Browse Later Help Page for iOS](https://www.iamdeveloper.com/img/browse_later_help_page.png "MS Edge Browse Later Help Page for iOS")

Those things are somewhat minor, but the big one for me was about a week or two ago, I started getting warning messages about legitimate sites I browse every day being considered as unsafe, i.e. [https://dev.to](https://dev.to), [https://netlify.com](https://netlify.com) to name a couple.

![MS Edge on iOS reporting legitimate site as unsafe](https://www.iamdeveloper.com/img/unsafe_site_edge.png "MS Edge on iOS reporting legitimate site as unsafe")

In the end, I found this too annoying and reverted back to using Brave browser on my mobile.

I will just end with this. The new Microsoft Edge is still in Beta, so the annoyances and errors I mention above will probably get sorted out.

In the meantime, I am going to Tweet them this post to provide them with my constructive feedback.

*[This post is also available on DEV.](https://dev.to/nickytonline/evaluating-the-new-microsoft-edge-4m1j)*


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
