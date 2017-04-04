---
layout: project
title: React Hydra
description: Server-side rendering for those of us who aren't on the node js stack.
date: 2015-11-01 12:00:00
allowSocial: true
allowComments: true
---
After the initial wierdness of jsx, React js is a great tool for building complicated web stuff. Luckily for those with a node js back-end it has a function called React.renderToString() which allows the server render and send those complicated components to the client. The benefits of doing this are twofold; A slight saving in render time for the client, and more importantly, SEO! That's all good and well for those already on node js but for everyone else there are not a lot of options other than phantom js.

What is it?
-----------

React Hydra exposes the ```React.renderToString()``` and ```React.renderToStaticMarkup()``` methods within React js as a HTTP service. It is intended as a way of using a React js front-end without losing the benefits of SEO in non-javascript server languages.

Find it on GitHub
-----------------

More details on the installation and configuration can be found at [https://github.com/mr-damagii/react-hydra](https://github.com/mr-damagii/react-hydra)
