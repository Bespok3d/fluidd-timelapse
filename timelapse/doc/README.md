# Timelapse

Enables the Fluidd/Mainsail **timelapse** menu on stock Snapmaker firmware, which ships
Moonraker without the timelapse component.

## What it does

- Adds the Moonraker `timelapse` component and a `[timelapse]` config section, so the
  timelapse panel appears and works in Fluidd and Mainsail.

## Using it

Install the plugin, then configure timelapse from the Fluidd/Mainsail timelapse panel as
usual. A camera is required to capture frames (see **Camera HW Accel** and the
**webcam-builtin** plugin).

## Notes

- Restarts Moonraker on install.
- Pairs with **Force Timelapse** if you want a timelapse on every print regardless of the
  slicer setting.
