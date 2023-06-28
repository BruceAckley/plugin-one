# Plugin One

## How the project was bootstrapped
git clone https://github.com/juce-framework/JUCE
and copy the folders from "/examples/CMake/AudioPlugin" into a new directory

git submodule add https://github.com/juce-framework/JUCE

## Local development setup on Windows 10 with VSCode

Add the submodule `git submodule init --recursive`

Configure build dependencies

- MINGW32
- `winget install Microsoft.VisualStudio.2022.BuildTools`
- `winget install Kitware.CMake`

### Resources

- https://forums.cockos.com/showthread.php?t=250482
