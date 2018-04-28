# AutoQuest

###### Scary warning: Most of these addons were made long ago during Feenix days, then a lot was changed/added to prepare for Corecraft. Since it died, they still haven't been extensively tested on modern servers.

### [Downloads](https://github.com/Shanghi/AutoQuest/releases)

***

## Purpose:
* Can automatically take normal quests (off by default).
* Can automatically take daily quests (on by default).
* Can automatically take repeatable quests if you have the required items (on by default).
* Can automatically complete most quests - you still pick rewards (on by default).
* Can set specific quests to be automated or not, so if you never do a certain quest you can disable it so it won't be taken.

| Commands (/aq or /autoquest) | Description |
| --- | --- |
| /aq accept \<"on"\|"off">   | _auto-take every quest when talking to an NPC_ |
| /aq daily \<"on"\|"off">    | _auto-take daily quests_ |
| /aq repeat \<"on"\|"off">   | _auto-take repeatable quests if you have the required items_ |
| /aq complete \<"on"\|"off"> | _auto-complete quests when talking to an NPC_ |
| /aq toggle \<quest name>    | _toggle whether to automate a specific quest_ |

## Notes:
* Some specific quests have automation disabled by default (like turning in cloth). You can enable them, or disable ones you never want to do, using the toggle command like: **`/aq toggle additional runecloth`**

* Some quests (mostly ones like "go talk to that other quest giver") aren't fully automatically completed. This is because they aren't marked as complete in the quest log and I haven't found a safe way to check the status while talking to the NPC (you can't just look at the icon because private server bugs make that unreliable).
