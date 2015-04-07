# What' Up #

This document should contain list of important technical features. Especially those which would be harder to implement later. It might be also pointed out which significant technical features of modern video games won't be implemented.

# Details #

### Should be implemented: ###
  * Platform independence (via SDL)
  * Own model/object format
    * Vertices/Normals/TexCoords
      * Pre-ordered for VBOs
    * Name(s) of material script(s)
    * Each material => one mesh => one VBO
  * Material scripts
    * Textures/shaders
  * Character scripts
    * Defines what parts character consists of and how they're transformed over time
  * Cg Shader support

### Does not need to be implemented: ###
  * Keyframe/Skeletal animations
  * **Networking**
  * Any sophisticated "shadowing" algorithm
  * Any sophisticated physics engine