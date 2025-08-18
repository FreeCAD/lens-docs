---
id: versioning
title: Version control
description: How to create and track revisions of your 3D CAD designs
weight: 5
---

Ondsel Lens supports creating and managing versions of `.FCStd` files uploaded to workspaces. This applies to all tiers, free and paid.

## How versions are stored

Lens uses a simple linear history of revisions. Versions of files are stored as new files and are referenced in the database using hashes.

## Create a new version

You can upload a new version of a file. To do that:

1. Open a file in a workspace.
2. Click on the **Upload New Version** button in the top toolbar.
3. Select the FCStd file of the new version.
4. Click on the **Finish Upload** button.

## Set an active version

Lens has a concept of an active version. This is the version that is displayed in the online viewer when you open the model. By default, it's the latest revision of the file. However, any revision can be assigned the role of the active one. To do that:

1. Open a file in a workspace.
2. Scroll down to the _Versions_ section.
3. Click on the revision comment.
4. In the newly opened dialog, click on the **Set As Active** button.

## Download a copy of a version

You can download any revision of a file that you have full access to:

1. Open a file in a workspace.
2. Scroll down to the _Versions_ section.
3. Click on the revision comment.
4. In the newly opened dialog, click on the **Download Copy** button.

To download the active version of the file, do the following:

1. Open a file in a workspace.
2. Click on the **Download Active** button in the top toolbar.

## Delete a version

Deleting versions has not been implemented yet.