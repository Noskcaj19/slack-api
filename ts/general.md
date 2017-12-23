# General
`TS` exposes a number of top level functions

---

## Reload 
`TS.reload(n, a, t)` triggers a reload of the page.

### Parameters
* `n` (body) an optional argument that when not `null` will display a generic popup with a message before reloading
* `a` (info) an optional argument that when not `null` will be logged
* `t` (force) an optional argument that will be passed to `location.reload()` to force refetching the page

---

## Refresh Teams

`TS.refreshTeams()` triggers a reauth and refreshes current teams

---

## Boot

`TS.boot()` seems to be the boot function, throws error when called after boot
