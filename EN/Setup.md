# How to Set Up (Uploading to VRChat)

## **1. Preparations**

Download and import [Poyomina](https://mesukemoshop.booth.pm/items/7420279) into your Unity project.


## 2. **Importing PoyominaEx**

- From the Unity menu, select **Assets → Import Package → Custom Package**.

- Specify and import the distributed file **`PoyominaExVerxxx.unitypackage`** (where xxx is the version name).

  Select Import to complete the import.

- Once the import is complete, the `00_Murixir/06Ex_PoyoEx` folder will be added to your assets.


## 3. **Placing it in the Scene**

Drag and drop the PoyominaEx.prefab onto Poyomina in the Hierarchy.

> ⚠️ <span style="color:red; font-weight:bold;">Note</span>
> Prefabs for Preset2 and Preset3 are provided individually within `/06Ex_PoyoEx/10_Presets/PresetX/`.
> This is necessary to match the color of Poyomina's Body texture.
>
> The procedure for importing PoyominaEx into a modified Poyomina is explained in the next step.

![image-20250914153538635](../Images/PoyoEx1.png)

## 4. Matching the Color

Perform the following settings to make the appearance of PoyominaEx more natural.

This step is not necessary if you are using Poyomina's presets without modification.
If you have modified and changed the texture, please refer to this guide for settings.

1. First, select the material of the `.prefab` you used.

​	If you used PoyominaEx.prefab directly under 06Ex_PoyoEx --> `/06Ex_PoyoEx/02_Materials/Preset1/`<BR>
​	If you used PoyominaEx.prefab in 06Ex_PoyoEx/10_Presets/Preset2/ --> `/06Ex_PoyoEx/02_Materials/Preset2/`<BR>
​	If you used PoyominaEx.prefab in 06Ex_PoyoEx/10_Presets/Preset3/ --> `/06Ex_PoyoEx/02_Materials/Preset3/`<BR>

![image-20250914154200383](../Images/PoyoEx2.png)

2. Edit `06_Poyomina_ExBody.mat` and `06_Poyomina_ExBody_Dark.mat` from the Inspector.
   Change the texture of Main Color 2nd to the texture used for Poyomina's Body2 (usually `06_Poyomina_Body_Base_color.png`). Make this setting for both `06_Poyomina_ExBody.mat` and `06_Poyomina_ExBody_Dark.mat`.

![image-20250914154858483](../Images/PoyoEx3.png)

## 5. **Uploading**

- In Unity, open VRChat SDK → Show Control Panel and log in with your VRChat ID.
- After logging in, you can fill in avatar information on the Builder tab. Set Name, Visibility, and a thumbnail, then upload.

> ⚠️ <span style="color:red; font-weight:bold;">Note</span>
> The Visibility setting must be set to <span style="color:red; font-weight:bold;">Private</span>.
> Setting it to Public is a <span style="color:red; font-weight:bold;">violation of the terms of use</span>!

- → From the Builder, run **Build & Publish for Windows**.

- Complete the upload. Enjoy...

