# Description

Scripted toold for Adobe After Effects


## KMarkRetime

Full featured scripted plugin that makes re-timing layers in AE a breeze.

It uses layer markers with speed values to create all kind of speed ramps for you.

Other features:

- Change marker colors
- Shift markers across layers
- Copy markers to other layers
- Change multiple layers time blending
- Select/disable time remapped layers in bulk

<img src="https://github.com/user-attachments/assets/30354828-fc62-47ba-9664-d557a669b72a" alt="Docable Interface" width="400">

To install put the compiled KMarkRetime.jsxbin file into `C:\Program Files\Adobe\Adobe After Effects 2025\Support Files\Scripts\ScriptUI Panels` folder to be able to dock it into AE's interface like any other plugin. Restart After Effects.


## LayerMarkIT.jsx

Creates compostition markers for each layer in current selection. You can specify handles (before and after) to the lengths


## LayerNullIT.jsx

Creates nulls for each of currently selected layers at their positions (also copying the rotation and scale)


## LayerQueueIT.jsx

This script enqueues/renders all of the current composition's areas where the selected layers present. It gives the names of the layers to the output files and adds handles (in seconds, before and after the layers ins/outs) 


## MarkerQueueIT.jsx

This script enqueues/renders all of the current composition's marker areas


## SubNudgeIT.jsx

Subframe layer nudge. Move it back and forth at a fraction of the frame length


# Usage

Use them however you want. Run with the Script menu or add them as snippets to KBar or similar extension
