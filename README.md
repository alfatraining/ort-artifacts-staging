ToDo:
- Build OpenVINO ep.
- Check whether macOS target can go back to macOS 10.15 if CoreML ep is disabled, otherwise should be macOS 13: <https://github.com/alfatraining/ort-artifacts-staging/actions/runs/13970358468/job/39110311692#step:7:4404>
- Option to compile WebGPU ep with Vulkan backend under Windows.
- Debug builds.
- Builds for Android.
- Builds for iOS.
- Custom CMake build of Emscripten.
- Add NPU-based execution providers (QNN?, Intel OpenVINO?, ...)
- Rename project?

Changes from [pykeio/ort-artifacts](https://github.com/pykeio/ort-artifacts) should be reviewed and merged into this fork.
Currently, the latest commit until reviewed was [2793c2e](https://github.com/alfatraining/ort-artifacts-staging/tree/2793c2e33712de2f5c19435af438c95ceada8085).
