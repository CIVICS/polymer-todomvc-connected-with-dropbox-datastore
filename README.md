# Polymer TodoMVC Example

This is a sample to show how to use dropbox datastore api using [Polymer](https://www.polymer-project.org/).

You can see original README of this TodoMVC app [here](https://github.com/Polymer/todomvc).

## Custom Element

I also developed custom element to use dropbox datastore api.
Please check it. This app is sample for it.

[polymer-dropbox-datastore](https://github.com/kashiro/polymer-dropbox-datastore)


## How to use this sample in local

According to dropbox data store api [documents](https://www.dropbox.com/developers/apps), We can use dropbox api in local (http://localhost is allowed to use for auth).

I tried but I could not use localhost to auth.

So if you want to use this app you have to prepare `https` environment (like dropbox public directory or github pages). 

* create dropbox app in [app console page](https://www.dropbox.com/developers/apps)
* set `Redirect URIs` in app console (you have to set `https` url)
* change app key in `index.html` (appKey attribute in `dropbox-datastore` custom tag)
* deploy `https` environment :)

## Demo

I deployed this app on github pages.
But my dropbox app is limited only 100 user can use it. (now in review to public)

[https://kashiro.github.io/polymer-todomvc-connected-with-dropbox-datastore/](https://kashiro.github.io/polymer-todomvc-connected-with-dropbox-datastore/)

## Reference

* [Dropbox Datastore API](https://www.dropbox.com/developers/datastore/tutorial/js)
