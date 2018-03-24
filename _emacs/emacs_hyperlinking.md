---
layout: post
title:  "Hyperlinking"
date: 2018-03-24
---

Hey! Organising information is *super* fun with Org mode. Collecting information is a tough job and sometimes you can't paraphrase or capture everything the way you want, sometimes you are need to reference a lot of different articles out there on the web, or maybe there's no better way to appreciate a piece of writing or music without going directly to the source. This is where hyperlinking comes in, and it's easy to manage too.

Simply put the link on the left and title or description on the right using the following syntax below:

```
[[link][description]]
[[https://www.youtube.com/watch?v=xZDJyBikt-A][Kamen Rider OOO: Reverse/Re:birth]]
```
Which would look a lot like [Kamen Rider OOO: Reverse/Re:birth](https://www.youtube.com/watch?v=xZDJyBikt-A). 

This is what I'm listening to right now as I type this out. The song is also quite fitting to describe how Org mode's syntax for capturing hyperlinks closely resembles markdown syntax but perhaps in a reverse manner.

What's realy fun about this is how you are able to open the link in your text editor with a mouse-click, or even better without removing your hands from the keyboard, using `C-c C-o`. This keystroke invokes the command `markdown-follow-link-at-point`. 

(NB: you can verify this by running [`C-h k key-sequence`](https://stackoverflow.com/questions/965263/given-an-emacs-command-name-how-would-you-find-key-bindings-and-vice-versa), or just follow the link for an awesome Stack Overflow post.)

Great stuff Emacs and Org-mode. I also learned a thing or two while just writing this post.
