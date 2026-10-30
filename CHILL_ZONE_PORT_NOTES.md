# Allied 2.0.0 Chill Zone — 26.3 compatibility prototype (unverified)

This is a **direct-source compatibility candidate** from the user-supplied Allied-master.zip. The original MIT LICENSE, original Java classes, commands, assets, and configurations are retained. No team features or permission changes are intentionally introduced.

Changes:
- Minecraft target 26.2 -> 26.3 (fabric.mod.json and Gradle)
- Fabric API 0.165.0+26.3, Placeholder API 3.2.0+26.3, Loom 1.19-SNAPSHOT
- Version identifier 2.0.0-chillzone-26.3-alpha1
- GitHub Actions build workflow with JDK 25

This build is NOT compiled or verified. It may require additional Java API compatibility patches, and source-level checks are not a substitute for in-game testing. Run GitHub Actions and share the first actual compilation error if any. Install the non-sources JAR from build/libs only after build passes; avoid keeping other Allied JARs concurrently.


## Alpha 2 (configuration test)
Removed unnecessary Fabric API client data-generation configuration from server-only build. Changed GitHub build output to plain, non-stacktrace for easier identification of the first Gradle error. Not yet compiled or in-game verified.
