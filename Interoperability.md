# Interoperability

This checklist is designed to facilitate the interoperability of VR studies, ensuring that simulations, assets, and data can be used across different platforms, eliminating barriers to replication. This means that an VR simulation and its assets, produced by one or more researchers, can be redeployed by others across different hardware systems, settings, and locations.

---

## DIGITAL ASSETS

- Digital assets should be in commonly used formats.
- VR simulations should be created in commonly used engines.
- Digital assets for each project have been fully listed in an online repository (e.g., listing what environments were used, the rendering pipeline, the credits for audio files, etc.).
- Version numbers have been listed for each asset used. This should include versions of the software used to develop and apply custom assets. For example, if a model was created in Blender for use in Unity, the version number of Blender and Unity should also be reported.
- Basic characteristics of digital assets should be listed to identify eligibility for specific VR simulations (e.g., high poly / low poly, material type, animations, etc.).
- Version control should be used in projects, and version numbers should be provided for VR simulations. For example, the first study completed from a Unity project could be version 1.0, but then the second study with its modifications could be version 2.0. Making it easy to revert to 1.0, or work on 1.0 separately, can help replicability.

---

## OPEN VR

As described by the Khronos Group, OpenVR is an open standard (i.e., a common set of APIs) that allow VR simulations to run on practically any headset. In other words, OpenVR enables developers to ‘develop once, deploy everywhere’. This can greatly expand the set of headsets on which an VR simulation can be run.

- Implement OpenVR in project.
- Versions should be listed for OpenVR and any other SDK used.
- If deviating from OpenVR, provide the details of what SDK was used and list what headsets the software will run.

> **Note:** As other technologies arise with a similar architecture to OpenVR, say for audio, researchers should adopt those technologies.

---

## CUSTOMIZED SYSTEMS

When research designs require more advanced hardware or software beyond what OpenVR provides, researchers may need to use custom systems. To support replicability, they should follow open science principles and share the details of their hardware and software choices.

- Report the specific hardware and software used in the simulation.
- Apply open science principles in highly customized software.

---

## ASSET SOURCING

Care should also be taken when sourcing assets. Asset choices should be driven by an expectation that future researchers will want to replicate each study.

- Repurpose assets from previous studies when possible.
- Review and consider End User License Agreements for the assets. Preference should be given to assets that are available and can be shared for non-commercial applications.
- Purchase assets from reputable stores (e.g., Unity Asset Store or Unreal Marketplace) to ease the need of future researchers to find the assets for purchase later.
