# Release Notes - 2.0.0 (2025-12-31)

![iCraft Editor](https://raw.githubusercontent.com/gantFDT/icraft/main/public/images/banner.jpg)

## Editor
### New Features
- Added model self-animation support so models can play continuously in Layout Editing mode and be sequenced in Animation Editing mode.
- Added Mermaid sequence diagram support; users can add sequence diagrams in Layout Editing mode using Mermaid syntax.
- Automatically generate animation timelines for Mermaid sequence diagrams; the system creates corresponding animation plans based on the sequence diagrams users add.

### Improvements
- Prism-type elements now support configuring the number of sides.

### Bug Fixes
- Fixed an issue where the camera view could not rotate under a perspective camera when the Bloom post-processing effect was enabled.
- Fixed an issue where values in slider input fields in the Properties panel occasionally jumped unexpectedly after editing.
- Fixed an issue where editor configuration occasionally failed to load.
