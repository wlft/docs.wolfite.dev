---
title: Usage
---

# Using Hydrogen

## Converting a link

Let's say you want to convert a link from a standard Roblox endpoint to Hydrogen. Lets say you want to convert `https://games.roblox.com/v2/games/323675642/media` to a working Hydrogen link. You would end up with `https://hydrogen.wolfite.dev/roblox/games/v2/games/323675642/media`.

## How it works

Hydrogen converts the api link from it's standard `{api}.roblox.com` to https://hydrogen.wolfite.dev/roblox/{api}/. So `https://games.roblox.com/*` would be `https://hydrogen.wolfite.dev/roblox/games/*`