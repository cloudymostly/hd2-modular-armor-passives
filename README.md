# hd2-modular-armor-passives
Requires Bingus Shared Loader. A 99% vibe coded mod that enables (up to) ALL 31 armor passives on any armor with the user-selected base passive (default Med-Kit). Works with Armor Transmog to allow any set to benefit, just choose the Med-Kit passive!

The mod is intended to be configurable for (de)selecting a list of passives but it's still buggy, feel free to mess with the files yourself and maybe you can make a better version.




Tutorial .txt is included in the .zip, follow the attached screenshots for a visual guide on how to rebuild the mod using your custom passive list. Requires Python 3.10+
1. Create new folder and add the downloaded .zip there. *ALSO* extract the contents to the same folder, see photo. Open and read HOW-TO-EDIT.txt
2. Following the .txt instructions, open a terminal and direct it to this subfolder (I used git bash, required adding another \ to listed command filepaths). Run
   
python tools\passive_picker.py extract "Passive Picker v3.0.zip"

3. Edit the created passive_picker_config.lua to your liking. The trigger_perk = 7 at line 90 can be edited to another perk using the table above. Below in the rows and stat_rows, comment-out or delete unwanted passives. SAVE FILE when done.
4. Refer back to your terminal and run

python tools\passive_picker.py build passive_picker_config.lua --zip "My Picker.zip"

(or with your preferred file name). Install the newly created .zip with your mod manager.




List of Passives/Perks (duplicates are included in the code but may not apply due to how I was designing it. some perks don't seem to apply properly in my limited testing)

-Extra Padding (+50 armor rating)

-Scout (-30% detection radius, ping radar scans every 2sec)

-Fortified (-30% recoil when crouched/prone, 50% explosive resist)

-Electrical Conduit (+95% arc resist)

-Engineering Kit (-30% recoil when crouched/prone, +2 throwables)

-Med-Kit (base perk, +2 stims, +2.0 second stim duration)

-Servo-Assisted (+50% limb health, +30% throw range)

-Democracy Protects (50% chance to not die, prevents chest bleeding)

-Reinforced Epaulettes (+30% primary reload speed, 50% chance to avoid limb injury, +20% melee damage)

-Inflammable (+75% fire resist)

-Peak Physique (+40% melee damage, +30 ergo)

-Advanced Filtration (+75% gas resist)

-Unflinching (-95% flinch, +25 armor rating, ping radar scans every 2sec)

-Acclimated (+50% fire/gas/acid/arc resist)

-Siege-Ready (+30% primary reload speed, 20% ammo capacity)

-Integrated Explosives (explode 1.5s after death, +2 throwables)

-Gunslinger (+40% sidearm reload speed, +50% sidearm draw speed, -70% sidearm recoil)

-Adreno-Defibrillator (+50% arc resist, one-time revive on death, +2.0 second stim duration)

-Ballistic Padding (+25% chest damage resist, +25% explosive resist, prevents chest bleeding)

-Desert Stormer (+40% fire/gas/acid/arc resist, +20% throw range)

-Feet First (-50% moving noise, +30% POI identification range, immunity to leg injury)

-Reduced Signature (-50% moving noise, -40% detection radius)

-Rock-Solid (+40% melee damage, -30% stagger/ragdoll)

-Supplemental Adrenaline (gain stamina when taking damage, +25 armor rating)

-Concussive Padding, Reinforced (+50% explosive resist, +30 armor rating)

-Concussive Padding, Grenadier (+50% explosive resist, +2 throwables,

-Concussive Padding, Hazmat (+50% explosive resist, +25% gas resist, -30% sidearm recoil)

-Kinetic Displacement Mitigation (+50% fire resist, 50% chance to avoid limb injury, -30% impact damage)

-Oxygenator (+10% walk/run speed, +50% slide distance)

-Blunt-Force Mitigation (-30% stagger/ragdoll, -30% impact damage, +25 armor rating)

-True Grit (+30% support reload speed, +20 ergo)




I'm dumb, unemployed, fat, ugly and already ran through my 10 google accounts' free limits for vibe coding so if you'd like to support me all proceeds will go toward DeepSeek v4.1 Flash tokens to "create" more mods with my darling ai agent. support me on [ko-fi](https://ko-fi.com/cloudymostly)
