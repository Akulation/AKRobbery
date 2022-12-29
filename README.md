# AKRobbery
Advanced rob script that features customizable messages, customizable cooldowns.

# Features:
- Use a command to rob the player you are looking at.
- Fully customizable.
- Simple to use.
 
# Permissions:
 /rob : `rob`
 
# Config:
  ```
  "robber_message": "You are now robbing {0}, make sure to give them at least three warnings.", // {0} = victim
  "victim_message": "You are being robbed by {0}!  Make sure to listen to the robber so you dont die!", // {0} = robber
  "not_looking_at_player": "You must be looking at a player to rob them.",
  "on_cooldown_message": "You are still on cooldown for robbing.",
  
  "discord_webhook_url": "https://discord.com/api/webhooks/0000000/XXXXXXX"
  // cooldown config is on line 34
  ```
  
  Edit the config by opening the `AKRobbery.uscript` file.
 
# Installation:
First make sure you have installed uScript2 on your server.
https://discord.gg/YGNmCQYT3e

1. Add `AKRobbery.uscript` to `exampleserverfolder/uScript/scripts`
2. Use the command `script reload` in console to load the script (or restart your server)


 

