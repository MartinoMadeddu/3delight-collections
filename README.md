# 3delight-collections
An initial small collection of OSL patterns and eventually materials and lobes for 3delight

# Patterns

- mmCameraProjection:-
    given a valid camera it creates a usable NDC space from it and can be used as uv projector in the shader (it also has a convenient float2 uv output you     can plug directly in a dlUV or dlTexture node). currently not working in IPRs (working as expected in full render)
    
- mmShadingGlobals:
    gives you access to most common shading globals (P, Ps, N, I, u, v, time etc)

- mmSpaceTransform
- mmToNDC
