# Unity3DToolset
# Unity NPC Navigation Sandbox

A simulation environment featuring NPC agents, player/dog entities, leash physics, and procedural terrain systems.

## Features
- NPC navigation with obstacle avoidance
- Player/dog system with leash mechanics
- Procedural terrain generation via noise
- Editor-time mesh noise tool (ProceduralMeshNoiseEditor)
- Box-based "places" (homes, workplace, park, mall)

## Architecture
- NavMesh-based movement controllers
- Noise deformation applied to mesh vertices
- Editor script ensures live updates
- NPCs avoid terrain edges and stay on playfield

## Roadmap
- Routine system (daily schedule)
- Behaviour trees
- Dynamic terrain events

Created by **Max Christian Heinrich Flinker**.
