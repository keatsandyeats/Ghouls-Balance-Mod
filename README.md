# Ghouls Balance Mod

**SteamWorks Mod ID**: *2dd47a50*

This mod contains various prototype balance changes based on various ideas of the NS2 balance team.

Current changes:

- Marines

    - Flamethrower
        - The flamethower now deals 100% (instead of 20%) more damage against structures (excluding the hive)
        - There is no more wind up time for dealing extra structural damage
        - The flamethrower now deals splash damage: 
            - That means any enemy inside a range of 2 of a hit target will be receive damage as well
            - Also a flame puddle is created below the hit target
        - Increased the burn damage targets take to 5 (from 2) but decreased the burning duration to 3.1 secs (from 6 secs)
        - Increased the damage flame puddles deal to 12 (from 8) but decreased their lifetime to 2.1 secs (from 5.6)
        - Increased the damage tick rate of flame puddles to 3 ticks per second (from 1.6) so fast aliens can't pass the flames without taking damage anymore.
        - Increased the cone width of the flamethrower to 0.3 (from 0.17)
        - Decreased the amount of energy the Flamthrower removes from a target to 1 (was 3)
        - The flamethrower no longer removes enzyme effects from it's targets.
        - Increased the cost of the flamethrower to 15 (was 12) pres.
        

- Aliens
    - Upgrades
        - Autoselect upgrades at spawn
            - At spawn previously selected upgrades will be reapplied if they are still available.
            - In case the player hasn't selected an upgrade for an available trait yet a random one will be applied at spawn. 
            
        - Silence
            - Removed Silence 
            
        - Phantom
            - Added the Phantom upgrade back to the game
            - Phantom cloaks you while moving slowly
            - Phantom let's you move and attack structures almost silently
            - Requieres a Shade Hive            
            
        - Vampirism
            - Requires now a Crag Hive (instead of a Shade Hive)
            - Doesn't cloak anymore
            - Rebalanced health gain values (for each shell):
                - Skulk: 5 (from 5)
                - Gorge: 6 (from 5)
                - Lerk (Bite): 5 (from 3)
                - Lerk (Spike): 2 (from 0.66)
                - Fade: 12 (from 6.66)
                - Onos: 20 (from  13.33)
            - If Focus is selected Vampirism will heal additional 33% to compensate for the longer attack cooldowns.
        
        - Alien Regeneration
            - Alien Regeneration (both the upgrade and the natural one) doesn't restore health if you have been hurt less than 3 seconds ago.
        
        - Regeneration 
            - Increased amount of hp regen restores every 2 secs to 4% (from 2%) of the base hp for each shell.
            
        - Crush
            - Requires now a Shift Hive (instead of a Crag Hive)
            
    - PvE
        - Hive
            - Each Hive can now gain up to 4 Biomass
                 - The 4th biomass costs 60 team ressources and takes 60 seconds to research.
        - Drifter 
            - Added passive abilities for each hive type:
                - Camouflage (Shade Hive): Drifters turn invisble when they idle.
                - Regeneration (Crag Hive): Drifters regenerate 3% of their hp every 2 secs while being hurt.
                - Celerity (Shift Hive): Drifters move 18% faster.
                          
        - Contamination
            - Contamination doesn't spew bile bombs after being set on fire.

Code @ Github: https://github.com/GhoulofGSG9/Ghouls-Balance-Mod

Feel free to leave feedback ;)
