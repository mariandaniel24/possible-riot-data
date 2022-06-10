# Riot API client - this data is available after a game is finished

### Match stats (this is pretty much what each player can see in post-game lobby, plus extra):
- Assists 		
- Baron kills 		
- Bounty level 		
- Champ experience 		
- Champ level 		
- Champion name 	
- Champion transform - 	This field is currently only utilized for Kayn's transformations
- Consumables purchased 		
- Damage dealt to buildings 		
- Damage dealt to objectives 		
- Damage dealt to turrets 		
- Damage self mitigated 		
- Deaths 		
- Detector wards placed 		
- Double kills 		
- Dragon kills 		
- First blood assist 	
- First blood kill 	
- First tower assist 	
- First tower kill 	
- Game ended in early surrender 	
- Game ended in surrender 	
- Gold earned 		
- Gold spent 		
- Individual position - The individualPosition is the best guess for which position the player actually played in isolation of anything else.
- Inhibitor kills 		
- Inhibitor takedowns 		
- Inhibitors lost 		
- Items		
- Items purchased 		
- Killing sprees 		
- Kills 		
- Lane 	
- Largest critical strike 		
- Largest killing spree 		
- Largest multi kill 		
- Longest time spent living 		
- Magic damage dealt 		
- Magic damage dealt to champions 		
- Magic damage taken 		
- Neutral minions killed 		
- Nexus takedowns 			
- Objectives stolen 		
- Objectives stolen assists 		
- Participant id 		
- Penta kills 		
- Perks
- Physical damage dealt 		
- Physical damage dealt to champions 		
- Physical damage taken 		
- Profile icon 		
- Quadra kills 		
- Role 	
- Spell1 casts 		
- Spell2 casts 		
- Spell3 casts 		
- Spell4 casts 		
- Summoner level 		
- Summoner name 	
- Team early surrendered? 		
- Team position  - The teamPosition is the best guess for which position the player actually played if we add the constrathat each team must have one top player,one jungle, one middle, etc.
- Time cc-ing others 		
- Time played 		
- Total damage dealt 		
- Total damage dealt to champions 		
- Total damage shielded on teammates 		
- Total damage taken 		
- Total heal 		
- Total heals on teammates 		
- Total minions killed 		
- Total time cc dealt 		
- Total time spent dead 		
- Total units healed 		
- Triple kills 		
- True damage dealt 		
- True damage dealt to champions 		
- True damage taken 		
- Turret kills 		
- Turret takedowns 		
- Turrets lost 		
- Unreal kills 		
- Vision score 		
- Vision wards bought in game 		
- Wards killed 		
- Wards placed 

### Champion select:
- Champion bans



### Match events (timeline):
Note: all of these events include a timestamp:

- kills on epic monsters
    - killer
- placed wards
    - who placed
    - type of ward
- items purchased/sold
- every player's lvl ups
- turret platings (which tower, killer)
- tower kills
    - killer
    - which tower
- kill events (think of death recap in game)
    - position (x/y coordinates)
    - who assisted
    - spells
    - amount of damage
    - auto attack damage
    - critical auto attack damage
    - how much damage each enemy dealt
    - minion damage

### Overview data - aggregated every minute
- for every player:
    - champion stats (armor, mr, attack damage, etc)
    - gold
    - gold per second 
    - current level and xp amount
    - minions
    - position (x/y coordinates)
    - k/d/a



# Live game client API - note that this requires the player to install a software on their computer:
Note: this data can be queried in real time:

- for any champion in the game:
    - current items
    - champion stats
    - respawn timer
    - creep score
    - k/d/a
    - ward score
- for the current player:
    - champion stats (armor/mr, crit chance, etc)
    - current position (middle/top/bot)
    - gold
    - level / xp amount
    - runes and current values (taste of blood - x amount healed, etc)
    - current spell levels (3 points Q, 1 point W, etc)
- events (we get them as soon as they happen in game)
    - champion kills
    - epic monster kills
    - tower and inhibitor kills
    - inhibitor/tower kills
    - multikills

