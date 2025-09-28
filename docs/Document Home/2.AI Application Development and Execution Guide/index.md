# Application Development and Execution Guide

This guide walks through the full lifecycle of AI development using Qualcomm-supported tools, runtimes, and frameworks.  
Whether you're training models, deploying pre-trained networks, or building multimodal AI workflows, this guide offers a modular, hands-on approach.  
The document covers:  
* Model creation with **Edge Impulse** and **Qualcomm AI Hub**  
* Inference using **LiteRT, TensorFlow Lite, and ONNX Runtime**  
* Local execution of large language models with **Llama.cpp**  
* Workflow orchestration with **Genie**  
* Sample applications using **IMSDK** and robotics SDKs 

Each section is designed to be standalone, so you can jump directly into the tools and flows that match your project needs. The goal is to provide clear, reusable examples and practical insights for integrating AI into real-world edge applications.

## 📊 AI Development & Execution Flow Summary

|Flow               |Purpose                                                                                               |Link         |
|-------------------|------------------------------------------------------------------------------------------------------|-------------|
|Edge Impulse       |Build and train AI models using audio, image and other sensor data - or bringing your own model in a variety of formats.                       |[Add Link]   |
| Qualcomm AI Hub   |Qualcomm® AI Hub simplifies deploying AI models for vision, audio, and speech applications to edge devices. You can optimize, validate, and deploy your own AI models on hosted Qualcomm platform devices within minutes.| [Add Link]  |
| LiteRT/TFLite     |LiteRT enables high-performance, on-device AI by running quantized models (Python or C++) on both CPU and NPU of Dragonwing devices using AI Engine Direct delegates—all with minimal setup.| [Add Link]  |
| ONNX              |ONNX enables cross-platform AI deployment by exporting models. On Dragonwing devices, ONNX Runtime with AI Engine Direct allows execution on the NPU for maximum performance.| [Add Link]  |
| Llama.cpp         | Execute large language models locally using a C++ backend optimized for CPUs and quantized formats.  | [Add Link]  |
| Genie             | Orchestrate AI microservices and multimodal workflows using Qualcomm’s generative AI runtime.        | [Add Link]  |