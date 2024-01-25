---
title: Elf Hosted Iceberg 🧝 from $0.05/day
slug: Iceberg
description: Iceberg is a WIP rewrite of plex_debrid, supporting Plex torrent streaming through Real Debrid and 3rd party services like Overseerr, Mdblist, etc.
upstream: https://github.com/dreulavelle/iceberg
links:
- name: Discord
  uri: https://discord.gg/wDgVdH8vNM
- name: project board
  uri: https://github.com/users/dreulavelle/projects/2
---

# {{ page.meta.slug }}

Iceberg is a rewrite of [plex-debrid][plex-debrid], enabling Plex torrent streaming through Real Debrid and 3rd party services like Overseerr, Mdblist, etc.

!!! warning "Under active development"
    Iceberg is under active development, and may break at any time. Users are welcome to try it out (*it's $0 in the store provided you already have [Zurg][zurg]*), but should have realistic expectations of support and reliability!

{% include 'app.md' %}
{% include 'app_access.md' %}

## How to use it

### Onboarding

#### Step 1 / 4 

When prompted, set **Host Path** and **Container Path** to `/storage/realdebrid-zurg`, and paste in your RD API key.

#### Step 2 / 4

Set your Plex URL to `http://plex:32400`, and authenticate

#### Step 3 / 4

When prompted for content services, use either `http://jellyseerr:5055` or `http://overseerr:5055`, depending which app you use.

#### Step 4 / 4

Set your indexers (*I've not really tested this part yet*)

### Manual config

Onboarding is a new feature, and may be buggy. You can also edit your settings manually, using [FileBrowser][filebrowser], and then restarting Iceberg using [ElfBot][elfbot].

{% include 'app_footer.md' %}