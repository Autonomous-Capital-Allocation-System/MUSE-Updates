# MUSE release notes

## 1.0.0 (2026-10-18)

First ACAS Tools release (follows 5.1.2; the version number restarts at 1.0.0). Code-signed installers (Windows Authenticode; macOS Developer ID + notarized), updates that download and install from inside the plug-in, a free trial with no time limit (export, drag-out and preset saving need a license), and a new 1.0 user guide. Download: https://github.com/Autonomous-Capital-Allocation-System/MUSE-Updates/releases/tag/v1.0.0

## 5.1.2

- Grid now starts enabled in both the main generator and Workspace.
- Added a Workspace Grid toggle and made track generation honor its state.
- Renamed Scene A-D to Clip A-D and Rhythm / Riff to Rhythm.
- Removed stray encoding artifacts from saved-bank labels and interface text.
- Replaced orange Workspace accents with colors aligned to the MUSE palette.
- Restored distinct Block, Stab, Gate, Triplet, Dotted, Arp, and Pulse behavior,
  including meaningful Rate changes.
- Restored chord stacks and control-driven compact generation after the v5.1.0
  Phase A integration.
- Repaired the Windows VST3 package and automated Windows installer creation.

## 5.1.1

- Restored the compact generator's chord, rhythm, and control behavior.
- Repaired VST3 packaging and live MIDI output regression.

## 5.1.0

- Added Phase A musical generation with repetition, contour, rests, cadence,
  Surprise, and deterministic seeds.
- Added Rhythm, Contour, Harmony, and Groove variation locks.
- Added dedicated Melody and Rhythm generation in Workspace.

## 5.0.2

- Integrated Workspace into the existing plug-in window with Main/Workspace
  switching and no detached window.
- Stopping the DAW transport now stops MUSE preview.
- Raised Bass MIDI export by one octave while leaving Sub unchanged.

## 5.0.1

- Added four clips with four routed tracks: Melody, Rhythm, Bass, and Pad.
- Added per-track routing and shaping, mute/solo, piano-roll editing, generation,
  duplication, playback, drag, and export.
