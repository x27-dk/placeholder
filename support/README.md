# OTTO iOS Support (Current Prototype State)

This page describes the current state of `otto-ios`. The app is a SwiftUI prototype with local, on-device chat. Users can be created locally, messages are stored on device, and voice memos can be recorded and played back on the same device. The app currently supports reactions, message editing/deleting, search, and simple delivery/read states in the local data model. There is no production backend integration, no cloud sync, and no cross-device account system in active use. Push notification entitlement exists in development configuration only.

## Known Scope and Limitations

- Local data storage in app documents (`users.json`, `messages.json`, and voice memo files)
- Prototype behavior may change between builds
- No guaranteed data portability between builds
- No guaranteed backwards compatibility for local data

## Troubleshooting (Prototype)

1. If the app behaves unexpectedly, force close and relaunch.
2. If local data seems inconsistent, use the in-app clear data options and recreate test users.
3. If voice memo playback fails, verify microphone permission is granted and record again.
4. For install/build issues in development, use the latest uploaded build and matching provisioning setup.

## Reporting Issues

Include the following in bug reports:

- Device model
- iOS version
- App build/version
- Steps to reproduce
- Expected result vs actual result
- Screenshot or screen recording (if possible)

## Contact

For prototype support inquiries, contact: ci-builder@garbus.dk.
