---
title: "Cert’s up: Using self-signed TLS to encrypt Cribl-to-Cribl data streams"
url: "https://cribl.io/blog/certs-up-using-self-signed-tls-to-encrypt-cribl-to-cribl-data-streams"
date: "2026-05-27"
author: "Cribl"
feed_url: "https://cribl.io/feed/"
---
If you've ever configured TLS certificates from scratch, you know the pain: Google it, copy-paste some OpenSSL commands, something doesn't work, Google it again, and an hour later read a Stack Overflow thread from 2014 written by someone who seems personally offended by the question. Good times. Recently I needed to set up TLS between a Stream Worker and Edge Node, a pretty standard "I want my data encrypted in transit for reasons" ask.
