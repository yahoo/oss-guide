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

Most open source licenses require that you give credit by reprinting the license and copyright text in any software you _distribute_ to others. Some products are _distributed_ to users (e.g. an app download) whereas others are _made available_ to users (software as a service). To our users, this difference is subtle. But this is relevant to open source license compliance. We consider binary or code to be _distributed_ if the CPU that interprets the binary (bytecode, script, etc.) is not owned or controlled by us. For example: Mobile apps run on a user's phone; they are distributed. JavaScript runs on a user's browser; it is _distributed script_. Desktop apps, browser extensions, and embedded software in physical hardware are distributed. When we distribute code containing open source to our users, we are obligated to comply with the license terms of the license and provide attribution.

## JavaScript

JavaScript is a web technology but it is distributed to the browser client. Node.JS is JavaScript based technology that runs on servers, except in cases like the Electron framework where it also runs on the client. Nearly all the JavaScript code we encounter is licensed under MIT or BSD terms. These are permissive and only require keeping the attribution that's already in the script code. Contact the OSPO if you wish to use JavaScript that is published under any non-permissive license. 

License compliance is easy with JavaScript since users can see and modify the script in their browser cache. We are required to retain license and copyright information in code we distribute. As long as you don't remove the text, you meet this obligation. Technical note: Minification of JavaScript code will often remove the license header text. Technically speaking, we should not remove the license header when minifying the rest of the JavaScript. That said, we are unaware of any JavaScript publisher complaining their license header was minified, so a mistake here will likely go unnoticed. We ask that you preserve license text in headers of JavaScript files that you minify.

## Desktop Apps

While publishing desktop apps is less common these days, if we publish them, we are required to provide open source credits in the app UI. 

 - **Browser app**. Browser extensions (such as Chrome, Firefox, and others) are distributed apps that run on the client's CPU. Include credits for any open source code you use via the user controls that the extension provides.
 - **Native desktop app**. Native desktop apps, include a credits UI that users can access via the Settings menu. Include credits for any open source code you use via the user controls that the app provides.
 - **Electron app**. Apps that use the open source Electron framework, run Node.JS on the desktop. When code distributes Electron along with an app, the publisher should provide credit for the open source code, the open source Electron framework, and for all the open source that Electron includes in their framework.

## Server-installed or Embedded Apps

Complying with installed open source distributions gets complicated. Many devices do not provide a UI to include a human-readable NOTICES file. We can comply with notices obligations by distributing a hard copy or by publishing a file on our open source website associated with the product. Also many embedded apps include open source licenses that contain clauses requiring some software to be made available to the end user. If you are working on a project that embeds code onto a hardware device, contact the OSPO on slack at #opensource or email ospo@ so that we can work with you on the compliance processes you'll need to have in place before product launch is approved.
