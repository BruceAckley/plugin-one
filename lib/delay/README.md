# Randomized Delay

The randomized delay module provides advanced delay modification for an audio stream.

## Road Map

1. **Idea**
The core concept of this code is a randomized delay. Additional features include:
- control parameters
    - Delay Time: This is the main parameter that determines how long it takes for the delayed signal to play back after the original signal
        - min
        - max
    - Feedback: This determines how many times the delayed signal is played back
        - min
        - max
    - Modulators: LFOs (Low Frequency Oscillators) that can modulate various parameters of the delay
    - Randomization Amount: determines how much randomness is applied to the delay time and feedback
    - Mix: blends the dry, unaffected signal with the wet, affected signal
- presets: presented in a dropdown to demonstrate possible configurations, from subtle to extreme
- visualizer: for MVP, start with a scatter plot that shows randomness of delay time and feedback

Here are links to designs:
- TODO: Add Figma designs and links
Including:
- Waveform Scatter Plot Visualizer: displays a waveform by default, but reveals a scatter plot when the user clicks or hovers over it. 
- Randomness sliders
- Mix and randomization knobs
- Presets dropdown
- Vibration lab for modulators
- Color scheme and typography
    - blue for delay stuff, purple for randomization stuff
    - clean, futuristic typeface

2. **Research**
Existing plugins that provide similar functionality include:
- TODO: Enumerate their strengths and weaknesses
The math behind delay:
- TODO: Add the math here for randomized or modulated delays

3. **Design**
User Interface (UI) Notes:
- TODO: Notes about the UI design
Algorithms used:
- Randomization: TODO: Add algos here
Plugin formats supported:
- VST3
- AU
Additional design elements:
- Buy me a coffee button

4. **Prototyping**
Start with a delay, no randomization.
Add placeholder elements for the UI.

5. **Test**
Add automated testing and CI/CD using GitHub actions.
Add contributing.md. Add log delivery mechanism.

6. **Iterate**
The meat of the development phase - improve implementation of the algos and visualizer.
Practice iterative development by making small, manageable changes and then testing to ensure they work as expected.

7. **Beta Testing**
Pick beta testing group and deliver the plugin to them. Create a template for delivering feedback and reporting bugs.

8. **Release**
Compile to all sources and release on a marketplace.
TODO: Create an app store to release and also add to other marketplaces.

9. **Promotion**
Promote the plugin locally and through the Internet.

10. **Post-Release Support and Development**
Create a support plan for the plugin and triage issues that are reported.
