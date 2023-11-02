# Cat5TV // unrealengine
Tools I've created to help me work with Unreal Engine for Category5 Technology TV

tiff2ue
=======

Convert TIFF sequence output from DaVinci Resolve to PNG or Optimized JPG sequence specially built for UE, including a UE Image Sequence Proxy. Must be run on Linux or in WSL on Windows. Multi-threaded to increase performance / reduce time required.

Supports both Cast and Screen output:

Cast - PNG sequence containing an actor with a dynamic alpha, such as a person moving. Alpha is maintained.

Screen - JPG seqeunce for something like a computer screen or TV screen in-game. Alpha, if it exists, is discarded.

console_variables.md
====================

[console_variables.md](console_variables.md) contains a table of the console variables I use when rendering video from Unreal Engine.
