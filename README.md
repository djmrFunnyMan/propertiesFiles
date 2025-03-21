# Euphoria Patches Properties Files
Welcome to the community-driven ``.properties`` files!
## How to contribute
- A Pull Request can be opened and the changes will be merged with Euphoria Patches.
- The raw property file can also be shared on [Discord](https://euphoriapatches.com/discord) for those who have not worked with GitHub before.

## - Please use the Template!
## - Please document mods in addedMods.md!
## Template
### At the top of each property file, there is a template on how new entries should look like
<details><summary><ins><strong>Click</strong></ins> to expand for block.properties template!</summary>
<p>

#### Template for Modded Blocks:
```properties
# Description of the block ID
block.XXXXX = vanillaId1 vanillaId2 vanillaId3 ... \
\
modName1:modId1 modName1:modId2 modName1:modId3 ... \
\
modName2:modId1 modName2:modId2 modName2:modId3 ... \
\
...
lastModInThisIDName:modId1 lastModInThisIDName:modId2 lastModInThisIDName:modId3

# Description of the Next block ID
block.YYYYY = ...
...

- The last line of a block.XXXX does not have a "\"

--- IDs should be grouped by mods, for every new mod it should be added in a new line using "\" ---
```
</p>
</details>

<details><summary><ins><strong>Click</strong></ins> to expand for item.properties template!</summary>
<p>

#### Template for Modded Items:
```properties
# Description of the item ID
item.XXXXX = vanillaId1 vanillaId2 vanillaId3 ... \
\
modName1:modId1 modName1:modId2 modName1:modId3 ... \
\
modName2:modId1 modName2:modId2 modName2:modId3 ... \
...
lastModInThisIDName:modId1 lastModInThisIDName:modId2 lastModInThisIDName:modId3

# Description of the Next item ID
item.YYYYY = ...
...

- The last line of a item.XXXX does not have a "\"

--- IDs should be grouped by mods, for every new mod it should be added in a new line using "\" ---
```
</p>
</details>

<details><summary><ins><strong>Click</strong></ins> to expand for entity.properties template!</summary>
<p>

#### Template for Modded Entities:
```properties
# Description of the Entity ID
entity.XXXXX = vanillaId1 vanillaId2 vanillaId3 ... \
\
modName1:modId1 modName1:modId2 modName1:modId3 ... \
\
modName2:modId1 modName2:modId2 modName2:modId3 ... \
...
lastModInThisIDName:modId1 lastModInThisIDName:modId2 lastModInThisIDName:modId3

# Description of the Next Entity ID
entity.YYYYY = ...
...

- The last line of a entity.XXXX does not have a "\"

--- IDs should be grouped by mods, for every new mod it should be added in a new line using "\" ---
```
</p>
</details>

<details><summary><ins><strong>Click</strong></ins> to expand for dimension.properties template!</summary>
<p>

#### Template for Modded Dimensions:
```properties
dimension.world-1 = vanillaId1 vanillaId2 \
\
modName1:modId1 modName1:modId2 modName1:modId3 ... \
\
modName2:modId1 modName2:modId2 modName2:modId3 ... \

dimension.world1 = ...
...

--- IDs should be grouped by mods, for every new mod it should be added in a new line using "\" ---
```
</p>
</details>
This template was implemented so modded blocks can be easily added without having the risk of vanilla blocks being edited and one can easily see which mods are already supported as different mods are in different lines. 

## Documentating Changes
Once you've added your blocks, please go to addedMods.md and add what mod you've added with the appropriate status following this template.
<details><summary><ins><strong>Click</strong></ins> to expand for addedMods.md template!</summary>

<p>

```markdown
| [modName1](modLink) | Mod's Version | Mod's Added Status | #Optional Comment
```
<p>
</details>

Also please keep this list alphebeticlly sorted for ease of reading!

## Version
- Each property file has an independent version system which increases when a vanilla component has been changed, it does not increase when the community has added modded entries
- The properties files will always be up-to-date with the Euphoria Patches dev versions

## Tips And Tricks
- Use mod [ItemStackExporter](https://modrinth.com/mod/itemstackexporter) to export many modded blocks at once via JEI or REI or just the normal vanilla inventory.
- Use mod [Euphoria Companion](https://modrinth.com/mod/euphoria-companion) to gather an external list of all blocks registered within the current game.
- How to create a fork: [Instructions](https://www.git-tower.com/learn/git/faq/github-fork-repository)
- How to create a pull request from a fork: [Instructions](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)
- Read the documentation left within the files!
- Ask on [Discord](https://euphoriapatches.com/discord) if questions arise.
