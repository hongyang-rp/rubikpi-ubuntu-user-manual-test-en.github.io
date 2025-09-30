# Explore Sample Applications 

This section outlines a modular, hands-on approach to AI development using Qualcomm®-supported tools, runtimes, and frameworks.  
Whether you're training models, deploying pre-trained networks, or building multimodal AI workflows, this guide offers a modular, hands-on approach.  
The document covers:  
* Model creation with **Edge Impulse** and **Qualcomm® AI Hub**  
* Inference using **LiteRT, TensorFlow Lite, and ONNX Runtime**  
* Local execution of large language models with **Llama.cpp**  
* Workflow orchestration with **Genie**  
* Sample applications using **IMSDK** and robotics SDKs 

Each section is designed to be standalone, so you can jump directly into the tools and flows that match your project needs. The goal is to provide clear, reusable examples and practical insights for integrating AI into real-world edge applications.

## Application Development & Execution Flow Summary

|Flow               |Purpose                                                                                               |
|-------------------|------------------------------------------------------------------------------------------------------|
|[**Edge Impulse**](https://hongyang-rp.github.io/rubikpi-ubuntu-user-manual-test-en.github.io/docs/Document%20Home/Application%20Development%20and%20Execution%20Guide/Building%20AI%20Models/edge_impulse#train-an-ai-model)     |Build and train AI models using audio, image and other sensor data - or bringing your own model in a variety of formats.                       |
|[**Qualcomm® AI Hub**](https://hongyang-rp.github.io/rubikpi-ubuntu-user-manual-test-en.github.io/docs/Document%20Home/Application%20Development%20and%20Execution%20Guide/Building%20AI%20Models/qualcomm_ai_hub#finding-supported-models) |Qualcomm® AI Hub simplifies deploying AI models for vision, audio, and speech applications to edge devices. You can optimize, validate, and deploy your own AI models on hosted Qualcomm platform devices within minutes.|
|[**LiteRT/TFLite**](https://hongyang-rp.github.io/rubikpi-ubuntu-user-manual-test-en.github.io/docs/Document%20Home/Application%20Development%20and%20Execution%20Guide/Framework-Driven%20AI%20Sample%20Execution/litert_tflite#quantizing-models)    |LiteRT enables high-performance, on-device AI by running quantized models (Python or C++) on both CPU and NPU of Dragonwing devices using AI Engine Direct delegates—all with minimal setup.| 
|[**ONNX**](https://hongyang-rp.github.io/rubikpi-ubuntu-user-manual-test-en.github.io/docs/Document%20Home/Application%20Development%20and%20Execution%20Guide/Framework-Driven%20AI%20Sample%20Execution/onnx#onnxruntime-wheel-with-ai-engine-direct)             |ONNX enables cross-platform AI deployment by exporting models. On Dragonwing devices, ONNX Runtime with AI Engine Direct allows execution on the NPU for maximum performance.| 
|[**Llama.cpp**](https://hongyang-rp.github.io/rubikpi-ubuntu-user-manual-test-en.github.io/docs/Document%20Home/Application%20Development%20and%20Execution%20Guide/Framework-Driven%20AI%20Sample%20Execution/llama_cpp#builing-llamacpp)        | Execute large language models locally using a C++ backend optimized for CPUs and quantized formats.  |
|[**Qualcomm® Genie**](https://hongyang-rp.github.io/rubikpi-ubuntu-user-manual-test-en.github.io/docs/Document%20Home/Application%20Development%20and%20Execution%20Guide/Framework-Driven%20AI%20Sample%20Execution/genie#installing-ai-runtime-sdk---community-edition)             | Orchestrate AI microservices and multimodal workflows using Qualcomm’s generative AI runtime.        |