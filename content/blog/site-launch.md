---
title: "Website Launch!"
date: 2018-03-31T07:33:59-04:00
draft: false
---

As of today, [bushidoboy.com](https://bushidoboy.com) has officially launched. I'm pretty happy and excited about it.

I started working on this site about a week ago just in my spare time at work, but I did enough work and was proud enough of it to launch this site for real. Purchased the domains -- bushidoboy.xyz also resolves to this site -- and set up my VPS with Caddy and a seamless deploy.

Now for some technical notes because I enjoy geeking out about some of this stuff:

This site was created using the Hugo static site generator. I like the idea of a generator that takes bits and pieces of HTML and stitches them together into a consistent experience. I'm using the ananke theme, simply due to it being used in their tutorial. However, I'm sticking with it because of the CSS framework that was chosen to power it: Tachyons. 

I've tried several CSS frameworks across the multiple times I've tried getting into web development; Bootstrap, Kube, Foundation, UIkit, etc. and I've never felt very productive using them. I like Tachyons because it feels less like its own framework and more like shorthand for useful CSS properties:

{{< highlight css >}}
.dn {
	display: none;
}

.pv4 {
	padding-top: var(--spacing-large);
	padding-bottom: var(--spacing-large);
}
{{< / highlight >}}

With this, it's very easy to compose properties into elements on the page to get them to do exactly what I want. The only criticism I can come up with is that it can create some very long and unwieldy `class` strings on some elements like navigation menus and such. 

I will say that the breakpoint system of `not-small`, `medium` and `large` was a little confusing at the beginning, but I believe that's more due to my inexperience with responsive design and not because of Tachyons. Still, I'm very happy ananke introduced me to this wonderful little CSS toolkit, and I'll be using it for the foreseeable future.

On the server side, Caddy is a great piece of software. I was exposed to Caddy by someone in IRC, and it's interested me for a very long time. The Caddyfile has a simple and readable configuration, supports SSL out of the box, and renews SSL certs automatically. This and the extensive plugins collection made Caddy a top choice for me, and I can say that my experience with it has been very nice. 

There were definitely easier options for me to get this website off the ground, but making and supporting my own website has been a goal of mine for years. I'm very happy with the results so far and I'll continue to develop this to my satisfaction.

Thank you for visiting, whoever you are. I truly and deeply appreciate it. Please stay a while, if you would be so kind.

Welcome, friend.