# Haunted House

### IMP : Instead of using random measures we are going to consider 1 unit as 1 meter.

    THREE.Group() is for grouping different meshes or objects

### Fog :

    Three.js supports fog with the Fog class
    color
    near - how far from the camera does the fog start.
    far - how far from the camera will the fog be fully opaque

    const fog = new THREE.Fog("#262837", 1, 15);
    // To activate fog we need to add fog to scene
    scene.fog = fog;

    // To fix the background, we must change the clear color of the 'renderer' and use the same color as fog.
    // We can do it with the setClearColor(...) on the renderer.
