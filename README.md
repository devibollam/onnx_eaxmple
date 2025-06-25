# onnx_example
This project demonstrates:
Creating a simple PyTorch model.
Exporting it to ONNX.
Running inference with ONNX Runtime.
Benchmarking PyTorch vs ONNX Runtime inference speeds.

# Architecture Diagram
PyTorch Model --> Export --> ONNX Model (.onnx) --> Inference --> ONNX Runtime

# Why ONNX?
Enables model portability across platforms
Enables hardware-optimized inference via ONNX Runtime
Supports deployment to mobile, edge, and cloud environments
