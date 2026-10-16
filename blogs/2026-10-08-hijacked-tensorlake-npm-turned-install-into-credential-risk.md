---
title: "Hijacked TensorLake npm Turned Install Into Credential Risk"
url: "https://www.sonatype.com/blog/hijacked-tensorlake-npm-turned-install-into-credential-risk"
date: "2026-10-08"
author: "research@sonatype.com (Sonatype Research Team)"
feed_url: "https://www.sonatype.com/blog/rss.xml"
---
TL;DR A malicious release of TensorLake's TypeScript SDK, tensorlake@0.5.144 , used an install hook to search for developer credentials and accept remote commands. Sonatype's code review found that its GitHub fallback could create a public repository and commit collected data, including a stolen GitHub token in one path, and that the malware could modify accessible repositories by committing .claude and .vscode files. The loader exits under several common CI environment markers, so the payload's separate GitHub Actions logic does not establish broad CI infection.
