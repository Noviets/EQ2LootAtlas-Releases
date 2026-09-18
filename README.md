# EQ2 Loot Atlas - downloads

The ACT plugin for [EQ2 Loot Atlas](https://lootatlas.noviets.com), an item-source database for the
EverQuest II **Anashti Sul (Origins)** server. It reads your combat log and records where items come
from - what dropped them, which quest rewarded them, which merchant sold them - so the atlas can
answer "where do I get this?" for everybody.

## Download

Take the `EQ2LootAtlas.dll` attached to the [latest release](../../releases/latest) and drop it in
ACT's plugin folder. Setup instructions, including how to get an API key, are on the
[setup page](https://lootatlas.noviets.com/setup).

Once the plugin is listed in ACT, updates arrive through ACT's own plugin tab and none of this is
necessary.

## What is in this repository

Releases, and nothing else. Each one carries the compiled plugin and the list of changes since the
previous release. The source lives in a private repository; the plugin talks to a server whose admin
and ingest surface is not something to publish.

## Reporting a problem

Open an [issue](../../issues). Useful things to include: the plugin version from ACT's plugin tab,
what you expected, and the log line involved if it is a parsing problem. The line as it appears in
the log file matters more than a description of it - EQ2's phrasing is the whole difficulty.
