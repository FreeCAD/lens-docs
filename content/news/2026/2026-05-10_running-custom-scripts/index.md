---
title: "Running Python scripts on your models in the web UI"
date: 2026-05-10
slug: running-custom-scripts
authors:
  - name: Aleksandr Prokudin
    link: https://github.com/prokoudine
    image: https://avatars.githubusercontent.com/u/57467?v=4
tags:
  - Analytics
type: blog
---

Running custom Python scripts on your models in the web interface for Ondsel Lens was originally planned as an Enterprise-tier feature. A few years later, it's finally implemented and available to everybody.

<!--more-->

Here is what the UI looks like:

![Running a custom Python script](running-custom-script.webp)

You can all store all code snippets on your account for later use. They are available on the newly added Macros page:

![Running a custom Python script](macros-collection.png)

From the technical (and security) standpoint, this new feature is about executing Python scripts in FC-Worker inside a restricted bubblewrap sandbox. Implementing it involved patching both the backend, the frontend, and FC-Worker.

All work was done by Amritpal Singh thanks to the Ondsel Onward fund donated anonymously and managed by the FreeCAD Project Association.