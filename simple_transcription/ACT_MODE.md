# ACT MODE - Implementation Plan

## Task: Auto-start batch transcription on GUI launch

### Plan:
- [x] Modify `gui.py` to auto-start batch transcription on launch when:
  - [x] API key is configured
  - [x] There are pending files in the audio folder
- [x] Add auto-start logic in `__init__` after API key is loaded and UI is built
- [x] Add a small delay or check to ensure UI is ready before starting
- [x] Test the implementation
