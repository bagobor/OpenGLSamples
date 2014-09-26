NVIDIA GameWorks OpenGL Graphics and Compute Samples
====================================================

The OpenGL Graphics and Compute Samples pack is a resource for cross-platform OpenGL 4 (GL4) and OpenGL ES 2 and 3 (ES2 and ES3) development, targeting Android, Windows, and Linux (x86/x64 and Linux for Tegra).  The samples run on all four target platforms from a single source base.

Advanced OpenGL features such as Tessellation Shaders, Geometry Shaders, Compute Shaders, Direct State Access, Texture Arrays and Instancing are all demonstrated.  In addition, support for NVIDIA's NSight Tegra Visual Studio plug-in means that developers can experiment with their effects on Windows OpenGL and immediately rebuild and retarget to run on Android Tegra systems, including Tegra K1. 

The samples also include source for a simple cross-platform application framework which forms the basis of all of the samples.  This framework supports GL window and context management, platform-independent main event loop, handling of input devices including game controllers, asset/file reading, texture/model loading, and other GL utilities.

What to Read Next:
------------------
* [Release Notes](http://docs.nvidia.com/gameworks/index.html#gameworkslibrary/graphicssamples/opengl_samples/gl_release.htm)
** What's new in this release, along with any known issues.
* [Prerequisites](http://docs.nvidia.com/gameworks/index.html#gameworkslibrary/graphicssamples/opengl_samples/gl_prereq.htm)
** Details the per-platform requirements for developing with the samples.
* [Setup Guide](http://docs.nvidia.com/gameworks/index.html#gameworkslibrary/graphicssamples/opengl_samples/gl_setup.htm)
** Details the per-platform steps needed to set up your PC for building and running the OpenGL samples.
* [Overview of OpenGL Samples](http://docs.nvidia.com/gameworks/index.html#gameworkslibrary/graphicssamples/opengl_samples/gl-samples.htm)
** Describes each of the samples in the pack, what they demonstrate, and in some cases further detailed analysis of how they work.
* [Overview of App Framework and Libraries](http://docs.nvidia.com/gameworks/index.html#gameworkslibrary/graphicssamples/opengl_samples/index-framework.htm)
** Details the cross-platform application framework and other support libraries, along with links to class/structure documentation.

Providing Pull Requests:
------------------------
NVIDIA is happy to review and consider pull requests for merging into the main tree of the samples for bug fixes and features. Before providing a pull request to NVIDIA, please note the following:
* A pull request provided to this repo by a developer constitutes permission from the developer for NVIDIA to merge the provided changes or any NVIDIA modified version of these changes to the repo. NVIDIA may remove or change the code at any time and in any way deemed appropriate.
* Not all pull requests can be or will be accepted. NVIDIA will close pull requests that it does not intend to merge.
* The modified files and any new files must include the unmodified NVIDIA copyright header seen at the top of all shipping files. 
