# Visual Trainer Fixes v2.2.2

COLREG AI Trainer v2.2.2 improves the accuracy of the real-image Lights & Shapes trainer.

## Fixed Items

### Vessel Not Under Command — Not Making Way

Previous answer text was too general:

```text
Vessel not under command
```

Updated answer text:

```text
Vessel not under command, not making way
```

This is more accurate because the image shows only two all-round red lights and no sidelights or sternlight.

### Vessel at Anchor 50 m+

The previous anchor image could be confused with an underway sternlight.

The corrected image now shows:

* forward all-round white anchor light
* aft all-round white anchor light
* no sidelights
* no sternlight
* no wake
* vessel clearly at anchor

## Visual Training Principle

The image should not reveal the answer through text.
The learner should identify the vessel status from the lights and visual scene.

## Current Real Image Workflow

1. Generate original 3D image using COLREG 2018 reference.
2. Manually check navigation lights for accuracy.
3. Reject images with extra, missing, or incorrect lights.
4. Save accepted image into `media/images/lights/`.
5. Map the image to the correct visual card.
6. Web app displays PNG first.
7. SVG remains available as fallback.

## Status

Stable visual accuracy fix for v2.2 real-image trainer.
