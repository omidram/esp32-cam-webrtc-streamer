# ESP32-CAM WebRTC Streaming

This project demonstrates how to capture video from an **ESP32-CAM**, send the video frames to a **server**, and then broadcast the video using **WebRTC**. It is ideal for real-time video streaming applications where you want to securely stream video without relying on third-party services.

## 🛠 Key Features
- **ESP32-CAM** captures video in MJPEG or H.264 format.
- **Server** handles incoming video frames from the ESP32-CAM and broadcasts them using WebRTC.
- **WebRTC** enables real-time peer-to-peer video streaming.
- **Real-time communication** with minimal latency.

## 🌐 Architecture Overview

![Architecture Diagram](https://img.shields.io/badge/Diagram-Available-blue?style=flat)  
The system architecture involves:
- **ESP32-CAM** capturing video frames and sending them to the server.
- The server handling the WebRTC connection and broadcasting video streams to a client (web browser).
- Real-time video communication enabled by **WebRTC**.
  
  ---
## System Workflow:
```mermaid
graph LR
  A[ESP32-CAM] -->|Capture Frames| B[Server]
  B -->|Process & Broadcast| C[WebRTC Client]
  C -->|View Stream| D[Browser/Client]
```
## 📝 Project Layout

