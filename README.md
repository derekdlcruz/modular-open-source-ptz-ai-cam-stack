# Modular Open Source PTZ AI Camera Stack (HW, SW and Cloud Services)

## Components
- Modular PTZ Camera HW in a variety of form factors for a variety of use cases
- Embedded SW to encode and stream video and control interfaces (e.g. PTZ)
- Embedded SW to run AI models for various use cases (e.g. object detection, tracking)
- Cloud services to provision, manage and interact with fleets of cameras

## Software Backend + Dashboard

Repository:
https://github.com/brandonle2016/ptz-ai-camera-dashboard

Features:
- CSI camera ingest via GStreamer
- YOLO object detection + tracking
- H.264/WebRTC streaming
- PTZ control APIs
- Metrics + telemetry
