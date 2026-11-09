# Depth Mask AR with Vuforia

A Unity maze scene for exploring marker-based AR and depth masking. A depth mask lets a virtual object hide parts of the rendered scene without drawing a visible surface of its own.

## Open the demo

1. In Unity Hub, add the nested [Maze](Maze) project folder and open it with **Unity 2021.3.3f1**.
2. Resolve **Vuforia Engine 10.8.4** from the local archive referenced in [Packages/manifest.json](Maze/Packages/manifest.json). Run `git lfs pull` if the checkout contains pointers for required assets.
3. Open [SampleScene](Maze/Assets/Scenes/SampleScene.unity) and inspect the AR camera, image target, and maze setup.
4. Configure Vuforia for your device and build to test with the configured target.
