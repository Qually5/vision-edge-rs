# vision-edge-rs

**Real-time computer vision processing optimized for edge devices.**

## Features
- Zero-copy image processing with Rust
- Optimized for ARM and RISC-V architectures
- Built-in support for YOLOv8 and MobileNet
- Low memory footprint for embedded systems

## Build
```bash
cargo build --release
```

## Usage
```rust
use vision_edge::Detector;

fn main() {
    let detector = Detector::new("yolov8.onnx");
    detector.run();
}
```