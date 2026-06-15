---
title: "New Shai-Hulud Miasma Wave Hits Hundreds of npm Packages"
url: "https://www.sonatype.com/blog/new-shai-hulud-miasma-wave-hits-hundreds-of-npm-packages"
date: "2026-06-04"
author: "Sonatype Security Research Team"
feed_url: "https://www.sonatype.com/blog/rss.xml"
---
A fresh malware campaign has compromised 304 npm package versions by abusing binding.gyp files to execute malicious code during installation, bypassing traditional package.json script detection. The attack steals credentials and uses them to publish additional malicious versions, creating a self-propagating supply chain threat. Organizations with affected installations should assume compromise, rotate credentials immediately, and implement continuous governance rather than relying on one-time trust decisions.
