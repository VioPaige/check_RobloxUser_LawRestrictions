# Check_RobloxUser_LawRestrictions
this roblox modulescript contains functions to check the permissions of a user regarding viewing links to twitter, discord, youtube, etc. on a legal level




## Download
You can get the model that contains this modulescript [here](https://www.roblox.com/library/8475802956/User-Law-Restrictions) in order to use it





## Description of functions

**Make sure to remember, if a function returns nil, it doesn't mean that the function returned false, instead the function failed to retrieve the player data**


### Module.canUseDiscord(player)
* this returns true if it's legal/allowed to show discord invites and other discord related things to the specified user inside of a game

### Module.canUseYoutube(player)
* this returns true if it's legal/allowed to show youtube links and other youtube related things to the specified user inside of a game

### Module.canUseTwitch(player)
* this returns true if it's legal/allowed to show twitch links and other twitch related things to the specified user inside of a game

### Module.canUseFacebook(player)
* this returns true if it's legal/allowed to show facebook links and other facebook related things to the specified user inside of a game

### Module.canBuyRandomisedItems(player)
* this returns true if it's legal for the specified player to buy randomised items (for example: eggs, chests, etc. that have a randomised reward) *this only counts for things that the player buys for robux, they can buy anything for ingame money*

### Module.canTradePaidItems(player)
* this returns true if it's legal for the specified player to trade items they bought with real money(robux) with other players

### Module.shouldFollowChinaPolicies(player)
* this returns true if the specified user is in china(meaning their experience has to abide the chinese policies)




## Api
```
Module.canUseDiscord()
  - required arguments:
    - player : Instance (the player instance you want to get information about)
  - can return:
    - nil (failed to retrieve player data)
    - true (player is allowed to see discord related things in game)
    - false (player is not allowed to see discord related things in game)
    
Module.canUseYoutube()
  - required arguments:
    - player : Instance (the player instance you want to get information about)
  - can return:
    - nil (failed to retrieve player data)
    - true (player is allowed to see youtube related things in game)
    - false (player is not allowed to see youtube related things in game)

Module.canUseTwitch()
  - required arguments:
    - player : Instance (the player instance you want to get information about)
  - can return:
    - nil (failed to retrieve player data)
    - true (player is allowed to see twitch related things in game)
    - false (player is not allowed to see twitch related things in game)

Module.canUseFacebook()
  - required arguments:
    - player : Instance (the player instance you want to get information about)
  - can return:
    - nil (failed to retrieve player data)
    - true (player is allowed to see facebook related things in game)
    - false (player is not allowed to see facebook related things in game)

Module.canBuyRandomisedItems()
  - required arguments:
    - player : Instance (the player instance you want to get information about)
  - can return:
    - nil (failed to retrieve player data)
    - true (player is allowed to buy randomised things for money(robux), such as chests, eggs, etc.)
    - false (player is not allowed to buy randomised things for money(robux), such as chests, eggs, etc.)

Module.canTradePaidItems()
  - required arguments:
    - player : Instance (the player instance you want to get information about)
  - can return:
    - nil (failed to retrieve player data)
    - true (player is allowed to trade items they bought for money(robux) with other users)
    - false (player is not allowed trade items they bought for money(robux) with other users)

Module.shouldFollowChinaPolicies()
  - required arguments:
    - player : Instance (the player instance you want to get information about)
  - can return:
    - nil (failed to retrieve player data)
    - true (player is legally only allowed to play your game if it complies with chinese policies)
    - false (player is legally allowed to play any game)

```
