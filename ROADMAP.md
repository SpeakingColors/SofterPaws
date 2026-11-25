# Roadmap

1. Mockup: iterate on look and sound until approved.
2. C++ core from the mockup engine, with tests (bypass, latency, cut amounts, de-esser, auto gain).
3. JUCE VST3 with the editor ported natively from the approved mockup.
4. Installers for Linux, Windows and macOS in one zip with a PDF manual and an uninstaller.

Open questions:
- A true near zero latency mode needs a different design from the spectral engine; research first.
- Linear phase switch: the spectral cuts are already zero phase; decide if a switch is needed.
- More than stereo (surround) later.
