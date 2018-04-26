## MisterBlue's Updated PrimMesher

This is my updated version of PrimMesher.

Edit 20180426: Dahlia also [started a fork] of the original
PrimMesher. Check out that fork at https://github.com/dahliaT/PrimMesher .
As of this date, I have combined all forks into this one.

When [SecondLife(r)] started, bandwidth to the home was limited so
they invented the [primitive] or 'prim' as it became known.
A [primitive] is a procedurally generated 3D mesh representation.
The [primitive] definition contains parameters (shape definition,
extrusion path, cuts, and twists) that can be converted into a
3D mesh.

PrimMesher is the open-source code to convert a [SecondLife(r)]
prim into a 3D mesh.

This is my knowledge of its history but I could have it wrong so
corrections are appreciated.

The original PrimMesher was written by Dahlia Trimble and kept
in the, now defunct, OpenSimulator Forge 
(```http://forge.opensimulator.org/gf/project/primmesher```).
Latif Khalifa eventually hosted and maintained 
a copy of [PrimMesher on GitHub]
which became the more-or-less 'official' source.

Sadly, Latif [passed away] leaving the repository stale.
Since it is still being used, copies of the PrimMesher source
files were included into [OpenSimulator]. Actually two different
copies were included: a default one used for physics mesh
generation and another one for the ubODE physics engine.

This version of PrimMesher attempts to bring together the best
of all  the various versions of PrimMesher out there.
If you hear of or know of bugs or needed improvements,
please add an issue.

## TODO (as of 20170704):

- Incorporate the additional LOD sculpty levels from OpenSimulator:ubODEMeshing/ScupltMesh.cs;
- Decide if code reorganizationin OpenSimulator:ubODEMeshing/SculptMesh.cs is significant or cosmetic;

[SecondLife(r)]: https://secondlife.com/
[OpenSimulator]: http://opensimulator.org/
[primitive]: http://wiki.secondlife.com/wiki/Primitive
[sculpted prim]: http://wiki.secondlife.com/wiki/Sculpted_prim
[passed away]: http://opensim-users.2152040.n2.nabble.com/Latif-Kalifa-td7582691.html
[PrimMesher on GitHub]: https://github.com/lkalif/PrimMesher
[Idealist Viewer demonstration]: https://vimeo.com/2123232
[LookingGlass Viewer]: http://lookingglassviewer.org/
[started a fork]: https://github.com/dahliaT/PrimMesher

