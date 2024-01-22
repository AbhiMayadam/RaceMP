# TODO 1.2.0
- Finish point to point and test
- Write some more documentation (how to use, add new track data, etc)
- ✓ Fix the vscode task, BeamNG does not load mods packed by powershell properly
    - Requires 7zip in path
- ✓ Changed compression stuff for release

## Client side
- possibly change splits format (to mirror server side)

## GUI
- ✓ fix positioning (fixed again)
- Add GUI lap counter
- Add times to the raceboard

## Levels
- Shorten prefab names in WCUSA
- Add inside barriers to Hirochi derby

## Server Side
- ✓ (changed fucntionality) change names of position indexing in laps/splits
    - position in a split/lap is now the position of the player at that point

# Rewrite (2.0?)
- Use core_hotlapping / hotlapping.lua to add BeamNG UI checkpoints.

# LATER
- Add images of GUI to README.md
- Make code consistent
- Permissions of some kind


## Race config stuff
- Possible to toggleable collisions: settings.setValue('disableDynamicCollision', true)
- Race name configuration
- Qualifying mode (sort raceboard by lap time)
- Rally mode (sort raceboard by split time)

## Client side
- add separate utilities file

## GUI
- Change chat based UI to imgui, possibly with file picker

## Server Side


# INVESTIGATE
- Moving to be a CobaltEssentials extension
- Investigate pretty names for prefabs
- Solid barriers in prefabs
- Investigate check onWaypoint and onBeamNGWaypoint
- Toggleable collisions: settings.setValue('disableDynamicCollision', true)
- Difference in time between server and client side