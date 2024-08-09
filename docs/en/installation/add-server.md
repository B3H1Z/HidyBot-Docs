---
title: Add Server
layout: default
nav_order: 4
parent: Getting Started
---

<head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="https://b3h1z.github.io/HidyBot-Docs/assets/css/style.css">
</head>
<div dir="rtl">

<head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="https://b3h1z.github.io/HidyBot-Docs/assets/css/style.css">
</head>
<div dir="rtl">
<h3>How to Add a Server</h3>
<br>
<b>Initial Setup:</b>
<p>After the initial setup of the bot, you need to add your server. To add a server, first go to the "Server Management" section in the bot management panel and click on the "Add Server" button.</p>
<img src="https://b3h1z.github.io/HidyBot-Docs/assets/images/add_server/add-server-1.png" class="centered">
<p>Now, select your panel version from the displayed list.</p>
<img src="https://b3h1z.github.io/HidyBot-Docs/assets/images/add_server/add-server-2.png" class="centered">
<br>
<b>Install Hiddify API Expanded Script:</b>
<p>Before adding the server, you need to install the Hiddify API Expanded script on your server. Note that server verification by the bot and operations depend on the installation of this script, so it is mandatory.</p>
<img src="https://b3h1z.github.io/HidyBot-Docs/assets/images/add_server/add-server-3.png" class="centered">
<p><b>Installation Command:</b></p>
<code>sudo bash -c "$(curl -Lfo- https://raw.githubusercontent.com/B3H1Z/Hiddify-API-Expanded/main/install.sh)"</code>
<br>
<p>After entering the command on the server panel, wait until you see a successful installation message.</p>
<img src="https://b3h1z.github.io/HidyBot-Docs/assets/images/add_server/add-server-7.png" class="centered">
<br>
<b>Entering Required Information:</b>
<p>The following details need to be entered to add the server:</p>
<ul>
    <li><strong>Server Title</strong></li>
    <li><strong>Panel Domain</strong></li>
    <li><strong>Admin Proxy Path</strong></li>
    <li><strong>Admin UUID</strong></li>
    <li><strong>User Proxy Path</strong></li>
    <li><strong>Server Capacity</strong></li>
</ul>
<p>To obtain the domain, Admin Proxy Path, and Admin UUID, you need to log in to your server and select the "admin" option from the Hiddify menu. After entering the admin menu, your panel address will be visible.</p>
<img src="https://b3h1z.github.io/HidyBot-Docs/assets/images/add_server/add-server-5.png" class="centered">
<p>Your panel address consists of three parts separated by slashes, as marked in the image above, indicating which value to enter for the bot’s required information.</p>
<img src="https://b3h1z.github.io/HidyBot-Docs/assets/images/add_server/add-server-6.png" class="centered">
<ul>
    <li><strong>Server Domain</strong></li>
    <li><strong>Admin Proxy Path</strong></li>
    <li><strong>Admin UUID</strong></li>
</ul>
<p>Next, the bot will ask for the User Proxy Path. To obtain this value, go to the personal page of one of the created subscriptions in your panel, and then enter the specified section in the image for User Proxy Path in the bot.</p>
<img src="https://b3h1z.github.io/HidyBot-Docs/assets/images/add_server/add-server-8.png" class="centered">
<p>Finally, the bot will request a value to set a limit on the number of server users. This value is used so that the bot automatically prevents the purchase of new subscriptions once the number of users on your panel reaches this number.</p>
<img src="https://b3h1z.github.io/HidyBot-Docs/assets/images/add_server/add-server-9.png" class="centered">
<br>
<b>Important Notes:</b>
<ul>
    <li><strong>The Admin UUID must have Super Admin access level.</strong></li>
    <li><strong>The entered domain address must be direct; do not enter a CDN domain.</strong></li>
</ul>
<br>
<b>Completing the Process:</b>
<p>Once you see the successful addition message, you can view the added server by clicking on the "Manage Server" button with the title you assigned.</p>
</div>