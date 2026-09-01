---
title: "Matomo image restored"
date: 2026-04-26
slug: matomo-image-restored
authors:
  - name: Aleksandr Prokudin
    link: https://github.com/prokoudine
    image: https://avatars.githubusercontent.com/u/57467?v=4
tags:
  - Analytics
type: blog
---

A while ago, the Bitnami Matomo Docker image (docker.io/bitnami/matomo:5) became unavailable which broke analytics for deployments that were using the matomo-enabled profile. The issue is now fixed.

<!--more-->

As part of work on another privately-sponsored grant managed by the FPA, Amritpal Singh replaced docker.io/bitnami/matomo:5 with the official matomo image from Docker Hub (matomo:5.8.0-apache or matomo:latest).

He also updated environment variables and volume mappings to match official image schema and ensured compatibility with existing Matomo database schema and matomo-db (MariaDB).