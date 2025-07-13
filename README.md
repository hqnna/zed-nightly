# Nightly Zed Builds

This repository automatically builds the latest commit of the
[Zed](https://github.com/zed-industries/zed) text editor for Windows.

- [deevus](https://github.com/deevus) made the original repository to build nightly versions.
- [someone120](https://github.com/someone120) created the patch to fix LSPs starting on windows.
- [lilnasy](https://github.com/lilnasy) made the original version of this workflow repository.

There are some key differences in this repository compared to the others that I should note:

- The **OpenGL** build is disabled here due to it failing to compile on nightly releases.
- The **Vulkan** build is the only one that I support using via my repository builds.
- The **LSP patch** is automatically applied to each nightly build of the binaries.

If you have any issues with Zed itself, make an issue upstream, not on this.

Lastly, thanks to [Zed](https://github.com/zed-industries/zed) for making everything
open source.
