# GLAL
GLAL - Graphic Libraries Abstraction Layer

Abstraction Layer For Native Graphics API's For Each Platform, Put Into One For,
 macOS, iOS, appleTVOS, ipadOS, watchOS - Metal,
 Windows - DirectX,
 Linux - Vulkan,
 Android - OpenGLES
  and also it checks the versions of macOS,iOS,ipadOS,watchOS,appleTVOS and assign which API to use(Metal or OpenGLES),
 same for android(Vulkan or OpenGLES).

The version of each graphics API(Metal/Vulkan/OpenGLES/DirectX) is dependent on the user acceptance rate worldwide, so your application will be running on most of the devices for today and we will update GLAL when necessary.

After every update you can just add the new libraries directly to your project and delete the old one because even if a major change happens, we will design the API in such a way that nothing changes for you.

and also its open source !


The main idea is to make a common function out of every API's similar function and make an API so that you can write a single program and it should run everywhere with the proper executable, so no hassling around with other graphics API for hardware accelerated rendering,
use this one API and get the job done.
