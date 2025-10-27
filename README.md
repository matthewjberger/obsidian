# Obsidian

Rendering gltf models with Vulkan and Rust

![Dragonglass Scene](/screenshots/screencap.gif?raw=true "Dragonglass rendered scene")

## Running

```
# bash
RUST_LOG=dragonglass cargo run > logfile 2>&1

# fish
env RUST_LOG=dragonglass cargo run > logfile 2>&1

# powershell
$env:RUST_LOG="dragonglass"; cargo run
```

