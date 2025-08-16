---
title: Files vs models
description: Learn what distinguishes models from files on Lens
weight: 1
---

Lens makes a distinction between files and models.

A **file** is an object that represents any file stored in the Lens system. It can be any type of file, such as `.txt`, `.step`, `.md`, `.pdf`, or `.fcstd`. You can upload files with any extension to Lens, but Lens can visualize only  certain types of files.

A **model** is an object that facilitates rendering a 3D file in the browser using Three.js (in a 3D scene). So, a file object that contains a model object (via the `file.modelId` property) can be viewed in a 3D scene.

Thus, when we discuss uploading, downloading or versioning, we use the word “file”. But when we discuss something you can render with Lens, we use the word “model”.

Models have unique URLs, such as https://lens.ondsel.com/model/672a0f9be0f5e61b6639591a. Only members of the respective organization can use such a URL to open the model’s page.
