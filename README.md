## Mods

- [UpdateChecker](#updatechecker)

## Building

To Build simply:

1. Set a `CVR_DIRECTORY` environment variable.
  - On Windows you can run `setx CVR_DIRECTORY "C:\[SomePath]\common\ChilloutVR"`

2. Clone repo using git
3. Open solution in an ide that supports C#
4. Build Solution/Specific Project


### ILRepack
A copy of [ILRepack.Lib.MSBuild.Task](https://github.com/ravibpatel/ILRepack.Lib.MSBuild.Task) and [ILRepack](https://github.com/gluck/il-repack) are included in the repo to build the solution

## UpdateChecker

- Simple mod for people who dislike auto updaters
- Checks for mod updates and lets you know in the console
- Only works for mods that follow the semver format

### Acknowledgements
Repo structure copied from [Knah's VRCMods Repo](https://github.com/knah/VRCMods/)
