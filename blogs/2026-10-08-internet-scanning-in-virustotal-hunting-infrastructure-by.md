---
title: "Internet Scanning in VirusTotal: hunting infrastructure by what it exposes"
url: "https://blog.virustotal.com/2026/10/internet-scanning-in-vt.html"
date: "2026-10-08"
author: "noreply@blogger.com (Joseliyo Sánchez)"
feed_url: "https://blog.virustotal.com/feeds/posts/default?alt=rss"
---
Until now, an IP report in VirusTotal told you a lot about reputation, who hosts it, what resolves to it (passive DNS) and which files talk to it . It told you nothing about what the machine itself was running. VirusTotal now scans the public IPv4 space every day and stores, for each IP, the open and closed ports, the service behind each port, its banner and its fingerprints.
