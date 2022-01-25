---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Hello world!
publishDate: 21 Jan 2022
name: SetiZ
value: 128
description: Just a Hello World Post!
---

<Cool name={frontmatter.name} href="https://twitter.com/funkysetiz" client:load />

This is so cool!

Do variables work {frontmatter.value * 2}?