# mapify
Digital D&amp;D Battle Map with drawable terrain and movable tokens

# features
- Fast and lightweight
- Touchscreen support
  - Designed for laptop and tablet use
- Terrain drawing using a simple pen tool
- Tokens with names, HP, initiative, and effects
- Sidebar overview of tokens sorted by initiative
- Effects with durations (for effects with indefinite durations, just use 999 rounds)
  - Turns: Every time one presses "next turn", duration decreases by 1
  - Rounds: On **affected token's** next turn, duration decreases by 1
- Save and import exact map state

# behavior
- When not having selected the pen or erasing tool, you can move the map around freely.
- When having the pen or erasing tool selected, the map is locked.
- Pressing the pen or eraser button activates the tool, pressing the button again deactivates it.
- When wanting to switch from pen to eraser, you need not deactivate the pen to activate the eraser, you can press the eraser button directly and vice versa.
- Zoom using scrolling or pinching on a touchscreen.

# info
The touchscreen support has been tested on a Samsung Galaxy Tab S4 with an S Pen. In my testing, it has been important to select the drawing tools using a finger instead of the S Pen to avoid weird zooming and panning behavior. If you use your finger to select drawing tools, you should be fine drawing normally with your S Pen.
