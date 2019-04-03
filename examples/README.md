## PlotOptiX examples

### Basic plot making

Collection of short and simple scripts to get started.

Most of the scripts is using Tkinter UI, so here is a summary of mouse and keys actions:
- rotate camera eye around the target: hold and drag left mouse button
- rotate camera target around the eye: hold and drag right mouse button
- zoom out/in (change camera field of view): hold shift + left mouse button and drag up/down
- move camera eye backward/forward: hold shift + right mouse button and drag up/down
- change focus distance in "depth of field" cameras: hold ctrl + left mouse button and drag up/down
- change aperture radius in "depth of field" cameras: hold ctrl + right mouse button and drag up/down
- focus at an object: hold ctrl + double-click left mouse button
- select an object: double-click left mouse button (info on terminal output)

### Animations and callbacks

Callbacks in PlotOptiX are available in many points of the raytracing process. You can provide functions that will be executed on each frame raytracing start, completion, etc., allowing for image updates, saving output to file or making animated plots. Callbacks designed for heavy compute are executed in parallel to the raytracing. That is a really powerfull pattern!

*Progressing...*