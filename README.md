# Bmad's Dirty Undo-Redo for [ComfyUI](https://github.com/comfyanonymous/ComfyUI)  

ComfyUI extension that adds undo (and redo) functionality.

Undo: <kbd>Ctrl</kbd>/<kbd>⌘</kbd> + <kbd>Z</kbd> 

Redo: <kbd>Ctrl</kbd>/<kbd>⌘</kbd> + <kbd>Y</kbd> ; or <kbd>Ctrl</kbd>/<kbd>⌘</kbd> + <kbd>Shift</kbd> + <kbd>Z</kbd>

Keeping the keys pressed will repeat the undo/redo operation at an ever-increased pace.

## Installation:

- Navigate to `/ComfyUI/custom_nodes/` folder;
- `git clone https://github.com/bmad4ever/ComfyUI-Bmad-DirtyUndoRedo`.

### Why "dirty"?

I was mainly concerned with getting a somewhat working solution quickly and not so much with implementing it "right". For example, the undo/redo data contains snapshots of the entire serialized workflow (this is overkill), and I'm not considering changing it.

