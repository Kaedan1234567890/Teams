# Team command visibility trial

`/team` is also a built-in Minecraft scoreboard command. This trial registers `/teams` (plural) to avoid the vanilla command collision. `/teamAdmin` is still restricted to vanilla operator-level owners as in the previous source, NOT yet to the LuckPerms Owner group.

This is a compatibility/visibility workaround, not the desired final `/team` name. Does not compile or prove permission integration. No special LuckPerms use permission is needed for `/teams` because these Brigadier commands require player only.
