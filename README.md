# TrackML - CK

In particle accelerators, collisions produce billions of particles that are then observed by detectors at various locations.
We're interested in probing those intermediate states, but they quickly decay away into myriad stable byproducts.  The only way to 
understand the parent interaction, then, is by way of analyzing these byproducts.  A key challenge in doing this is reconstructing
the byproduct particle's path, or track, from a couple of isolated detector hits.  

We develop a modified clustering algorithm that take in collision event files and assigns each hit event to a corresponding particle track.
