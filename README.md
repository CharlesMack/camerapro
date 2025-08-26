# camerapro

🎥 P.O.P.S. Cinema — Pro++ (Zebra Lo/Hi/Band, FC Legend, Preview-only Overlays)-Class Sidekick
Core Design Philosophy

Never miss the moment → Always-ready record trigger with offline-first caching to hot storage, warm JSON archive, or cold slices (USB).

Digital Preservation → Capture → Compress → Store locally (WebM / ProRes-like wrapper), then sync when/if online.

Professional Feel → Full-frame emulation in software with sensor-inspired modes, cinematic HUD, LUT pipeline, and ND simulation.

🔑 Software Features 

Full-Frame Capture Simulation

Software “sensor modes”:

8.6K (emulated upscale / AI-assisted)

6K native (device resolution)

2K high-fps (slow-mo offline mode)

Dual Base ISO → Dual Exposure Curves

Offline tone-mapping presets: Daylight 800 and Night 3200

Fast toggle for low-light vs high-contrast environments

16 Stops of Latitude

Extended dynamic range recording with HDR metadata baked into P.O.P.S. clips

Built-in ND Filters

UI slider simulating 0.3 → 2.4 ND density (brightness cut via shader filter)

Recording Formats

Local WebM / VP9 or offline ProRes-like wrappers

AppDrop MediaRecorder pipeline: direct bin saves for replay/archiving

Lens Mount Flexibility

Attach “virtual lens packs” (JSON definitions for field of view, distortion, anamorphic de-squeeze factors)

Extension Mode

“Compact HUD” detachable: works on phone-sized P.O.P.S. screens

Sensor-UI split for VR/AR headset or secondary display

🖥️ UI / HUD (like your uploaded display mockups)

Top Bar: Frame rate (FPS), resolution mode, ISO curve, ND filter slider

Center Overlay: Safe-frame guides (2.39:1, 16:9, 4:3 anamorphic)

Bottom Bar: Battery slice % | Storage bin used (Hot/Warm/Cold) | LUT selector

Record Button (red circle): Hooks directly into MediaRecorder → local save

Assistant Display: Simplified control panel (FPS, ISO, LUT, ND)

Operator Display: Full HUD with waveform, histogram, focus peaking toggle

⚡ Storage / Slices Integration

Hot (IndexedDB/localStorage): Instant buffer + replay bin

Warm (JSON archives): Clip logs + metadata (ISO, ND, LUT used)

Cold (USB / Offline Media): Exportable bundle .popsfilm.zip with video + metadata + LUTs
