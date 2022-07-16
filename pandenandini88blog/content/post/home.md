---
title: "Home"
date: 2022-07-16T10:58:07-04:00
draft: false
---

# This is my post

<ul>
    {{ range .discography }}
      <li>{{ . }}</li>
    {{ end }}
    </ul>
