---
title: Understanding Node-Server Add-On Service
layout: default
nav_order: 2
parent: FAQ
---

<head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="https://b3h1z.github.io/HidyBot-Docs/assets/css/style.css">
</head>
<div dir="rtl">
<h2>What is Node-Server Add-On Service?</h2>
<p>Node-adding servers consume a high amount of resources for the bot, requiring us to allocate additional resources to your bot. This is because every few minutes, all users must be synchronized across all nodes.</p>
<h3>Important Points:</h3>
<ul>
    <li>If you have users on a node and want to make them multi-server, you need to merge the node users into the main server. This means that node users become users of the main server, and main server users will also be added to the node server.</li>
    <li>All users on the main server or node server will be multi-server with their previous subscription link.</li>
</ul>
<h3>Understanding the Concept of Node-Addition:</h3>
<ul>
    <li>Example 1: If the main server has 100 users and you create one node, this means 100 node-additions.</li>
    <li>Example 2: If the main server has 150 users and you create two nodes, this means 300 node-additions.</li>
    <li>Example 3: If the main server has 70 users and you create three nodes, this means 210 node-additions.</li>
</ul>
<h3>What Does Node Users Mean?</h3>
<p>Suppose your main server has 170 users and you add a node to it through the bot. These 170 users will also be added to the node server and will be considered node users. Additionally, if you select the option to merge node users into the main server, the node users will also be added to the main server and will be considered node users. In simple terms, the number of users you have on the main server is referred to as node users.</p>
</div>