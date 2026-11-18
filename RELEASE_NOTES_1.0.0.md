**1.0.0 - Columns**

A supply column on the Eastern Road, gaps kept, escort in front. You placed it ten minutes ago. Now go and ambush it.

![A truck column with a BMP escort on a road](docs/images/convoy.gif)

First public release. Testers had 0.1.x builds since the start of November. This is everything since 0.1.6.

## New

* **Convoys.** Groups on Follow roads drive like a real column: on the road through every bend, gaps kept, the lead waiting for the tail. Works on roads you drew too.
* **Convoy drill.** A column that spots you: the ones in the kill zone drive through, the rest pull off both sides, guns out, riders out. Trucks can drive on while the escort fights.
* **Zeus.** Press \ over a running battle: give orders, spawn units, drop HE, smoke, mines or an IED, pause, jump into any tank. Save the battle as a new mission.

  ![Zeus over a running battle](docs/images/zeus.gif)

* **Edit mission** in a test run. The editor's panels over the fight. Change a group or a trigger, it's saved and happens right away.
* **Edit a route after you drew it.** Drag waypoints, add one in the middle, delete one.
* **Campaigns.** Missions in a row with branches for won and lost. Losses that stick, crews with names and skill, or a whole company to keep alive.
* **Infantry your way.** Squad presets or your own kit per man. Riders who get out when hit.
* **When they see you:** carry on, stop and fight, go for them, take cover, convoy drill. And what they do after the fight.
* **Minefields** you draw, with signs. Trenches and fire positions. Roads, bridges, forests and clearings.

  ![A drawn minefield, a trench line and a road with a bridge](docs/images/map_objects.png)

* **Action report** after a mission: everyone's tracks, a cross where each one fell, who got whom.

  ![The action report](docs/images/action_report.png)

* **Fire a shot.** A real round at the exact part of a tank you pick. Plus camera shots and slow motion as trigger actions.
* **The Inspector, tidied.** Sections that fold and remember it, a summary line on each, a "?" that opens the right handbook page.
* **Triggers read as sentences**, and the action list is grouped instead of 44 rows in one column.
* **Guides.** A look round, Your first mission, A bigger mission, and short ones for each part of the editor.
* **Handbook** on F1, now also in Russian and Chinese.
* **The Outliner.** Folders, tags, find, hide, lock.
* Undo with a history, copy and paste between missions, templates.
* Move and turn handles, box select, measure, line of sight, weapon and sight rings.
* Map marks and NATO symbols on the player's map.
* Keys shown as key caps. Every editor key can be rebound.
* Russian and German join English, Polish and Chinese.
* With Task Force: play your missions in co-op. The host's mission is sent to everyone.

## Bugfixes

* A save that was interrupted could make the mission vanish from the list.
* A failed save followed by a test or a switch lost your edits.
* All missions autosaved over the same file.
* Fog from a Phase Line mission stayed on in the game's own missions.
* Fire support was gone after Play again or Next mission.
* Play again started the mission as the last run left it, not as you made it.
* Back to the mission list could leave you in a frozen mission.
* Invisible bridge walls stayed on the map and blocked you.
* Trench holes stayed in the map after you left.
* Selecting a group could delete its riders.
* The Teleport action moved only the model.
* Trigger actions due at the same moment ran in reverse order.
* The Hold objective's clock ran fast under fire.
* Opening Zeus during a film gave a black screen.
* Save as a mission lost the pictures and sounds.
* The import window showed only 16 packs.
* A lot less work per frame in the editor: the Outliner, the mission list and the Browser no longer hitch on big missions.

## Coming up

* **Seasons.** Autumn, winter, snow you fight in. Coming soon.
* Real places as maps, and motorways.

**Install:** MelonLoader 0.7.x, `PhaseLine.dll` into `Bin\Mods`. Works alone, or with Combat Overhaul 2.0 and Task Force 1.0.

**From a tester build:** put the new DLL over the old one. Your missions stay.

Bugs: open an issue with `Bin\MelonLoader\Latest.log`, and the mission folder zipped if it's about a mission.
