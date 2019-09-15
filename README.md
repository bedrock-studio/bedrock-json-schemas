Minecraft: Bedrock Edition Addon Schemas
========================================

These are JSON schemas for the various components of a Minecraft: Bedrock Edition Addon


## How to Use (VS Code)

Copy the settings from `vscode-settings.json` to your workspace or user settings.


## How to Use (Other)

For other programs/IDEs you will need to set it up yourself. The main files you'll want to configure are:

| Description           | File                                          |
|-----------------------|-----------------------------------------------|
| The addon manifest    | manifest.json                                 |
| Animation controllers | actor_animation_controller.json               |
| Animations            | actor_animation.json                          |
| Entities              | client_entity.actor_resource_definition.json  |
| Attachables           | attachable.actor_resource_definition.json     |
| Render controllers    | render_controller.json                        |
| Entity Geometry       | geometry.json                                 |


## Current Status

- Manifest v1 ✔️
- Manifest v2 ✔️
- Actor Animation Controller v1.8.0 ✔️
- Actor Animation Controller v1.10.0 ✔️
- Actor Animations v1.8.0 ✔️
- Actor Resource Definition v1.8.0 ✔️
- Actor Resource Definition v1.10.0 ✔️
- Render Controller v1.8.0 ✔️
- Geometry v1.1.0 ✔️
- Geometry v1.8.0 ✔️
- Geometry v1.12.0 ✔️
- Block Geometry v0.0.0? 🚫
- Biome v1.12.0 🚫
- Block v1.10.0 🚫
- Item v1.12.0 🚫
- Particles v1.10.0 🚫
- Recipe v1.12 🚫