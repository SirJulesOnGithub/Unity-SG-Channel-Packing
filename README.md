# Unity-SG-Channel-Packing

Unity3D Shader Graph Shaders with Channel Packing for URP

__Lit-Packed-3Textures:__
- Texture 1 : Albedo(RGB), Transparent(A) 
- Texture 2 : Metalic(R), Ambient Occlusion(G), Smoothness(B)
- Texture 3 : Normal/Bump Map)

__Lit-Packed-2Textures:__
- Texture 1 : Albedo(RGB), Ambient Occlusion(A)
- Texture 2 : Normal R(R), Metalic(G), Smoothness(B), Normal G(A)

_Note: this shader saves disk space, but reconstructs the Z-value of Normal Map, so it is more computationally intensive_
