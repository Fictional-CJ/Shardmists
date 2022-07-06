# **NOTE: THIS MOD IS HEAVILY W.I.P AND MOST FEATURES WILL NOT BE ADDED UNTIL LATER**
*also sorry about the messy layout*
*if any of this contradicts any other part please let me know as i'm not the best proof-reader and this was made over several months*


# Shardmists Mod


# Gamemodes
## Shard
- Can only be seen by spectators, shards, normal avatars and shardmist avatars
- Can reveal themselves to creative mode players, and people with a strong connection to their Intent, so long as they are not being blocked
- Has spectator mode movement, as well as most things being unable to affect them
- Has “shard only” chat
- Only one player can be a certain shard at any time, although one person can have multiple shards
 - Can be changed in config or using operator commands
- Can give up power, returning to survival mode, and the power can be absorbed by someone else
- Can spectate someone else and whisper to them even if being blocked, however being blocked will make some text obfuscated
- Can store up investiture to create survival-friendly blocks in a creative-like menu
- Has access to ender chest tab rather than saved hotbar tab (because I know how OP that would be in survival servers - I want to at least SOMEWHAT balance it)

## Shardmist Avatar
- can be seen by all gamemodes, and bronze allomancy (and other detection investiture) reveals a line the same colour that is connected to the shard
- has same speech requirements as shard
- looks like a misty outline of a player
- has survival mode movement and cannot equip armour, but can still hold items
- cannot take damage or be targeted by mobs
- does not have creative mode item spawn but can still access ender chest
- Shardmist avatars have no nametag or skin, but have a mist texture that is coloured based on the shard.

## Avatar
- can be seen by all gamemodes, looks like a normal survival mode player
- has infinite allomantic reserves, however they refill over time rather than instantly refilling like the shard and shardmist avatar. (this is for preservation, other shards would get different powers)
- does not have creative mode items spawn and needs an ender chest in order to access their ender chest inventory
- can speak like a normal survival mode player, as well as speaking in shard chat
- burning bronze as a shard, shardmist avatar or avatar also shows a coloured line with the colour based on the colour of the shard, meaning that shards can see who is an avatar
 - Needs a compatible allomancy mod to do so (see compatibilities)
- sees shards, but more transparently than if in shard or shardmist form

# Mechanics
## Blocking
Shards can interfere with each other’s actions, so long as the shard interfering chooses to do so before or as the action is being taken. All ability cooldowns are quadrupled while blocking another. Blocking a shard does not prevent them blocking you, and certain actions are unavailable when blocking others.

## Avatar Creation
At any point in time, a Shard can decide to become an Avatar or a Mist Avatar, both of which are described above. At any point they can choose to revert back, although turning into a mist avatar or normal avatar can be countered by blocking, as can the process of turning from a normal avatar into a full shard.

Avatars work similarly to survival mode players, with a few buffs tailored to each shard. These buffs will be explained later on. Avatars have a few Shardic features, such as Blocking, but cannot do much else compared to a normal player.

Mist Avatars, on the other hand, are extremely limited. They cannot be harmed, can only harm if not being Blocked, and cannot destroy or place blocks without a charge of investiture. (see later section) The benefit of a Mist Avatar, as opposed to a Normal Avatar, is that you can turn back at any time no matter whether you are being blocked or not.

## Intent Orientation
A player’s actions will over time orient them to intents. These Intents do not cancel each other out directly, however doing something that would gain Preservation will most likely lose Ruin and vice versa as they are more or less opposites. The stronger an Intent is, the closer your connection to the Shard associated with it, to the point where if the Shard has no vessel you can pick it up. This connection can also have benefits if you are friends with the shard, as they can interact more with you.
Each intent also has an associated colour, however the bearer of the shard can change this with enough investiture.
If you pick up multiple shards then the colour is an average between them.
Intents:
- Devotion
 - Default colour #ffffff
- Dominion
 - Default colour #000000
- Preservation
 - Default colour #ffffff
- Ruin
 - Default colour #000000
- Odium
 - Default colour #ffcc00
- Cultivation
 - Default colour #00ff00
- Honor (unfortunately not Honour as it’s a name)
 - Default colour #00ffff
- Endowment
 - Default colour #005500
- Autonomy
 - Default colour #??????
- Ambition
 - Default colour #cc00cc
- Invention
 - Default colour #??????
- Mercy
 - Default colour #??????
- Valor
 - Default colour #??????
- Whimsy
 - Default colour #??????
- ???????
 - Default colour #??????
- ???????
 - Default colour #??????


# Shard Specific Features
## Preservation
### Shard
As the source of Allomancy, Preservation can directly fuel Allomancy to keep a player’s Allomantic reserves filled. So long as Preservation is fueling this user, they will not run out of charge. This ability cannot be used on someone with a Hemalurgic Spike, unless the bearer of Preservation also has the shard of Ruin.
This would be designed to use Lego’s mod, and therefore this feature would simply be rendered inoperable without it. Possible compatibilities with other mods in the future.

### Avatar (Normal)
As Preservation, you get the ability to slowly gain an Allomantic charge. It will take approximately 1.5x to fill an Allomantic charge than to use it, meaning that Allomancy cannot be used infinitely.
This would be designed to use Lego’s mod, and therefore this feature would simply be rendered inoperable without it. Possible compatibilities with other mods in the future.



# Commands & Items
## Commands
- /mist [spawn/despawn] [shard] {spawns or despawns mists that cover the land at night}
- /shard [add/grant/revoke/kick/intent]
 - [add/kick] [player] {forces the player to have or not have shard powers}
 - [grant/revoke] {allows or stops allowing a player to absorb a shard power (if the shard power is free)}
 - [intent] [add/remove/get/set] {sets the Intent Orientation of a player}
  - [add] [player] [intent] [integer] {adds a set amount to the player’s intent}
  - [remove] [player] [intent] [integer] {removes a set amount to the player’s intent}
  - [get] [player] [intent] {gets the player’s level of intent orientation for the specified intent}
  - [set] [player] [intent] [integer] {forces the player’s intent orientation to a specific number}
- /shardpower [spawn/despawn] [shard] {spawns a concentrated bit of power that can be absorbed by someone who is able to use that shard power}

## Items

# Mod compatibilities
This mod would be designed to have compatibility with Lego's Allomancy mod, my Cosmere API, as well as possibly other cosmere mods.
