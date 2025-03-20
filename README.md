ToDo:
- [ ] Option to link against static or dynamic MSVC runtime on Windows.
- [ ] Option to compile WebGPU ep with Vulkan backend under Windows.
- [ ] Add [`dxcompiler.dll`](https://github.com/alfatraining/ort-artifacts-staging/actions/runs/13452162958/job/37588407901#step:8:19204) and [`dxil.dll`](https://github.com/alfatraining/ort-artifacts-staging/actions/runs/13452162958/job/37588407901#step:8:19213) to the output archive for Windows builds with WebGPU ep.
- [ ] Debug builds.
- [ ] Builds for Android.
- [ ] Builds for iOS.
- [ ] Custom CMake build of Emscripten.
- [ ] Add NPU-based execution providers (QNN?, Intel OpenVINO?, ...)
- [ ] Remove unused setups? (training, Cuda, etc.)
- [ ] Rename project?

Changes from [pykeio/ort-artifacts](https://github.com/pykeio/ort-artifacts) should be reviewed and merged into this fork.
Currently, the latest commit until reviewed was [2793c2e](https://github.com/alfatraining/ort-artifacts-staging/tree/2793c2e33712de2f5c19435af438c95ceada8085).