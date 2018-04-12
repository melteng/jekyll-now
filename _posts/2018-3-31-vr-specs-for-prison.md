---
layout: post
categories: [reentry, blog]
title: Technical specs for virtual reality in prisons
tags: thesis reentry
---

Designing for prison has many constraints (this is the understatement of the century). We want to bring a simple VR demo to prison, which is turning out to be both more challenging than anticipated and a blessing in disguise. For me, it's been a great crash course in the opportunities and limitations of VR as a new medium. Here are some technical challenges we've been working around as we design for such a constrained environment:

1. #### No wifi and no cellphones
Everything we design needs to work for offline, meaning the VR experience we are looking for that cannot depend on phone-based experiences. I've been exploring the incredibly vibrant ecosystem of WebVR (via [A-Frame](https://aframe.io/) and [Glitch](https://glitch.com/)), but now that we have to use heavy-duty VR headsets like the Vive, this opens up a lot more possibility for complex graphics rendering and location-based interactivity.

2. #### Portable set-ups
Headsets need to be attached to a computer for rendering and these computers can be in the form of laptops or towers. For us, the more portable the better, so we need to work with fairly powerful laptops usually for gaming. Turns out many VR labs we know have stationary (powerful tower-based, "come to us") set-ups. This is an interesting accessibility challenge. Who is their intended audience? \\
We have been testing with the Lenovo Explorer headset, which is not as powerful as the HTC Vive but purportedly one of the easier and more portable headsets to set up (10-min set-up process, no installation of physical sensors required). Even so, it still requires a PC with specs as powerful as 2017 Surface models:
- **Windows 10** Home, Pro, Business, or Education
- **Intel Core 15 7200U** (7th generation mobile), dual-core with Intel® Hyper-Threading Technology enabled (or better)
- **8GB** DDR3 duel channel RAM
- **Intel HD Graphics 620**, DX12-capable integrated GPU; NVIDIA MX150/965M (or greater) DX12-capable discrete GPU
- Windows Display Driver Model (WDDM) 2.2  for graphics
- HDMI 2.0 or DisplayPort 1.2 (needs to support 4K)
- USB 3.0 Type-A or Type-C
- **At least 10 GB** free disk space
-  Bluetooth 4.0
- ideally at least 15" screen size\\
(*Having to answer, "How powerful does your laptop need to be?" has been a nice primer on what these acronyms mean. Handy for talking with IT and tech guys who assume girls aren't as technologically literate.* 🙄)

3. #### Security check everything
This isn't so much technical as it is about being extra prepared. We have to get every piece of technology ok-ed before we bring it into prison, which means A) knowing what we're bringing well beforehand and B) documenting each piece of technology in language/images that laymen can understand adequately enough to assess potential risk. This is one of those *inclusive design* aka "design for the margins first" lessons that would be helpful in any project.
