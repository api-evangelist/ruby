---
title: "Cool down before you install: give new gems a few days to be vetted"
url: "https://blog.rubygems.org/2026/06/03/cooldown-let-new-gems-be-vetted.html"
date: "2026-06-03"
author: "Hiroshi SHIBATA"
feed_url: "https://blog.rubygems.org/atom.xml"
---
Most supply-chain attacks against RubyGems exploit a narrow window: an account is compromised, a malicious version ships, and any bundle install in the minutes that follow resolves straight to it. Bundler 4.0.13 introduces cooldown , a time-based filter that refuses to resolve to a version until it has been public for at least N days. Releases too new to have been scrutinized are passed over in favor of ones that have aged past the window.
