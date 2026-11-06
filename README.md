# arm64 emulator verification for voice-forward (Nuke)

Run `Actions -> arm64-emulator-verify -> Run workflow`. The job boots a native
ARM64 Android emulator (android-34 google_apis arm64-v8a), patches the latest
WeChat (8.0.80 arm64) with LSPatch + Nuke, installs it, launches it, waits for
QR login, and uploads logs + screenshots as artifacts.
