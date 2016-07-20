---
title: iOS IRC Clients
author: irchelp.org staff
layout: default
---

## A word of warning about Apple's background app restrictions

Apple imposes severe limits on applications written for iOS. Under Apple's
strict rules, very few applications qualify for background data or for exemption
from automatic suspension. Generally, in the case of chat applications, Apple's
stance is that those applications must be implemented with push notifications.

As mobile push notifications are obviously not part of the IRC protocol, this
means that any application that wants to evade these restrictions has to either
provide a proxy for all of its users, require its users to set up a proxy for
for themselves, or be specific to one IRC network, which provides the requisite
push support.

Some applications have tried to cheat these rules over the years by playing
inaudible tones over the speaker in order to be classed as audio streaming
apps. Apple however, considers this a violation of the app store guidelines.

Unfortunately, this stance from Apple leaves virtually all of the iOS clients
almost unusable. This is not a fault of the application developers, it is
entirely a result of Apple's draconian platform restrictions.

## Colloquy
[Colloquy](http://colloquy.mobi/), one of the staples of MacOS desktop clients,
also makes an appearance on iOS in the form of a mobile version.  There is support
for push notifications [using a special bouncer](http://colloquy.mobi/bouncers.html)
to allow background connectivity without falling victim to Apple's aggressive app
suspend, but you'll have to run the bouncer on a desktop system or dedicated server
of your own in order to get it to work.


## LimeChat
Also a transplant from the MacOS desktop, [LimeChat](http://limechat.net/iphone/) is an IRC client for all iOS devices.
It supports SSL connections and SASL authentication, as well as automatic nickserv
authentication on non-SASL networks.