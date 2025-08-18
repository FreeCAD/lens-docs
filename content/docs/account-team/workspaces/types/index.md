---
title: Types of workspaces
id: workspaces-types
description: What workspace types are available in Ondsel Lens
weight: 1
---

Workspaces are a collection of files organized in directories. These files can be accessed by one or more people depending on administrative settings.

Every workspace is owned by an organization, therefore, just like with organizations, there are three types of workspaces: personal, open, and private.

**Personal** workspace is the one created for every user by default. It cannot be marked as open, renamed, deleted, or provided access to for another user.

**Open** workspace is the one that is marked open in the visibility settings. It is visible to all users, including anonymous ones. Files in an open workspace are read-only and can be downloaded by everybody. Write access requires membership in the owning organization/workspace and write permission.

**Private** workspace is _not_ marked as open in visibility settings. It isn't visible to anybody except members of an organization that the workspace is owned by. Write access also requires membership in the owning organization/workspace and write permission.

| Type | Participation | Read access | Write access |
|------|---------------|-------------|--------------|
| Personal | Automatically created per user | Only available to the user it belongs to | Only available to the user it belongs to |
| Open     | Users can be invited | Available to all | Requires membership |
| Private  | Users must be invited | Requires membership | Requires membership |