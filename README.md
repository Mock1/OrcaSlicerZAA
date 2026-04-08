# OrcaSlicer + Z Contouring

A fork of [OrcaSlicer](https://github.com/OrcaSlicer/OrcaSlicer) adding 
**Z Contouring** (also known as Z Anti-Aliasing / ZAA) — non-planar slicing 
that varies the Z height of each extrusion to follow the model surface, 
reducing the staircase effect on curved surfaces.

## Using Z Contouring

Enable per-object via **Print Settings → Quality → Z Contouring**.

Key settings:
- **Z Contouring enabled** — turns on non-planar extrusion for this object
- **Minimize wall height angle** — reduces perimeter height on shallow slopes
  (default 35°, set 0 to disable)
- **Minimum Z height** — minimum layer step size (default 0.05mm)
- **Don't alternate fill direction** — useful for some surface types

## Building

See [OrcaSlicer's build instructions](https://github.com/OrcaSlicer/OrcaSlicer/wiki/How-to-build).

## Acknowledgements

This project is a fork of [OrcaSlicer](https://github.com/OrcaSlicer/OrcaSlicer) 
by [SoftFever](https://github.com/SoftFever) and contributors, licensed under 
[AGPL-3.0](LICENSE.txt).

The Z Contouring feature is ported from 
[BambuStudio-ZAA](https://github.com/zaalbarxx/BambuStudio-ZAA) by zaalbarxx.

OrcaSlicer is built on:
- [BambuStudio](https://github.com/bambulab/BambuStudio) by Bambu Lab
- [PrusaSlicer](https://github.com/prusa3d/PrusaSlicer) by Prusa Research
- [Slic3r](https://github.com/Slic3r/Slic3r) by Alessandro Ranellucci 
  and the RepRap community

**I take zero credit for this, this is 100% Claude.** I don't even know C++. But it did such a good job, I'm putting it out there.

## License

GNU Affero General Public License v3.0 — see [LICENSE.txt](LICENSE.txt).