---
weight: 1
title: "Procom CTF 2023"
date: 2023-03-10T07:00:21+05:00
lastmod: 2023-03-10T07:00:21+05:00
draft: true
author: "Saad Akhtar"
authorLink: "https://ssaadakhtarr.github.io/"
description: "Procom CTF arranged by ACM Cyber Security FAST-KHI writeup."
images: []
resources:
- name: "featured-image"
  src: "0.png"

tags: ["ctf", "writeup"]
categories: ["CTF"]

lightgallery: true

toc:
  auto: false
---

This post is focused on the walkthrough of Procom 2023 CTF by FAST-KHI.

<!--more-->

# Web

## Dance

**Description**

![Description](1.png "Description")

**Solution**

On the provided website reading the source code we are provided with an endpoint `/dance.html` which when we visit again provide another endpoint and so on.

`/dance.html` -> `/hackerman.html` -> `/secret_page.html` -> `flag`

![Flag](2.png "Flag")

**Flag:** `procom{DaNce_dAnc3_d4nce}`