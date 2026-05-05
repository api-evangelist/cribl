---
title: "Federated security observability: Investigating bot traffic with Cribl Search and Hydrolix"
url: "https://cribl.io/blog/federated-security-observability-investigating-bot-traffic-with-cribl-search"
date: "Mon, 13 Apr 2026 01:00:00 GMT"
author: "Cribl"
feed_url: "https://cribl.io/feed/"
---
For most web platforms, a significant share of incoming traffic isn't human. Bots crawl product catalogs, scrape pricing data, probe APIs, and manipulate request patterns in ways that quietly erode performance. Some of that is benign. A lot of it isn't. When latency starts climbing and cache hit rates begin to drop, bot traffic is often the culprit, and the harder-to-catch variety doesn't look like an attack. It mimics normal browsing behavior closely enough to stay under the threshold of your existing defenses, quietly degrading performance, impacting metrics, and blocking legitimate users from interacting with your content. This post shows how you can use federated queries from Cribl Search into Hydrolix to analyze CDN logs and origin application telemetry from a single interface to detect a common bot issue—cache busting. In this scenario, automated traffic targets an inventory API, bypasses the cache, and overloads the origin server.
