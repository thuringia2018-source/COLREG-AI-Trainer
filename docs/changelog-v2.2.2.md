# Changelog v2.2.2

## COLREG AI Trainer v2.2.2 — Visual Trainer Fixes

This version stabilizes the expanded real-image Lights & Shapes trainer.

## Main Improvements

* Improved visual quiz answer text for NUC not making way
* Changed answer from generic “Vessel not under command” to more precise “Vessel not under command, not making way”
* Replaced the incorrect vessel-at-anchor image with the corrected 50 m+ anchor image
* Improved visual training clarity
* Preserved larger image-first quiz layout from v2.2.1
* Preserved PNG-first image loading with SVG fallback

## Confirmed Working Fixes

* `nuc_not_making_way.png` displays correctly
* NUC not making way answer text is now precise
* `anchor_50m_plus.png` displays the corrected anchor image
* Vessel at anchor answer text is now more specific
* Lights & Shapes trainer works correctly with real 3D images

## Status

Stable expanded real-image visual trainer preview.

This version improves the accuracy and usability of the web-based Lights & Shapes recognition trainer.
