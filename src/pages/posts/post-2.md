---
layout: ../../layouts/MarkdownPostLayout.astro

title: My Second Blog Post
author: Astro Learner
description: "After learning some Astro, I couldn't stop!"
image:
    url: "https://docs.astro.build/assets/arc.webp"
    alt: "Thumbnail of Astro arcs."
pubDate: 2022-07-08
tags: ["astro", "blogging", "learning in public", "successes"]
---

<style>
	html{
		background-color: #f1f5f9;
    	font-family: sans-serif;
	}

	body {
		margin: 0 auto;
		width: 100%;
		max-width: 80ch;
		padding: 1rem;
		line-height: 1.5;
  	}
	* {
    	box-sizing: border-box;
  	}

	h1{
		margin: 1rem 0;
    	font-size: 2.5rem;
	}
</style>

<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="utf-8" />
		<link rel="icon" type="image/svg+xml" href="/favicon.svg" />
		<meta name="viewport" content="width=device-width" />
		<meta name="generator" content={Astro.generator} />
		<title>Second Page</title>
	</head>
	<body>
		<a href="/">Home</a>
        <a href="/about/">About</a>
        <a href="/blog/">Blog</a>
        <h1> This is a test sentence for the second blog </h1>
        <h1>TEST TEST TEST</h1>
        <p>After a successful first week learning Astro, I decided to try some more. I wrote and imported a small component from memory!</p>
	</body>
</html>
