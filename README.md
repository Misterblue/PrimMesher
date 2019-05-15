## MisterBlue's Updated PrimMesher

This is my updated version of PrimMesher.

Edit 20190508: CinderBlocks keeps another version of PrimMesher as
part of the [LibreMetaverse] version of [libOpenMetaverse].
I've looked through the changes and most (if not all) the modifications
are stylistic (using 'var' over explicit type, etc). If anyone knows of
functional changes, please [report an issue].

Edit 20180426: Dahlia also [started a fork] of the original
PrimMesher. Check out that fork at https://github.com/dahliaT/PrimMesher .
As of this date, I have combined all forks into this one.

### History

When [SecondLife(r)] started, bandwidth to the home was limited so
Linden Labs invented the [primitive] or 'prim' as it became known.
A [primitive] is a procedurally generated 3D mesh representation.
The [primitive] defines parameters (shape definition,
extrusion path, cuts, and twists) that are converted into a
3D mesh for display.

PrimMesher is open-source code that converts one of these [SecondLife(r)]
prims into a 3D mesh.

The original PrimMesher was written by Dahlia Trimble and kept
in the, now defunct, OpenSimulator Forge 
(```http://forge.opensimulator.org/gf/project/primmesher```).
Latif Khalifa eventually hosted and maintained 
a copy of [PrimMesher on GitHub]
which became the more-or-less 'official' source.

Sadly, Latif [passed away] leaving the repository stale.

Since PrimMesher is still being used, copies of the PrimMesher source
files have been copies and reused. Copies of PrimMesher sources are
included in [OpenSimulator] and a derived version is part of
[LibreMetaverse].

Because PrimMesher creates faceted meshes (separate faces for the
prim), it is also used by projects that display prim based regions.
Examples of these are the [LookingGlass Viewer] and [Radegast].

This version of PrimMesher attempts to bring together the best
of all  the various versions of PrimMesher out there.
If you hear of or know of bugs or needed improvements,
please [report an issue].

And, any corrections to the above history are appreciated.

## TODO (as of 20190515):

- Incorporate the additional LOD sculpty levels from OpenSimulator:ubODEMeshing/ScupltMesh.cs;
- Decide if code reorganization in OpenSimulator:ubODEMeshing/SculptMesh.cs is significant or cosmetic;
- Review and encorporate any functional changes from the [LibreMetaverse] version;

[LibreMetaverse]: https://bitbucket.org/cinderblocks/libremetaverse/src/master/
[libOpenMetaverse]: https://github.com/openmetaversefoundation/libopenmetaverse
[report an issue]: https://github.com/Misterblue/PrimMesher/issues
[SecondLife(r)]: https://secondlife.com/
[OpenSimulator]: http://opensimulator.org/
[primitive]: http://wiki.secondlife.com/wiki/Primitive
[sculpted prim]: http://wiki.secondlife.com/wiki/Sculpted_prim
[passed away]: http://opensim-users.2152040.n2.nabble.com/Latif-Kalifa-td7582691.html
[PrimMesher on GitHub]: https://github.com/lkalif/PrimMesher
[LookingGlass Viewer]: http://lookingglassviewer.org/
[Radegast]: http://github.com/radegastdev/radegast.git
[started a fork]: https://github.com/dahliaT/PrimMesher

