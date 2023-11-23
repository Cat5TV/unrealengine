# Color Grading
This table contains the base color grading technique I use when rendering video from Unreal Engine and grading in DaVinci Resolve.

The following are all done on the Color page in DaVinci Resolve.

Fix Colorspace
==============

Match the colorspace from Unreal Engine to DaVinci Resolve:

1. Drag Color Space Transform effect to the clip.
2. Set Input Color Space to **sRGB**.
3. Set Input Gamma to **Linear**.
4. Set Output Color Space and Output Gamma both to **Rec.709**.

Grade Video
===========

1. Create a new corrector node prior to the video node.
2. Fix White Balance if needed.
3. Adjust your Shadows (Lift) and Highlights (Gain), and Offset (whole image).
4. Create a new corrector node after the video clip node / colorspace.
5. Drag Color Space Transform effect to the node.
6. Change the Output Gamma to **Cineon Film Log**.
7. Add another corrector node after that node.
8. With that new node highlighted, open LUTs.
9. In Film Looks, click the one that looks best.
10. Add another correction node at the end of the series and add Film Grain effect.


By Robbie Ferguson, [Category5 Technology TV](https://youtube.com/LinuxTechShow)
