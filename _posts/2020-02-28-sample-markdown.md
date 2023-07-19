---
layout: post
title: Site-to-site VPN with Wireguard between OpenWRT and Mikrotik
subtitle: Simple VPN solution with Wireguard
tags: [Mikrotik, OpenWRT, OSPF, Wireguard]
comments: true
---
So here is the thing, I needed to create a site-to-site VPN between a Mikrotik and OpenWrt device, the OpenWrt is behind NAT. I was looking at some options but I decided to try Wireguard as I have good experience with it in a normal access scenario. Here is the topology:

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg)

You need install the right packages in Openwrt:

