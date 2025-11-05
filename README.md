# rimworld-fertile-fields-balance-patch

Making crushed rocks, sand and clay took too long in the original Fertile Fields.  This mod makes adjustments to both the quantity and work amounts of the various recipes to help with that.

- [rimworld-fertile-fields-balance-patch](#rimworld-fertile-fields-balance-patch)
- [Adding/Removing Mid-Game](#addingremoving-mid-game)
- [Recipe Changes](#recipe-changes)
  - [Crushed Rocks](#crushed-rocks)
  - [Sand](#sand)
  - [Clay](#clay)
- [Source and Feedback](#source-and-feedback)

# Adding/Removing Mid-Game

This mod is safe to add mid-game.  

Removing it mid-game might do weird things with your workstation recipe bills.  I've not tested that.  But it's probably okay as this is just an XML patch mod which alters existing recipes and doesn't add new bills.

# Recipe Changes

Here are the recipe changes.  The goal was to reduce haul time by making bulk recipes as well as some other balance tweaks.

## Crushed Rocks

The math on this recipe didn't math out in my opinion.  Making stone chunks into stone blocks is a 1:20 ratio.  It made more sense for 1 stone block to equal 1 crushed rocks instead of the 10:1 ratio from before.  This also means that a chunk should produce 20 crushed rocks.

Some recipes are now bulk recipes (reduce hauling time):

- 1 chunk to 20 crushed rocks
- 5 chunks to 100 crushed rocks
- 10 stone blocks to 10 crushed rocks
- 100 stone blocks to 100 crushed rocks

## Sand

The original recipe was 1 crushed rock to 1 sand.  This is very slow.  Changed it to a bulk recipe to reduce hauling time. Then lowered the work amount by 1/3 and gave another 1/5 reduction on work for the 25x recipe.

- 5 crushed rock to 5 sand
- 25 crushed rock to 25 sand

## Clay

The original recipe was 1 sand to 1 clay, which results in a lot of hauling time.  Changed it to a bulk recipe. Lowered the work amount by 1/3 and gave another 1/5 reduction on work for the 25x recipe.

- 5 sand to 5 clay
- 25 sand to 25 clay

# Source and Feedback

GitHub: [WuphonsReach/rimworld-fertile-fields-balance-patch](https://github.com/WuphonsReach/rimworld-fertile-fields-balance-patch)

Issues and patch requests should be reported at GitHub on the above repository.
