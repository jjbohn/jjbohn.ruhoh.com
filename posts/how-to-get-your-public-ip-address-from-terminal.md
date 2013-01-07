---
title: How to get your public IP address from the terminal
date: '2013-01-07'
description:
categories: [cheat sheet]
---

Came across this little command the other day. This does a simple GET request to http://ifconfig.me, which returns your IP address.

```curl ifconfig.me```

There are also a few other commands that can give you other information including your hostname, user agent, etc. You can get it return in json, xml or plain text. I encourage you to checkout http://ifconfig.me on the web to see them all.

There are a few services to retrieve your public facing IP address, but I think this one is the nicest/easiest to remember.
