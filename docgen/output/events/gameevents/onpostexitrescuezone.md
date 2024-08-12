---
title: OnPostExitRescueZone
index: true
order: 2
category:
  - Guide
---

# OnPostExitRescueZone
This event is triggered after exit_rescue_zone is triggered.
::: tabs
@tab Lua
```lua
@event returns void
AddEventHandler("OnPostExitRescueZone", function(event --[[ Event ]])
    --[[ ... ]]
    return EventResult.Continue
end)
```

:::
|    Key   | Data Type |
| :------: | :-------: |
| `userid` |   `int`   |