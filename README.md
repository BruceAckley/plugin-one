# Plugin One

## How the project was bootstrapped

Include JUCE as a submodule with 
`git clone https://github.com/juce-framework/JUCE`
and copy the folders from "/examples/CMake/AudioPlugin" into a new directory

Run 
`git submodule add https://github.com/juce-framework/JUCE`

## Local development setup on Windows 10 or 11 with VSCode

Add the submodule `git submodule init --recursive`

### Configure build dependencies

- MINGW32
- `winget install Microsoft.VisualStudio.2022.BuildTools`
- `winget install Kitware.CMake`

From there, it should be possible to access the builds using the VSCode CMake extension.

### Resources

- https://forums.cockos.com/showthread.php?t=250482
- https://www.youtube.com/@TheAudioProgrammer

## Summary

plugin-one is intended to create tasty cyberpunk synths out of input sounds. 
You can send audio to it, and it outputs glitchy madness. 
