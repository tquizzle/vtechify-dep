---
layout: post
title: Unmount pesky CD-ROMs from VMs
excerpt: 
modified: 2014-07-29
tags: [CDROM, PowerCLI, Unmount]
comments: true
image:
  feature: 
---

Sometimes you need to quickly remove CDROMs from VMs to not violate vMotion or just because you're lazy and forgot to unmount them when you were finished. Either way, those CDROMs should not be forever mounted to your VMs. This can only cause problems for you in the future.

So, if you need a quick PowerCLI one-liner to do that for you, look no further.

<script src="https://gist.github.com/tquizzle/f92d3081118d07049c0e.js"></script>
