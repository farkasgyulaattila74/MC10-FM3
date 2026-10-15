# MC10-FM3

Custom firmware for the **PaintAudio MIDI Captain 10** (MC10), made to control a **Fractal Audio FM3**.

> Unofficial project. It is not made by, or affiliated with, PaintAudio or Fractal Audio Systems.

## What it is

A foot controller layout built for playing live, treating the MC10 like a small pedalboard:

- **Presets and scenes** on dedicated switches. The display and LEDs follow what the FM3 actually does (preset, scene, effect state).
- **Six dedicated "stomp-box" switches** for the effects you reach for most. Each switch has a short-press and a long-press function, so three switches control six effects.
- **Combos** (two switches at once) for amp and delay channel changes, looper on/off and looper mode.
- **Looper mode** with transport controls on their own switches. The LEDs and display follow the FM3 looper, whether you press on the pedal or on the FM3.
- The layout is fixed on purpose, so you can find a switch by feel without reading the display.

## What you need

- PaintAudio MIDI Captain 10
- Fractal FM3
- **Two** 5-pin MIDI cables: pedal OUT -> FM3 IN **and** FM3 OUT -> pedal IN. The pedal needs both directions to follow the FM3.
- USB cable to load the firmware

## Download

See **Releases** on the right: `FM3_MC10Std_C6.21.4.uf2`

Loading a `.uf2` works the same way as for PaintAudio's own firmware updates: follow PaintAudio's official update document, using this file.

## License

Free for personal, non-commercial use. You may not sell it, bundle it into a paid product, or use it to earn money.

Source code is not published. Support and collaboration are at my discretion.

Third-party components (such as the arduino-pico core) keep their own licenses.

## Feedback

Questions and bug reports: use **Issues** on this page.
