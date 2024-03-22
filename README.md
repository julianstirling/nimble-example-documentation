# Nimble example docs

This is an example of documentation for a specific Nimble configuration. This is being used to plan the documentation in the new [Nimble Smart docs](https://github.com/Wakoma/nimble/pull/23) and to plan and test functionality for [GitBuilding](https://gitbuilding.io).

### Why is this a separate repo?

GitBuilding is designed so that your documentation can sit in the same repository as the hardware project itself. One problem with keeping documentation in the main repository is that the history of photos and STL files can create a huge repository that is hard to clone.

Smart Docs will get around this by generating assembly images and STL files from source code for each configuration. While we plan how the documentation looks we had two options:

1. Use a lot of complex [Git LFS](https://git-lfs.com/) settings
1. Make the example docs in a separate repo

We chose option two!
