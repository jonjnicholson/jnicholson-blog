+++
title = "How I Use Tailscale"
date = "2023-06-18T17:44:03-04:00"
author = ""
authorTwitter = "" #do not include @
cover = ""
tags = ["technology", "vpn", "tailscale"]
keywords = ["", ""]
description = "How I'm using Tailscale to secure my personal devices"
showFullContent = false
readingTime = false
hideComments = false
+++

## What is it?
> [Tailscale](https://tailscale.com/kb/1151/what-is-tailscale/#the-benefits) is a VPN service that makes the devices and applications you own accessible anywhere in the world, securely and effortlessly. It enables encrypted point-to-point connections using the open source WireGuard protocol, which means only devices on your private network can communicate with each other.

It has a very generous free tier that includes most of the features included in the higher paid tiers while limiting you to 100 devices--more than enough for my use cases.

## Where does it work?
Tailscale also has apps and integrations with all the operating systems and devices that I require. I have it installed on my [pi-hole](https://pi-hole.net/) and [home assistant](https://www.home-assistant.io/) Raspberry Pi's as well as my iPhone, Mac, and [Synology NAS](https://www.synology.com/en-us).

## Ad blocking
I have been casually using Tailscale, but I recently read this [post](https://tailscale.com/kb/1114/pi-hole/) that explained how to use Tailscale in coordination with your Pi-Hole to get ad-blocking even when I'm not at home.

One issue I ran into was covered by the [troubleshooting](https://tailscale.com/kb/1114/pi-hole/#troubleshooting) section of the previously mentioned article, but the UI of my Pi-Hole running versions `
Pi-hole v5.17.1 FTL v5.23 Web Interface v5.20.1` did look a little different.

## Using Tailscale while traveling
Another aspect of Tailscale I recently learned is the concept of [exit nodes](https://tailscale.com/kb/1103/exit-nodes/).
> The exit node feature lets you route all non-Tailscale internet traffic through a specific device on your network.

This means that I can use Tailscale in place of other VPN options to secure my internet traffic when I'm traveling and using public wifi.

## Conclusion
I'm very happy with how powerful Tailscale is as well as how great the documentation is. The free tier is extremely useful and I'm surprised that they offer all they do in the tier. 
