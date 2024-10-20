---
title: Switch
index: true
order: 2
category:
  - Guide
---

# Switch
Allows for a switch-like behavior in Lua, matching a value against a set of cases. It supports functions or direct values for each case and includes a default fallback.
::: tabs
@tab Lua
```lua
@returns any
switch(key --[[ string ]], switch_table --[[ table ]])
```
#### Example
```lua
local result = switch("hello", {
    hello = function() return "world" end,
    goodbye = "farewell",
    default = function() return "unknown" end
})
print(result) -- Output: world
```
:::