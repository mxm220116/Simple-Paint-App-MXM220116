# Simple Paint App: FunPad! (i might change that name...........)

## Repository
[https://github.com/mxm220116/simple-paint-app
](https://github.com/mxm220116/Simple-Paint-App-MXM220116)
## Description
My plan is to create a very lightweight and beginner-friendly desktop drawing application built in Python.
It would provide digital artists with essential tools like custom pens and color selectors, as well as other features like layer/canvas management (and potentially even an animation/video compilation feature).

## Features
- Multi-Layer Support
  - Each layer a user creates will be treated like a separate visual canvas. Their opacity and stack order can be customized at will.
- Custom Pen and Color Controls
  - Users would be granted a color picker as well as other helpful widgets to adjust brush color, size, and more!
- Engaging and Unique UI with Sound and Visual Effects
  - Navigating the UI and interacting with certain elements should also trigger some fun responses from the system, granting users a (hopefully) engaging experience.
- Export and Canvas Controls
  - This program enables creating custom canvas sizes and exporting any final composited images to an array of available formats (.png, .mp4, .jpg, etc!).

## Challenges
- Layer Management: Ensuring multi-layered drawings are available to users without delay or other forms of lag
- Dynamic UI and Audio Integration: Integrating interactive sound effects and visual feedback without interfering with canvas rendering performance
- Multi-Format File Export and Video Compilation: Handling compositing for .png/.jpg formats if compiling animations to video formats like .mp4
- Object-Oriented UI architecture: Keeping the canvas rendering, event handling, event triggers and layer handling separate (modular) to ensure everything works independently/properly

## Outcomes
Ideal Outcome:
- Ideally, I would like to create a fully-functional desktop drawing app with at least 3+ customizable layers (stacking order, opacity controls), brush size/color customization, interactive sound/visual UI feedback and an array of export options.

Minimal Viable Outcome:
- At the bare minimum, I will ensure I have a responsive 1 to 2-layer drawing canvas featuring basic brush/color tools and file exporting.

## Milestones
- Week 1
  1. Set up repository and framework with a basic drawing canvas AND event-driven mouse tracking to enable drawing.
  2. Implement multi-layer options and basic layer creation/stacking logic.
- Week 2
  1. Create brush customization controls (color picker, size sliders, eraser mode, etc) and layer opacity/reordering features.
  2. Integrate UI sound and visual feedback triggers for buttons and canvas actions.
- Week 3
  1. Have fully-functioning layer management UI (reordering, hiding, opacity adjustment, etc.) and allow multi-format exports.
  2. Implement any remaining stretch goals (potentially animation/video compilation) and perform any final UI/performance polishes.
