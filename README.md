# MeshInstancedIndirect-GPU-Vegetation-Shader  

InstancedIndirect method to render lotta grass on the gpu for URP. 
  
Feature:  
1. Interactive Grass  
2. LOD(LOD Group component must present in the object. Optional!)  
3. Wind  
  
Requirements and IMPORTANT:  
1. A single flat mesh like object(as in quads or blades), or else the wind will displaced the vertexs!  

Note: to use interactive feature, playerpos.cs component must be added to the object that you want to be interacted with, e.g : Character, enemies, etc...   
  
The GrassIntanced.hlsl is work of Cyanilux. What an awesome dude :)

