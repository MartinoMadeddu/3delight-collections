# 3delight-collections
An initial small collection of OSL patterns and eventually materials and lobes for 3delight

# Patterns

- **mmCameraProjection:**
    - *given a valid camera it creates a usable NDC space from it and can be used as uv projector in the shader (it also has a convenient float2 uv output you can plug directly in a dlUV or dlTexture node). currently not working in IPRs (working as expected in full render)*
    
- **mmShadingGlobals:**
    - *gives you access to most common shading globals (P, Ps, N, I, u, v, time etc)*

- **mmSpaceTransform:**
    - *given a type point, normal or vector input this is just a more comprehensive space transform (from_space :: to_space) node matching Mantra's style interface*

- **mmToNDC:**
    - *quick and light transform of a given P to NDC coordinates, passing global P to it give you access to render camera projection space so you can plug this as uv of your texture and project your shot plate to proxy tracking geo for example - this also works in IPR as it doesn't rely on camera_name*
