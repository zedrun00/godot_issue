### Tested versions

[4.4 dev3](https://godotengine.org/download/archive/4.4-dev3)

### System information

win10 21H2,Vulkan API 1.2.0

### Issue description


![B`}0_G%H8QZC3B3Q}UFUW{D](https://github.com/user-attachments/assets/e83d11cb-9897-4365-b3f1-22a185fc121d)


```
Godot Engine v4.4.dev3.official.f4af8201b - https://godotengine.org
libpng warning: iCCP: cHRM chunk does not match sRGB
Vulkan 1.3.242 - Forward+ - Using Device #0: NVIDIA - NVIDIA GeForce RTX 3080

ERROR: Basis [X: (1, 0, 0), Y: (0, 0, 0), Z: (0, 0, 1)] must be normalized in order to be casted to a Quaternion. Use get_rotation_quaternion() or call orthonormalized() if the Basis contains linearly independent vectors.
   at: (core/math/basis.cpp:725)
ERROR: FATAL: Index p_index = 620 is out of bounds (count = 620).
   at: operator[] (./core/templates/local_vector.h:177)

================================================================
CrashHandlerException: Program crashed with signal 4
Engine version: Godot Engine v4.4.dev3.official (f4af8201bac157b9d47e336203d3e8a8ef729de2)
Dumping the backtrace. Please include this when reporting the bug to the project developer.
[1] error(-1): no debug info in PE/COFF executable
[2] error(-1): no debug info in PE/COFF executable
[3] error(-1): no debug info in PE/COFF executable
[4] error(-1): no debug info in PE/COFF executable
[5] error(-1): no debug info in PE/COFF executable
[6] error(-1): no debug info in PE/COFF executable
[7] error(-1): no debug info in PE/COFF executable
[8] error(-1): no debug info in PE/COFF executable
[9] error(-1): no debug info in PE/COFF executable
[10] error(-1): no debug info in PE/COFF executable
[11] error(-1): no debug info in PE/COFF executable
[12] error(-1): no debug info in PE/COFF executable
[13] error(-1): no debug info in PE/COFF executable
[14] error(-1): no debug info in PE/COFF executable
[15] error(-1): no debug info in PE/COFF executable
[16] error(-1): no debug info in PE/COFF executable
[17] error(-1): no debug info in PE/COFF executable
[18] error(-1): no debug info in PE/COFF executable
[19] error(-1): no debug info in PE/COFF executable
[20] error(-1): no debug info in PE/COFF executable
[21] error(-1): no debug info in PE/COFF executable
[22] error(-1): no debug info in PE/COFF executable
[23] error(-1): no debug info in PE/COFF executable
[24] error(-1): no debug info in PE/COFF executable
[25] error(-1): no debug info in PE/COFF executable
[26] error(-1): no debug info in PE/COFF executable
[27] error(-1): no debug info in PE/COFF executable
-- END OF BACKTRACE --
================================================================

```

### Steps to reproduce

1. create new project
2. export  glb file
3. 99% crash
