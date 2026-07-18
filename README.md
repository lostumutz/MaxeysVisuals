Overview
MV is designed for developers and enthusiasts requiring direct, low-overhead access to depth buffer data. By utilizing a DXGI proxy DLL, it bridges the gap between the game's rendering pipeline and external applications, enabling advanced shader injection and custom overlay capabilities without compromising system performance.

Core Features
DXGI Proxy Architecture: Wraps the swapchain for efficient, direct integration.

Depth Texture Streaming: Captures and exposes shared depth handles for real-time access.

Low-Latency Pipeline: Optimized for minimal CPU/GPU overhead during frame capture.

External Integration: Seamlessly feeds data to external processes for custom rendering overlays.
