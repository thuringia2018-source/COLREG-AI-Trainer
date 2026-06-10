# Real Image Assets v2.1.2

COLREG AI Trainer v2.1.2 introduces working real 3D image assets inside the web prototype.

## Purpose

The goal is to replace early SVG placeholder images with professional 3D-style maritime illustrations for COLREG lights and shapes training.

## Image Location

```text
media/images/lights/
| File                     | Training Use                                          |
| ------------------------ | ----------------------------------------------------- |
| `nuc_making_way.png`     | Vessel not under command, making way                  |
| `nuc_not_making_way.png` | Vessel not under command, not making way              |
| `ram_making_way.png`     | Vessel restricted in ability to manoeuvre, making way |
| `cbd_50m_plus.png`       | Vessel constrained by draught, 50 m+                  |
| `pdv_50m_plus.png`       | Power-driven vessel, 50 m+                            |

Image Workflow
Create original 3D image using COLREG 2018 reference.
Manually check navigation lights for accuracy.
Reject any image with extra, missing, or incorrect lights.
Save accepted image into media/images/lights/.
Map image to the correct visual card.
Web app displays PNG image first.
SVG remains available as fallback.
Design Requirements

Images should be:

original project assets
realistic 3D maritime style
night-time training illustrations
clean and uncluttered
focused on correct navigation lights
free from text labels, logos, watermarks, and extra lights
Important Rule

Do not use copyrighted images from books, PDFs, websites, apps, or screenshots.

All commercial image assets should be original.