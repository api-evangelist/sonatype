---
title: "Atomic Arch npm Campaign Adds Malicious Dependency"
url: "https://www.sonatype.com/blog/atomic-arch-npm-campaign-adds-malicious-dependency"
date: "2026-06-11"
author: "research@sonatype.com (Sonatype Security Research Team)"
feed_url: "https://www.sonatype.com/blog/rss.xml"
---
TL;DR On June 11, 2026, Sonatype researchers uncovered Atomic Arch, a new campaign targeting orphaned packages in the Arch User Repository in which attackers take over legitimate, abandoned AUR projects and modify PKGBUILDS to install a malicious npm package during installation. Analysis of atomic-lockfile, the malicious dependency, found a bundled Linux payload with functionality tied to credential harvesting, stealth, anti-debugging, and potential data exfiltration. On June 12, 2026, a second wave emerged, using Bun-based installation paths in some affected packages rather than npm alone.
