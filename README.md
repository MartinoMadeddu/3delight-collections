# 3delight-collections
An initial small collection of OSL patterns and eventually materials and lobes for 3delight

# Patterns

- mmCameraProjection
    given a valid camera it creates a usable NDC space from it and can be used as uv projector in the shader (it also has a convenient float2 uv output you can plug directly in a dlUV or dlTexture node). think multiple cameras matte painting projection etc. currently not working in IPRs (working as expected in ful render)
    
- mmShadingGlobals
- mmSpaceTransform
- mmToNDC
