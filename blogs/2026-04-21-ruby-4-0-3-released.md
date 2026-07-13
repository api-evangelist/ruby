---
title: "Ruby 4.0.3 Released"
url: "https://www.ruby-lang.org/en/news/2026/04/21/ruby-4-0-3-released/"
date: "2026-04-21"
feed_url: "https://www.ruby-lang.org/en/feeds/news.rss"
---
Ruby 4.0.3 has been released. This release only contains ERB 6.0.1.1, which fixes CVE-2026-41316 . If your application calls Marshal.load on untrusted data AND has both erb and activesupport loaded, please update your ERB to 4.0.3.1, 4.0.4.1, 6.0.1.1, 6.0.4 or later.
