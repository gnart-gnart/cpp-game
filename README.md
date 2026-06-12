# C++ Game
This repository will be a long-term project for professional development
as well as my own enjoyment. I will be coding a cross-platform desktop
application with 3D graphics and online multiplayer. This is ambitious
and will likely take a long time.

I'll be starting from the ground up using this guide:
[Khronos Vulkan Tutorial](https://docs.vulkan.org/tutorial/latest/00_Introduction.html).

Started on: June, 12th, 2026.

## High-Level Vulkan Notes
### Lesson 1: Drawing a Triangle
Most operations in Vulkan are asynchronously executed by submitting them to a `vk::Queue`.