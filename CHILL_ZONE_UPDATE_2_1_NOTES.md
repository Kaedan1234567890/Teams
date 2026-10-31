# Chill Zone Teams 2.1 — source preview, uncompiled

Changes: `/team` replaces `/allied`; `/teamAdmin` replaces `/alliedAdmin`; original data directory and mod id remain `allied` for persistence compatibility. All clickable command text is updated. Team owners may use `/team storage toggle true|false`; opening shared storage requires both the admin existing `storageEnabled` master and the team-owner `storageOwnerEnabled` toggle. Existing teams default owner toggle to enabled. Admin roots now demand vanilla highest operator permission level, not an independently checked LuckPerms Owner group; this remains to be implemented before production because OP level and LP group aren't equivalent. Admin master remains under `/teamAdmin storage <team> <boolean>` and `/teamAdmin storageAll <boolean>`.

**Not compiled, not in-game tested.** This is a partial change, not the final approved feature release.
