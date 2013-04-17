---
layout: page
title: Buttercoin
tagline: Buttercoin is an open source, high-volume trading engine used to arrange trades in an order book.
---


# Buttercoin
Buttercoin is an **open source, high-volume trading engine** used to arrange trades in an order book.

## What Is Buttercoin?
Buttercoin is an open source, high-volume trading engine used to arrange trades in an order book

## Why Do We Need It?
Current exchanges such as MtGox and Bitstamp have run into problems when handling high amounts of load.
Buttercoin would let exchange operators run a high performance trading platform while separating out other concerns (like websocket tickers) that have different scaling characteristics.

## How Can I Help?
If you're a developer, <a href="https://buttercoin.hackpad.com">read through the docs</a>, <a href="https://github.com/buttercoin/buttercoin">fork the repo</a>, and get hacking. There will be tons of opportunity down the line for people to help with websites, documentation, etc.
<a href="irc://irc.freenode.net/#buttercoin">Join #buttercoin on IRC.</a>
                

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


