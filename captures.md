# Capture settings

All report screenshots are unmodified 1600 x 1200 PNGs saved with the renderer's S key. The application window used 800 x 600 logical pixels on a Retina display. The inspector coordinates below are framebuffer pixels, measured from the top left. The report's extra Task 2 detail panels crop the same PNG in CSS.

| Files | Scene | View | Samples | Pixel / level | Inspector |
| --- | --- | --- | --- | --- | --- |
| task2-{1,4,16}.png | basic/test4.svg | Default | 1, 4, 16 | Nearest / zero | (480,568) |
| task3-robot.png | my_robot.svg | Default | 16 | Nearest / zero | Off |
| task4-wheel.png | basic/test7.svg | Default | 1 | Nearest / zero | Off |
| task4-rgb.png | barycentric.svg | Default | 1 | Nearest / zero | Off |
| task5-*.png | texmap/test5.svg | Default, then four Page Up presses (2.44140625x magnification) | 1, 16 | Nearest or bilinear / zero | (800,600) |
| task6-*.png | mipmap.svg | Default | 1 | As named in each file | (1088,488) |

Keyboard inspector controls added to the viewer: Home centers the inspector; arrow keys move it by 32 framebuffer pixels (Shift: 1 pixel). Page Up/Page Down zoom about the view center by reciprocal factors of 0.8 and 1.25. Z toggles the inspector; Space resets the view. These controls are for repeatable captures; no extra credit is claimed.

Task 6 uses `assets/apple-logo.png`, the supplied 348 x 348 PNG, unchanged (including its baked-in checkerboard). The four captures share the same view and inspector position.

Additional Task 5 edge comparison: `task5-edge-{nearest,bilinear}-{1,16}.png` uses test5.svg at the same 2.44140625x zoom, level zero, inspector (800,388). All four originals were saved with S. `task5-edge-comparison.png` is a labeled montage of the inspector regions cropped from those originals for comparison.
