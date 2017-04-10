---
title: "Tech Stack: What Am I Building It With?"
date: "2017-04-10"
layout: post
permalink: "/blog/tech-stack"
---

[Vulcan.js](http://vulcanjs.org/) is what I've started exploring in detail. I hail from a non CS background. Since this would not be a traffic intensive website, I'm using Vulcanjs (with is a framework on top of [Meteorjs](https://www.meteor.com/f)) because even though there are some intial load performance trade offs, since it's a non profit website, I can simply use service workers to increase the perceived performance from second time load onwards. Vulcanjs uses React, Redux, GraphQL on the client; and nodejs as its backend layer, and MongoDB as its persistent storage.

I've explored [firebase](https://firebase.google.com/) for a serverless architecture in detail but have found it a little limiting. I've not explored SQL options, since it would take my time (which is a pathetic reason to give I know)