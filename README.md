# VTComfy

VTComfy is an open-source creative studio interface for the ComfyUI ecosystem,
built for the Comfy Open Source Higgsfield challenge.

## Current status

This first slice adopts the proven OpenSfield/Higgsfield-style studio shell:
top navigation, Image/Video/Audio workspaces, Cinema Studio, apps, generations,
elements and creator hub. The backend and VTComfy workflows will be connected
next.

## Preview

Serve the interface locally:

```bash
python3 -m http.server 8765 --directory app/static
```

Then open <http://127.0.0.1:8765>.

## Attribution

The initial interface layer is adapted from
[OpenSfield](https://github.com/codyclack/opensfield), licensed under the MIT
License. The original license is preserved in `LICENSE.opensfield`.

VTComfy is an independent project and is not affiliated with Higgsfield AI.
