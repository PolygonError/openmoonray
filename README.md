# MoonRay
MoonRay is DreamWorks’ open-source, award-winning, state-of-the-art production MCRT renderer
This fork adds a Dockerfile for (attempting) to build on Ubuntu 18.04, you can find it in building/Dockerfile.ubuntu.
You can follow the [original Docker build instructions](https://docs.openmoonray.org/getting-started/installation/building-moonray/building-moonray-container/), replacing instances of 'Dockerfile' with 'Dockerfile.ubuntu', which will work up to the final step.
Fully building openmoonray does NOT currently work. [Relevent issue](https://github.com/PolygonError/openmoonray/issues/1)

## Cloning
This is the top-level repository for MoonRay opensource. The actual source code is contained in a number of other repositories referenced here as git submodules.

To clone this repository along with the submodules:
```bash
git clone --recurse-submodules https://github.com/dreamworksanimation/openmoonray.git
```

[Source Structure](https://dreamworksanimation.github.io/openmoonray-docs/developers-guide/source-structure/)  
[Building MoonRay](https://dreamworksanimation.github.io/openmoonray-docs/getting-started/installation/building-moonray/)  
[Documentation](https://dreamworksanimation.github.io/openmoonray-docs/)  
[Website](https://openmoonray.org/)  
