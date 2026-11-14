# material-maker-mcp

Servidor MCP para Material Maker: crea grafos de materiales `.ptex` y los renderiza a mapas PBR en headless.

## Tools
- `listar_nodos`, `describir_nodo`: catálogo de nodos (398)
- `crear_material`: grafo .ptex desde nodos y conexiones
- `plantilla_material`: grafo PBR canónico desde un nodo base
- `combinar_materiales`: mezcla dos .ptex con un nodo blend
- `inspeccionar_material`: nodos, conexiones y parámetros de un .ptex
- `render_material`, `render_ejemplo`: export de mapas PBR
- `listar_ejemplos`, `listar_targets_export`, `instalar_material_maker`

## Requisitos
Python 3.12+ y Material Maker en `~/Applications/material_maker`.

## Nota
El target `Blender` falla en headless; usa `Godot/Godot 4 Standard` y conecta los PNG en Blender.
