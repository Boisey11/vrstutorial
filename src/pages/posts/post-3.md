---
layout: ../../layouts/MarkdownPostLayout.astro

title: My Third Blog Post
author: Astro Learner
description: "I had some challenges, but asking in the community really helped!"
image:
    url: "https://docs.astro.build/assets/rays.webp"
    alt: "Thumbnail of Astro rays."
pubDate: 2022-07-15
tags: ["astro", "learning in public", "setbacks", "community"]
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
        <h1> This is a test sentence for the third blog </h1>
        <p>It wasn't always smooth sailing, but I'm enjoying building with Astro. And, the [Discord community](https://astro.build/chat) is really friendly and helpful!</p>
	</body>
</html>