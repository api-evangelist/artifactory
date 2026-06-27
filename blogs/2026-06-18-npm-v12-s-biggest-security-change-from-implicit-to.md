---
title: "npm v12's Biggest Security Change: From Implicit to Explicit Trust"
url: "https://jfrog.com/blog/npm-v12-from-implicit-to-explicit-trust/"
date: "2026-06-18"
author: "drewt"
feed_url: "https://jfrog.com/blog/feed/"
---
npm v12 shifts from implicit to explicit trust by blocking three high-risk installation mechanisms by default: script execution, Git dependencies, and remote URLs. The JFrog Security Research Team found these vectors involved roughly 53% of malicious npm attacks over the past year, with lifecycle scripts alone accounting for 46% of malicious packages.
