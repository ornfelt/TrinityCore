# ![logo](https://community.trinitycore.org/public/style_images/1_trinitycore.png) TrinityCore (3.3.5)

--------------


* [Build Status](#build-status)
* [Introduction](#introduction)
* [Requirements](#requirements)
* [Install](#install)
* [Reporting issues](#reporting-issues)
* [Submitting fixes](#submitting-fixes)
* [Copyright](#copyright)
* [Authors &amp; Contributors](#authors--contributors)
* [Links](#links)


## My custom changes

My custom changes include:
* Arena skirmish with npcbots. Currently, I've only added Nagrand Arena. You can queue 2v2, 3v3 and 5v5 and the npcbots will automatically join the queue just like in BGs. You need [this](https://github.com/ornfelt/TrinityCore/commit/1b5e874d4b8fbea218a2fc7efec69d24b9afc416) commit and the Nagrand arena wander nodes (my sql can be found [here](https://github.com/ornfelt/TrinityCore/blob/3.3.5/sql/Bots/updates/world/2023_06_09_00_creature_template_npcbot_wander_nodes.sql)) to add arena, and ideally [this](https://github.com/ornfelt/TrinityCore/commit/da88e361ae611a9a8d4e75b1fcaf4f76d7e425a5) one as well.

* Compatability with https://github.com/ornfelt/wander_nodes_util. See [this](https://github.com/ornfelt/TrinityCore/commit/1565a9b2c8222518505997d56af05a962fd6596b#diff-821d8443e5562c441172343cb58672bed4f1275e800e3ea08e9436c5eb2f4e7a) commit for required changes (look for DB execution in bot_ai.cpp and botdatamgr.cpp).

## Build Status

[![Fetch status](https://github.com/trickerer/NPCBots-cron/actions/workflows/automerge.yml/badge.svg)](https://github.com/trickerer/NPCBots-cron/actions/workflows/automerge.yml)

3.3.5
:------------:
[![GCC](https://github.com/trickerer/TrinityCore-3.3.5-with-NPCBots/actions/workflows/gcc-build.yml/badge.svg)](https://github.com/trickerer/TrinityCore-3.3.5-with-NPCBots/actions/workflows/gcc-build.yml)
[![Build status](https://ci.appveyor.com/api/projects/status/jck8c86eiti50v26/branch/npcbots_3.3.5?svg=true)](https://ci.appveyor.com/project/trickerer/trinitycore-3-3-5-with-npcbots/branch/npcbots_3.3.5)

## Introduction

TrinityCore is a *MMORPG* Framework based mostly in C++.

It is derived from *MaNGOS*, the *Massive Network Game Object Server*, and is
based on the code of that project with extensive changes over time to optimize,
improve and cleanup the codebase at the same time as improving the in-game
mechanics and functionality.

[NPCBots](https://github.com/trickerer/Trinity-Bots) is TrinityCore mod.

It is completely open source; community involvement is highly encouraged.

## Requirements


Software requirements are available in the [wiki](https://trinitycore.info/en/install/requirements) for
Windows, Linux and macOS.


## Install

Detailed TrinityCore installation guides are available in the [wiki](https://trinitycore.info/en/home) for
Windows, Linux and macOS.
NPCBots installation guide is available in the [NPCBots Readme](https://github.com/trickerer/Trinity-Bots#npcbot-mod-installation).


## Reporting issues

NPCBots issues can be reported via the [Github issue tracker](https://github.com/trickerer/Trinity-Bots/issues/).

Please take the time to review existing issues before submitting your own to
prevent duplicates.


## Submitting fixes

C++ fixes are submitted as [pull requests](https://github.com/trickerer/TrinityCore-3.3.5-with-NPCBots/pulls).


## Copyright

License: GPL 2.0

Read file [COPYING](COPYING).


## Authors &amp; Contributors

Read file [AUTHORS](AUTHORS).


## Links

* [NPCBots Readme](https://github.com/trickerer/Trinity-Bots/)
* [TrinityCore Website](https://www.trinitycore.org)
* [TrinityCore Wiki](https://www.trinitycore.info)
* [TrinityCore Forums](https://talk.trinitycore.org/)
* [TrinityCore Discord](https://discord.trinitycore.org/)
