# wanari
[![Matrix](https://img.shields.io/badge/User_Matrix-%23wgpu--users%3Amatrix.org-blueviolet.svg)](https://matrix.to/#/#wgpu-users:matrix.org)
[![Build Status](https://github.com/gfx-rs/wanari/workflows/pipeline/badge.svg)](https://github.com/gfx-rs/wanari/actions)

The new Khronos' ARNARI stands for "Analytic Rendering Interface". It aims to streamline data visualization development for any company creating scientific visualization rendering engines, libraries and applications. 

This project is attempting to sandwich ANARY with Rust on both sides:
  - `wanari-core` is the ANARI implementation based on [wgpu-rs](https://github.com/gfx-rs/wgpu-rs)
  - `wanari-rs` as a Rusty idiomatic frontend library to `wanari-core`
  - `wanari-native` is the C API backend to ANARI, based on `wanari-core`
