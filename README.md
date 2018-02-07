# BobbleHeadCMS

BobbleHead CMS is a pure-Javascript CMS that uses HTML5, CSS and Javascript to generate your pages and to interface optionally with a Rest-Server.
It allows to create front-end in a really fast and simple way (just writing a simplified XHTML).
The CMS allows you to define a multi-pages webapp and to fill this pages with tables, forms, images and others.

## Project Status
- ### CMS Core
       - [x] Access Menaging
       - [x] Page Loding
       - [x] Database (delegated to PouchDB)
       - [ ] Cacher (to resolve request uid problem)
       - [x] Router
       - [x] AppController (application configuration reader)
       - [x] Internal / External Communicator
       - [ ] Event Trigging
- ### Rest - WADL Communicator
       - [ ] WADL Reader (almost completed)
       - [ ] Models generator
- ### XHTML Page Composer
       - [ ] XPAG Reader
       - [ ] XPAG Render

## Library Used
- PouchDB [a link](https://github.com/pouchdb/pouchdb)
- mustache.js [a link](http://mustache.github.io/)

## Basic Usage