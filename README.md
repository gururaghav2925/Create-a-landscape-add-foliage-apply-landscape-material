# Landscape Creation and Foliage in Unreal Engine

## Aim
To create a landscape in Unreal Engine, apply a custom landscape material, and add foliage for realistic environment generation.

## Procedure

1. **Create a New Landscape:**
   - Open your Unreal Engine project.
   - Go to the **Modes Panel** and select **Landscape**.
   - Set the desired section size, number of components, and overall resolution.
   - Click **Create** to generate the landscape.

2. **Apply a Landscape Material:**
   - In the **Content Browser**, create a new **Material** and name it `M_Landscape`.
   - Open the material and:
     - Use **Landscape Layer Blend** to blend textures (e.g., grass, rock, dirt).
     - Connect appropriate texture samplers to different layers.
     - Output the final blend to the **Base Color**, **Normal**, and optionally **Roughness** inputs.
   - Save the material.
   - Select the landscape in the scene, go to the **Details Panel**, and assign `M_Landscape` to the **Landscape Material** slot.

3. **Add Foliage:**
   - Go to the **Foliage Mode** from the **Select Mode dropdown**.
   - In the **Foliage Panel**, click the **+** icon to add Static Meshes (e.g., trees, grass, bushes).
   - Adjust settings like **Density**, **Scale**, and **Randomness**.
   - Use the brush tool to paint foliage onto the landscape.

## Output

![Screenshot 2025-05-08 135337](https://github.com/user-attachments/assets/0b523414-9f03-42f5-b94a-20511cc851c6)



![image](https://github.com/user-attachments/assets/e42a434b-86a3-48d6-a789-f02fb7eea43d)


## Result
A landscape was successfully created and enhanced with:
- A layered, textured material using `M_Landscape`.
- Static mesh foliage such as trees and grass for realism.
This setup provides a foundation for open-world levels, terrain-based gameplay, or environmental simulations in Unreal Engine.
