---
title: "Security advisory: Possible leak of legacy API keys via improper cache configuration"
url: "https://blog.rubygems.org/2026/07/22/security-advisory-legacy-api-key-leak.html"
date: "2026-07-22"
author: "Colby Swandale"
feed_url: "https://blog.rubygems.org/atom.xml"
---
A CDN caching bug on RubyGems.org could hand one account’s API key to another person for up to an hour. If you signed in to RubyGems.org with a gem client older than v3.2.0, your key could have been exposed (the technical details are below). Currently, 18% of sign-ins through gem signin come from an affected version, and for the first several years of this bug, before we changed the client’s sign-in path in December 2020, it was every gem client.
