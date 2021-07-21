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



Copyright 2021 SirJulesOnGithub

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
