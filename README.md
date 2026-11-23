# 📦 In This Pack

This resource pack brings back the mob spawn egg textures from before update 1.21.5, and adds textures for newer mobs in the same old artstyle. 


# 🔗 Compatibility

This resource pack should be compatible with your other packs, if it is not working try placing this resource pack above others in your pack list. 

## Bedrock Edition
This resource pack is designed exclusively for Minecraft: Java Edition. It is not intended for Bedrock Edition, including Minecraft for Windows, Pocket Edition, or any console edition. Compatibility with Java Edition emulators or alternative clients is also not guaranteed. If I could make it work on Bedrock I would, but due to the lack of item definitions on Bedrock it simply is not possible. 

## Downloads

Supports Minecraft: Java Edition **1.21.5–26.3**.

- [Modrinth](https://modrinth.com/project/Njog4jbX)
- [GitHub Releases](https://github.com/Nycto9648/Reverted-Spawn-Eggs/releases)

## Publishing

Add a repository Actions secret named `MODRINTH_TOKEN` containing a Modrinth personal access token with permission to create versions on project `Njog4jbX`. GitHub supplies `GITHUB_TOKEN` automatically.

Commit pack updates, then publish a GitHub release with a unique version tag, a title, and a changelog. The workflow builds `Reverted Spawn Eggs.zip`, attaches it to the GitHub release, and publishes the same file to Modrinth.

The default Minecraft version range is **1.21.5–26.3**. Override it for a release by adding a line such as:

```text
Minecraft versions: >=1.21.5 <=26.3
```

Do not commit tokens or manually built ZIP files.
