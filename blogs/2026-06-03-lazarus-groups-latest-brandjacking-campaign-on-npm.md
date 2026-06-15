---
title: "Lazarus Group's Latest: Brandjacking Campaign on npm"
url: "https://www.sonatype.com/blog/lazarus-groups-latest-brandjacking-campaign-on-npm"
date: "2026-06-03"
author: "Sonatype Security Research Team"
feed_url: "https://www.sonatype.com/blog/rss.xml"
---
The Sonatype Security Research team discovered a Lazarus Group campaign distributing dozens of malicious npm packages using brandjacking tactics such as suffix addition and version mimicry to impersonate trusted libraries like Buffer and React. The malicious buffer-utilities package functions as a dropper that retrieves and executes remote payloads, establishing persistent access through a Node.js backdoor that collects system information and communicates with command-and-control servers.
