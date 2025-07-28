---
map_height_y: 120
map_width_x: 2048
scale_pixels: 268
scale_pixels_range: 25
mapCalc1: 0.09328358208955223
---




> [!NOTE]- Quick Calculator  
> Map Height in Pixels: `INPUT[number:map_height_y]`  
> Map Width in Pixels: `INPUT[number:map_width_x]`  
> lat: `VIEW[{map_height_y} / 2][math]`  
> long: `VIEW[{map_width_x} / 2][math]`  
> How Many Pixels In Scale: `INPUT[number:scale_pixels]`  
> How Many Units in Scale: `INPUT[number:scale_pixels_range]`  
> Scale: `VIEW[1/({scale_pixels}/{scale_pixels_range})][math:mapCalc1]`



```leaflet  
id: MapCalcExample ### Must be unique with no spaces  
image: [[Spike.jpg]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [2048, 1642]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 500px ### Size of the leaflet embed in px on your screen  
width: 120% ### Size of the leaflet embed in your note  
lat: 1024 ### To center the map, make this half of the map height.  
long: 821 ### To center the map, make this half of the map width.  
minZoom: -1.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.09328358208955223 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```




# The World & Continent

The year is 44 of the Second Great Age, the continent of Pyke is experiencing a rare but welcome era of prosperity. The land has been riddled with conflict the entire first great age, and only continued for the first 808 years of the Second Age. The lands, diverse and tumultuous as they are, for the time being, remained rather peaceful, and has done so for quite some time. Still licking their wounds after suffering the Long Night, the major Kingdoms have all refrained from warring and bringing Chaos to the land, and instead have focused on growth and expansion. That said, there is still plenty of adventure to be had.

Travelling is manageable on Pyke there are various teleport stones, called Waynodes. Though common Waynodes are only permitted to go to certain places and only places the user has visited before.
# Pyke & Her Provinces

Pyke has 6 major provinces with their own unique features and areas. There are a plethora of encampments for Mortals all over the landmass, from settlements, villages, towns, and bustling Cities. 

- [[The Western Woods]]
- [[Territories of Eternal Snow]]
- [[The Jewel Desert]]
- [[Kormandir's Plains]]
- [[Badland Provinces]]
- [[Bruitalis]]

#  The Adventurers Guild

The **Adventurers Guild** stands as a vital institution for the brave, the bold, and the foolhardy. Whether you're a noble-born Lord or a humble farmer, there’s always work that needs doing… in exchange for coin, of course. Adventurers take on jobs big and small, risking life and limb for glory, trinkets, and—let’s be honest—mostly for the gold.

Originally founded to promote community aid, the Guild became even more critical in the aftermath of the **Long Night**, when the world was left scarred and scattered. Governments were overwhelmed, and rebuilding required more hands than they could muster. Enter the Guild—serving as the middleman between those in need and those crazy enough to answer the call.

Prosperity doesn't mean peace. Bandits still roam the roads, trolls still steal away Lordlings, and some problems need more than a farmer with a pitchfork. That’s where the Guild thrives. Jobs are ranked by **tiers**, categorizing danger and reward.

---

## Adventurer Tier Rankings

| **Tier**    | **Description**                                                                                               | **Example Quests**                                                     |
| ----------- | ------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| **Legends** | _Must be nominated and pass the Guild’s Grand Examination._ Reserved for the best of the best.                | ???                                                                    |
| **S**       | _Must have completed at least 20 A-tier quests with excellence._ The Brave. The Bold. The Few.                | Slaying a Fire Giant, Eliminating a cult deep underground.             |
| **A**       | High-level combat training or masterful skill strongly recommended.                                           | Battling a troll pack, Rescuing hostages from a pirate armada.         |
| **B**       | Expect combat and significant danger. Even veterans should tread carefully. **Death waivers must be signed.** | Clearing a den of bandits, Guarding a noble through treacherous lands. |
| **C**       | Mild risk. Low-level combat likely, but manageable by seasoned groups.                                        | Trapping a rare beast, Harvesting a poisonous bloom deep in the woods. |
| **D**       | Minor danger. Some physical effort or low-threat encounters possible.                                         | Standing night watch for coyotes, Logging in goblin-infested forests.  |
| **E**       | Nearly no danger. Basic labor or errands. A good start for greenhorns.                                        | Gardening for an elderly man, Finding a lost kitten in town.           |

---

The Guild acts not only as a quest board, but a lively social hub. Adventurers can meet, form parties, brag about their victories, and celebrate (or mourn) completed jobs. The Guild does, of course, take a small cut of all job payments—gotta keep the lights on.

This is where many begin their journey. Who knows? Maybe someday, they’ll call **you** a Legend.

# If a Book Tells you about Races it's science but when I do it, I'm racist

Mortal races are born for the most part in the same environment and areas.

[Races](https://www.dndbeyond.com/species?srsltid=AfmBOorYtYfH9UIes2rnMo8Ut_ReqNB1iFuDXmtF8a-WIdje8w91egI6) (try to stick to the PHB ones, but if any other ones interest you ask DM first.)

Mortal races are often classified into long life races and short ones. Each race has their own positive and negative stereotypes assigned to them, but ultimately for the most part, they live in harmony with one another. 

| Short Life <100 Yrs | Long Life >100Yrs      |
| ------------------- | ---------------------- |
| Human               | Elves/Half-elves(500s) |
| Dragonborn          | Dwarf (300s)           |
| Tiefling            | Halfling(200s)         |
| Half-orc/orcs       | Gnomes(500s)           |
## It's not easy being Green

^3f1b3d

In the F.G.A racism and discrimination against Giantfolk and Giant-related people were prevalent. Giants, Goliaths, Ogres, Trolls, Orcs, Hobs and Goblins were seen as lesser than and barbaric by the other races. All green skinned brutes as the mortals like to call them They seem to value strength overall more than any other trait. Now while other species, like Dragonborns value militaristic tactics overall, the Giantfolk were noticeably more savage.

Now this age you will see some orcs, half-orcs and goliaths being assimilated in common society, but the others are still shunned and reviled for the most part. Now this distinction is not without reason. For the most part orcs, goliaths, and half orcs have made effort through trading and honoring the common rules with the rest of Pyke's inhabitants. The others though still for the most part are violent towards mortals on sight. This was made prevalent with [[Commonly Known History#^82e493|The Long Night]]. The TLDR is vampires did not like the taste of some Giantfolk (and avoided conflict with Giants altogether) so they hired them as lackeys to be guards and hunt down the "cattle". Often beating down and torturing those under them the scars of the Long Night still echo to this day and mortals are not willing to relinquish the feud. No love is lost on either side. Also one more noticeable thing...

Giants actively hunt and eat all mortals. Before the Long Night, Giants had a point in time where they would eat mortals. Pick up their houses and shake them out of there, giants are not to be trifled with. Also, what separates them from other the other shunned Giantfolk is their intelligence. They have the potential and the social acumen to join society, they just choose not to and prefer to keep us mortals on their diet. Times have changed and mortal might has grown, to where most giants know not to frequent too close to mortal strongholds, and they typically frequent the [[Badland Provinces]], but it is not odd to hear the odd tale of farmers and their families disappearing while finding their stead ripped out from the ground.

# TLDR LORE (Everything Beyond this Page is Extra)
- Continent(Pyke) was at war with each other during the First Era. Constant bloodshed with each other.
- Then people from another continent attacked, forcing the Kingdoms to band together to fight off the invaders
- Eventually the invaders fell, peace amongst the kingdoms.
- Then something known as the [[Commonly Known History#^82e493|The Long Night]] happened and a vampiric plague fell onto the continent.
- No sun for 170+ years until the night ended and the sun rose again.
- Now is the Second Era, mostly peaceful, small skirmishes
- Adventurers guild made to help those in need
- Current year is 44th year of the Second Era or 2nd-E-44 is how it is written.
- The Campaign will be taking place at a small outpost called Genis. (Young and Flourishing, used to be a Vampire settlement but was reclaimed by us.)
- You will be recruits to the Adventurers guild.
- They will be starting at level 2.