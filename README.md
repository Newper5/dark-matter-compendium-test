# Dark Matter Compendium
A module for [Foundry VTT](https://foundryvtt.com/) that adds content specific
to the [Dark Matter](https://darkmatter.magehandpress.com/) setting created by
[Mage Hand Press](https://store.magehandpress.com/).

## Contributing

You should be familiar with
[this process](https://foundryvtt.com/article/compendium/). Adding new content
to this compendium requires that you be a little familiar with git, with
copying files on the system where Foundry VTT is running, and with Foundry VTT
itself. You will also need a GitLab account. Bonus points if you are familiar
with [git lfs](https://docs.gitlab.com/ee/topics/git/lfs/).

### Setting Up
1. Clone this repository. You will be creating branches, pushing them, and
  opening merge requests.
2. Install the module into Foundry VTT where you are creating content.

### Creating Content
1. Create items, actors, scenes, etc.
2. Make sure the art you use is added to the images subdirectory of the module
  filesystem.
3. Unlock the corresponding compendium. There will be warnings.
4. Drag and drop your content to the compendium.

### Submitting The New Content
1. Create a new branch in the clone of this project.
2. Copy your module db files into the clone of this project.
3. Make sure any new artwork or audio files are also copied to the
  corresponding location in this project.
4. Add, commit, and push your changes.
5. Open a merge request in the GitLab web interface and assign it to someone.

## Dependencies

* This module uses the [Dark Matter System Extensions](https://gitlab.com/csmcfarland/dme)
* (Optional) The [game-icons.net](https://github.com/datdamnzotz/icons/blob/master/README-FoundryVTT.md)
  module adds 3800 icons at {User}/modules/game-icons-net. I find the "whitetransparent"
  icons look the best, but YMMV. (Added by @Android8675#9424)
