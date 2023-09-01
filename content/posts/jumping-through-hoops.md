---
title: "Jumping through Hoops - Installing the Java SDK"
linktitle: "Jumping through Hoops - Installing the Java SDK"
draft: true
toc: false
type:
- post
- posts
images:
series:
- Rambling
categories:
- software engineering
tags:
- development
- tools
---

## Installing the Java SDK ... yet again ... for the eleventy billionth time

Always looking out for that quick and easy way to install the Java SDK. This time, I'm going to try [sdkman](https://sdkman.io/) which is a 
tool for managing multiple versions of the Java SDK. It's a little more than that, but that's what I'm going to use it for.

I'm using Debian 10, so I'll follow the instructions for [Linux](https://sdkman.io/install).

```bash
$ curl -s "https://get.sdkman.io" | bash
```

I still had to open <https://jdk.java.net/20/> to find the latest version number. I'm sure there's a way to do that programmatically.

Then, open a new terminal window and run the following:

```bash
$ sdk install java 20.0.2-open
...
Setting java 20.0.2-open as default.
```

One thing it did do was set the package to be the default... without asking... Anyway, turns out `sdk default java 20.0.2-open` will set it to the stated version.
