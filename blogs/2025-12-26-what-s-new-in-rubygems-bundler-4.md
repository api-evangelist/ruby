---
title: "What's New in RubyGems/Bundler 4"
url: "https://blog.rubygems.org/2025/12/26/whats-new-rubygems-bundler4.html"
date: "2025-12-26"
author: "Hiroshi SHIBATA"
feed_url: "https://blog.rubygems.org/atom.xml"
---
Ruby 4.0.0 was released on December 25, 2025 , and RubyGems/Bundler 4.0.3 is now bundled with Ruby 4.0.0. Since my previous post focused on migration and compatibility concerns , I’d like to highlight some of the exciting new features in this release. Parallelization of C-extension Gem Builds Add MAKEFLAGS=-j by default before compiling When installing gems with C extensions (such as mysql2 or pg ), RubyGems now automatically adds MAKEFLAGS=-j to the make command for parallel execution.
