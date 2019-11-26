---
layout: default
title: Publishing Binaries
nav_order: 1
parent: Launching Mobile Apps
---

# Publishing Binaries 

The Verizon Media Open Source Program Office (OSPO) provides services to help engineers at Verizon Media succeed with open source. If you are interested to learn more about open source, we are here to help. To get an overview of our program, vist the [OSPO Welcome Page](http://yo/ospo) intranet page, chat with us on our internal Slack channel (#opensource), or send an email to ospo@.

This page highlights issues engineering teams need to know about open source code in their binary apps. 

### Step Zero: Planning for Success

Most open source licenses require that you give credit by reprinting the license and copyright text in any software you _distribute_ to others. Some products are distributed to users (e.g. an app download) whereas others are made available to users (software as a service). To our users, this difference is suble. But this is relevant to open source license complaince. We consider a binary to be distributed if the CPU that interprets the binary (bytecode, script, etc.) is not owned or controled by us. For example: Mobile apps run on a user's phone. They are distributed. JavaScript runs on a user's browser. It is distributed script. Desktop apps, browser extentions, and embedded software in TV sets and routers are distributed. When we distribute code containing open source to our users, we are obligated to comply with the license terms of the license and provide attribution.

## JavaScript

JavaScript is a web technology but it is distributed to the browser client. Node.JS is JavaScript based technology that runs on servers, except in cases like the Electron framework where it also runs on the client.  Most JavaScript code is licensed under MIT or BSD terms. These are permissive and only require attribution. Avoid using JavaScript under a GPL license (only), as it slows down our launch process. It's overly complicated and best to avoid GPL in JavaScript. Users can see and modify the script in their browser cache. We are required to retain license and copyright information in code we distribute. As as long as you don't remove the text, you meet this obligation. Note: Minification of JavaScript code will often remove the license header text. We are unaware of any JavaScript publisher complaining their license header was minified. However it is a technical foul which feeds the troll. We recommend preserving license text in headers of JavaScript files that you minify.

## Desktop Apps

While publishing desktop apps is less common, if we publish them, we are required to provide open source credits in the app UI. 

 - **Browser app**. Browser extensions (such as Chrome, Firefox, and others) are distributed apps that run on the client's CPU. Include credits for any open source code you use via the user controls that the extension provides.
 - **Native desktop app**. Native desktop apps, include a credits UI that users can access via the Settings menu. Include credits for any open source code you use via the user controls that the app provides.
 - **Electron app**. Apps that use the open source Electron framework, run Node.JS on the desktop. When code distributes Electron along with an app, the publisher should provide credit for the open source code, the open source Electron framework, and for all the open source that Electron includes in their framework.

## Embedded Apps

Complying with embedded open source distributions can get complicated. Many devices do not provide a UI to include a human-readable NOTICES file. We can comply with notices obligations by distributing a hard copy or by publishing a file on our open source websie associated with the product. Also many embedded apps include open source licenses that contain clauses requiring some software to be made available to the end user. If you are working on a project that embeds code onto a hardware device, contact the OSPO on slack at #opensource or email ospo@ so that we can work with you on the compliance processes you'll need to have in place before product launch is approved.
