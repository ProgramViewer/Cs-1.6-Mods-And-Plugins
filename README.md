# **Cs-1.6-Mods-And-Plugins**

This repository will host all the mods and plugins for Counter-Strike 1.6. It will include not only the plugins themselves but also **news and updates** regarding new mods, plugin changes, and additional features being added or adjusted. Stay tuned for the latest improvements and releases as they come!

---

Feel free to explore and contribute to the development!

-------------------------------------------------------------------------
### [First Update] - 11/02/2025 1:48 AM

We are thrilled to announce that the **Zombie Mod Infection Remake** is coming soon! This project is in the works, and we're actively polishing the code and adding exciting new features to bring the game back to life with a fresh, modern touch.

The **Zombie Mod Infection Remake** will capture the essence of the original mod, with improvements to gameplay, new mechanics, and a smoother, more dynamic experience. Fans of the original will find all the nostalgia they love, but with new surprises that will enhance the gameplay.

Stay tuned for more updates as the remake takes shape—it’s coming closer to being ready for release!
---
-------------------------------------------------------------------------
### [Sub Plugin Updates] - 11/02/2025 2:03 AM

In addition to the **Zombie Mod Infection Remake** announcement, we are also excited to share some updates on the **sub plugins** that have been tested and integrated into the mod during development. These plugins add exciting new features to enhance the overall gameplay experience.

### **1. Knockback by Cheap_Suit**
The **Knockback plugin** modifies the weapon knockback, making combat more dynamic and challenging. Players will feel the impact of their shots in a whole new way, adding more strategy to engagements.

### **2. Infect Effect by Dias**
The **Infect Effect plugin** creates a custom visual effect when players are infected, enhancing the immersion and creating a more intense atmosphere. This effect will add to the excitement of being infected, as players will visually experience the change.

### **3. Flare Nade by MeRcyLeZZ**
The **Flare Nade plugin** introduces flare grenades that illuminate the battlefield. Players can strategically use these flares for light or to signal teammates, adding an element of teamwork and tactics to the game.

**Credits:**  
- **Cheap_Suit** – Creator of the Knockback plugin  
- **Dias** – Creator of the Infect Effect plugin  
- **MeRcyLeZZ** – Creator of the Flare Nade plugin

These sub plugins have been thoroughly tested and refined for the **Zombie Mod Infection Remake** and will provide players with an enhanced experience once the mod is released.

Stay tuned for more updates as development continues!
---
-------------------------------------------------------------------------
---
### [Official Release] - 23/02/2025 6:08 PM

The wait is over! We are excited to officially announce the public release of Zombie Mod Infection! 🎉

After months of development, testing, and refining, the mod is now available for everyone. This remake stays true to the original Zombie Mod Infection, while introducing new mechanics, optimizations, and enhanced gameplay features to deliver a fresh experience for both veterans and newcomers.

Requirements
To run Zombie Mod Infection, you need:
✅ Counter-Strike 1.6 (Steam or non-Steam)
✅ AMX Mod X 1.8.3+ (or a newer version)

We Want Your Feedback!
We value your experience and want to hear from you! After diving into the Zombie Mod Infection, please share your thoughts, suggestions, and any issues you might encounter. Your feedback helps us improve the mod and make future updates even better.

---
-------------------------------------------------------------------------
---
### [New Plugin: Server Lore] - 06/05/2025 1:33 AM

Ever feel like your server has stories to tell?
Server Lore is a lightweight plugin that brings a bit of mystery, humor, or nostalgia to your rounds by displaying short HUD messages—mini tales that feel like memories from your server's past (real or imagined).

Each round, a new line of lore is shown, selected randomly from a list you can fully customize.
Think of it like your server whispering its own urban legends.

✅ Multilingual support
✅ Never repeats the same line twice in a row
✅ Fully customizable timing, message slots, and HUD settings
✅ Works with any mod

Create your own server mythology—one message at a time.

---
-------------------------------------------------------------------------
---
### [Zombie Mod Infection Fixing-Notice] - 30/05/2025 8:00 PM

Several bugs and design oversights were found in the latest version of the plugin. As a result, the .rar file has been temporarily removed to perform fixes, improvements, and model renaming.

🔍 Issues Identified:

Forced joinclass command loop:
In the clcmd_changeteam function, a line was found that forced the execution of the joinclass command. If triggered once, it would repeat indefinitely, leaving the player unable to operate the menu or interact normally — especially when no team could be selected, resulting in a frozen state.

Model naming conflict:
The zombie model names contained special characters such as "()", which led to errors in model transmission on the server. Model names are now being renamed to avoid these issues.

Incorrect help menu display:
Some entries in the help system were not being displayed completely or correctly.

Bot weapon assignment failure:
The restriction system was not correctly applied to bots due to an incorrectly implemented assign_weapon method.

A corrected version is being worked on and will be re-uploaded once all fixes are confirmed stable. Thanks for your patience and understanding.

---
-------------------------------------------------------------------------
---
### [Zombie Mod Annihilation Announce] - 30/05/2025 8:10 PM

We’re excited to officially introduce Zombie Mod Annihilation, a fast-paced and aggressive zombie game mode developed as a companion to Zombie Mod Infection, both crafted under the legacy of Mystic Death.

Unlike Infection, where the zombie outbreak spreads over time, Annihilation dives straight into chaos — the undead are ready from the start, and survival is not optional.

🔹 What is Zombie Mod Annihilation?
A streamlined, no-nonsense version of zombie gameplay:

🧟‍♂️ Zombies spawn immediately: Terrorists are already infected at the start of each round.

⚔️ No infection system: It’s full-scale war from second one — 50% humans, 50% zombies.

🧩 Shares core resources with Zombie Mod Infection to ensure stability and compatibility.

🎭 Includes a unique zombie model that went unnoticed in the original .rar but is now officially integrated.

🛠️ Why choose Annihilation?
It’s perfect for players and server owners looking for a more direct PvP experience with no interruptions, no transitions, and no confusion. Everyone knows their role, and every second counts.

A full release including all required assets and installation support for AMX Mod X on Counter-Strike 1.6 will be available soon.

Stay alert. Stay alive — or not.
