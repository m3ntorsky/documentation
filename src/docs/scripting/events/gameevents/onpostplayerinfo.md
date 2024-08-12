---
title: OnPostPlayerInfo
index: true
order: 2
category:
  - Guide
---

# OnPostPlayerInfo
This event is triggered after player_info is triggered.
::: tabs
@tab Lua
```lua
@event returns void
AddEventHandler("OnPostPlayerInfo", function(event --[[ Event ]])
    --[[ ... ]]
    return EventResult.Continue
end)
```

:::
|    Key    | Data Type |
| :-------: | :-------: |
|   `name`  |  `string` |
|  `userid` |   `int`   |
| `steamid` |  `uint64` |
|   `bot`   | `boolean` |