# Mont programmatic tools

Client-neutral recorder definitions for Mont SDK hosts. Capture, permissions, finalization, and scene composition remain SDK-owned; CLI and editor clients adapt the same definitions.

- `recorders/camera-screen-cursor-recorder.mont`: screen, camera, microphone, and cursor capture.
- `recorders/screen-cursor-recorder.mont`: screen, microphone, and cursor capture.

Reproducible synthetic examples and rendered previews live in [usemont/workflows](https://github.com/usemont/workflows#tools). Examples pin these definitions by commit and SHA-256; they do not open capture devices.

[Apache-2.0](LICENSE)
