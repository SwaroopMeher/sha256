# SHA-256 Binary Visualizer

Interactive step-by-step visualization of the SHA-256 hashing algorithm with binary representation.

## Usage

Open `sha256.html` in a web browser. Enter a message to see how SHA-256 processes it:

- **Preprocessing**: Padding and message preparation
- **Chunking**: Parsing into 512-bit blocks
- **Message Schedule (W)**: Extending W[0-15] to W[0-63]
- **Compression**: 64 rounds of compression with bitwise operations
- **Hash Update**: Final hash state calculation

## Controls

- Play/Pause to step through automatically
- Previous/Next to navigate manually
- Speed selector for playback rate
- Reset to start over

## Features

- Binary representation of all operations
- Sidebar showing hash state (H), message schedule (W), and constants (K)
- Color-coded bitwise operations
- Detailed formulas and calculations at each step

