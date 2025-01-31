# Skinned-Mesh-Armature-Remapper
**A Unity Editor utility that can transfer skinned mesh renderers from one armature to another. 
This does not automatically weight anything, it just lets you use a mesh on a specified armature instead of only the one it was imported with.**

***Some uses for this tool include:***
- Adding meshes to an existing configured model
- Replacing meshes to update instead of reimporting
- Refreshing every mesh on the model while maintinging original armature

*(And more)*

# Videos
### Example:
https://user-images.githubusercontent.com/90723146/139330629-c4a3f25f-565b-4424-8895-b95f454c1310.mp4


### Youtube Walkthrough Tutorial:
https://img.youtube.com/vi/N2BVAn7m2y4/0.jpg)](https://www.youtube.com/watch?v=N2BVAn7m2y4)

# How to Use
**1. You can access the editor window by toing to the top toolbar and going to Tools/Cascadian/Skinned-Mesh-Armature-Remapper.**

![image](https://user-images.githubusercontent.com/90723146/138570521-a9e0e431-d6f8-456c-a9e0-1439e369c71d.png)

**2. Drag in any skinned mesh renderer (Body mesh usually) from the base armature you want to use in the first slot.** ***Make sure the Base armature is humanoid. The other mesh armatures do not need to be.***

![image](https://user-images.githubusercontent.com/90723146/138570540-46d97e76-2f1f-485a-bdb8-c6738298bacb.png)

**3. After that, drag in the skinned meshes you want to bind to the base armature.**

![image](https://user-images.githubusercontent.com/90723146/138570556-e541b9b6-cc01-4f53-a383-1a4bb899e21d.png)

*(In this case, the Shoes and Skirt are being remapped to match the armature the body is attached to)*

**4. Press the "Remap Bones" Button and that's it! You can delete the old empty armatures from the scene now.** ***Only bones with the SAME NAME will be remapped. Any new bones will be ignored.***

**BEFORE:**

![image](https://user-images.githubusercontent.com/90723146/138570569-d66afa7d-7e5e-48ef-b035-261811935743.png)

**AFTER:**

![image](https://user-images.githubusercontent.com/90723146/138570575-f82bccfa-2a1b-4766-8208-2723c2c29663.png)

# **Download**
To download, go to the releases and download the .cs file and add it to your Unity project.

https://github.com/CascadianWorks/Skinned-Mesh-Armature-Remapper/releases
