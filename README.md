# mutant.city
This is my old personal site before being ported to Wordpress. It is no longer functional.

* Site is build with [middleman](https://middlemanapp.com/) ruby static site generator to handle the content and to generally make html more extensible.
* The javascript title bar is handled with [riot.js](http://riotjs.com/) web components and really neat micro-lib called [baffle.js](https://camwiegert.github.io/baffle/).
* The login is a little hack of an html particle engine called [proton.js](http://a-jie.github.io/Proton/).
* I made a template for sites like these that can be found here: [https://github.com/nick-templates/middleman_starter](https://github.com/nick-templates/middleman_starter) 

###  Notes
* This site is hosted on a non-root github pages repo, yet it has https! How you may ask?  The glory of cloudflare: [https://blog.keanulee.com/2014/10/11/setting-up-ssl-on-github-pages.html](https://blog.keanulee.com/2014/10/11/setting-up-ssl-on-github-pages.html)
* It appears all request's go through the cloud flare network which then fetches you page for serving.
* Downside is that there's a delay in updating which could inhibit development because of caching.  But I just turn off caching for dev.
