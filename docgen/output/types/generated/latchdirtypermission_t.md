---
title: LatchDirtyPermission_t
index: true
order: 2
category:
  - Guide
---

# LatchDirtyPermission_t
::: tabs
@tab Lua
```lua
LatchDirtyPermission_t = {
    LATCH_DIRTY_DISALLOW = 0x0,
    LATCH_DIRTY_SERVER_CONTROLLED = 0x1,
    LATCH_DIRTY_CLIENT_SIMULATED = 0x2,
    LATCH_DIRTY_PREDICTION = 0x3,
    LATCH_DIRTY_FRAMESIMULATE = 0x4,
    LATCH_DIRTY_PARTICLE_SIMULATE = 0x5
}
```
:::