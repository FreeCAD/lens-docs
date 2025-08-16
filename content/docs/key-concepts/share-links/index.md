---
id: share-links
title: Share links
description: Learn about share links and their settings
weight: 3
---

A share link is a way to make a model accessible to other users under certain conditions. You can create as many share links per model as you like. All share links have unique URLs, such as `https://lens.ondsel.com/share/672a106ce0f5e61b6639594f`.

## Toggling share links

You can toggle a share link to disable it without actually destroying it. The switch is at the top of the sahre link settings dialog.

## Mandatory fields

When you create a new share link, Lens requires you to fill in two fields:

- **Title**. This is the publicly visible title of the share link. It can be the name of the part, the part number, the revision number, or a combination of any of those three.
- **Private note**. This describes the share link that only you and other people in your organization can see. Private notes help keep track of the share link's purpose long after the person who created is gone.

## Permissions

Every share link can have a unique set of permissions that dictate who can open the share link and what they can do with the model. Once a share link is created, you can reopen the share link settings dialog and change permissions. There are three sets of permissions settings.

### Protection

You can make share links publicly visible or visible only under certain circumstances. To do so, use the **Protection** drop-down list to select the option that suits your needs best:

- **Listed**: the share link will be visible to everyone in the Public Share Links section; it will also be searchable.
- **Unlisted**: the share link will be visible to everyone, but it will not be listed in the Public Share Links section, it won't be searchable, and you can only find it if you know the exact URL.
- **PIN**: the share link will not be publicly listed, it will not be searchable, and you need to know the exact 6-digit PIN to access it.
- **Direct**: only existing Lens users you specified can access the share link if they know the exact URL; nobody else can see the share link or search for it.

### General permissions

The **General Permissions** section helps control basic :

- **Can view model**: this setting is always on by default, you cannot disable it.
- **Can view attributes**: if the model has parametric properties created with VarSets, this controls the visibility of those parametric properties.
- **Can update attributes**: if the model has parametric properties created with VarSets, this controls whether users with access to the share link can update these properties live on Lens.

For more information about attributes, please see the **Model Customization** section.

### Export/download permissions

Lens provides control over the downloading of the original file for users who have access to the model via the share link.

By default, users who accessed the model using a share link can only explore the model; downloading is not possible. You can make the downloading possible by enabling any combination of supported file formats: FCSTd, STEP, STL, OBJ.

The “original file” option helps download the model in its original file format, whatever format that is.

## Version change handling

Share links can be associated with either a particular revision of a model or with the latest active revision, for more information, please see the **Versioning** section.
