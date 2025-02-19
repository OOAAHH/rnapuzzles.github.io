---
title: "Miao Lab - Results"
layout: default
excerpt: "Miao Lab -- Results"
sitemap: false
category: results
permalink: /results/
---
<head>
    <!-- Begin: HEAD Section -->
    <meta charset="utf-8">
    <title>RNA-Puzzles</title>
    <meta name="author" content="Chichau Miao">

    <!-- Mobile Optimization Meta Tags -->
    <meta name="HandheldFriendly" content="True">
    <meta name="MobileOptimized" content="320">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- SEO: Canonical URL, Favicon, and Alternate Feed -->
    <link rel="canonical" href="http://www.rnapuzzles.org/">
    <link href="/favicon.png" type="image/png" rel="icon">
    <link href="/atom.xml" rel="alternate" title="RNA-Puzzles" type="application/atom+xml">

    <!-- Open Graph / Twitter Meta Tags -->
    <meta name="twitter:card" content="summary_large_image">
    <meta property="og:type" content="website">
    <meta property="og:url" content="http://www.rnapuzzles.org/">
    <meta property="og:title" content="RNA-Puzzles">
    <meta property="og:description" content="RNA-Puzzles a community-wide blind evaluation of RNA 3D structure prediction.">

    <!-- jQuery -->
    <script src="/js/jquery-3.2.1.min.js"></script>

    <!-- CSS Files -->
    <link href="/css/bootstrap.min.css" rel="stylesheet" type="text/css">
    <link href="/css/stylish-portfolio.css" rel="stylesheet" type="text/css">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <link href="//jpswalsh.github.io/academicons/css/academicons.css" rel="stylesheet">
    <link href="/stylesheets/screen.css" media="screen, projection, print" rel="stylesheet" type="text/css">
    <!-- End: HEAD Section -->
</head>

<div id="blog-archives" class="category" itemscope itemtype="http://schema.org/Blog">
<meta itemprop="name" content="{{site.title}}" />
{% if site.description %}
<meta itemprop="description" content="{{site.description}}" />
{% endif %}
<meta itemprop="url" content="{{site.url}}" />

{% for post in site.categories[page.category] %}
{% include results.html %}
{% endfor %}

</div>
