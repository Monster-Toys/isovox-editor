# Isovox-Editor

*A GPU-accelerated voxel-based editor for isometric pixel art, inspired by Aseprite’s intuitive 2D workflow and MagicaVoxel’s powerful 3D tooling.*

## Project Status

**v0.1.0 - Early development**: No binaries, installer, or usable editor yet.

## Core Concepts / Planned Features

### Multiple GPU-Powered Workspaces

Work seamlessly in 2D, isometric projection, or full 3D:
- **2D Canvas:** Edit slices along any axis (X, Y, Z) with onion-skinning for depth alignment.
- **Isometric Projection:** Paint directly in an isometric view, via real-time camera projection or layer-based editing.
- **3D Workspace:** Work with a cube-mesh representation of voxel data.
- Visualize adjacent or repeating tiles across all workspaces for seamless transitions.
- Auto-generates albedo, normal, and depth-offset maps.

### Brush System

Use familiar pixel-art tools in 2D and 3D:
- **2D Brushes:** Pencil, shapes, lines, flood fill, selection, move, etc.
- **3D Brushes:** Extend 2D tools into 3D space, painting across multiple slices at once with primitives or custom brushes.

### 3D Model Conversion

Import textured 3D models from your favorite software and convert them into fully editable isovox objects at the click of a button.

### Export Options

- **Isovox file**: Compressed format to save editor projects, including additional data (undo/redo steps and non-destructive workflow data) for seamless work over multiple sessions.
- **Isometric sprites:** Supports all common isometric tile types.
- **3D texture**: For engine integration.
- **Texture atlas**: For engine integration, if 3D textures are not supported.
- **Mesh**: For use in other 3D software.

## Roadmap 
(subject to change)

[&nbsp;&nbsp;&nbsp;] Initial Setup (v0.1.0)  
[&nbsp;&nbsp;&nbsp;] 2D workspace (v0.1.1)  
[&nbsp;&nbsp;&nbsp;] Isometric projection (v0.1.2)  
[&nbsp;&nbsp;&nbsp;] 3D workspace (v0.1.3)  
[&nbsp;&nbsp;&nbsp;] Brush system 2D (v0.1.4)  
[&nbsp;&nbsp;&nbsp;] Brush system Isometric (v0.1.5)  
[&nbsp;&nbsp;&nbsp;] Brush system 3D (v0.1.6)  
[&nbsp;&nbsp;&nbsp;] Model import & conversion (v0.1.7)  
[&nbsp;&nbsp;&nbsp;] Save & export (v0.1.8)  
[&nbsp;&nbsp;&nbsp;] Alpha Release (v0.2.0)

## Screenshots

Coming soon...

## License

This project is currently closed-source and proprietary. All rights are reserved.  
The future licensing and distribution model for public release is still under consideration.

## Community & Contact

For any questions, feedback, or business inquiries, feel free to reach out:

- **Website** [isovox-editor.com](https://www.isovox-editor.com) *(As of now, this domain forwards directly to this page.)*
- **Development Repository:** [isovox-editor-dev](https://github.com/Monster-Toys/isovox-editor-dev) *(Private repository)*
- **Email:**    [hello@monster-toys.com](mailto:hello@monster-toys.com)
- **Discord:** [Monster-Toys Community Server](https://discord.gg/UmJzynyRsp)
- **GitHub:** [Monster-Toys](https://github.com/Monster-Toys)
