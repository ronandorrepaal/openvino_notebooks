# Introduction to Performance Tricks in OpenVINO™

These notebooks show tips on how to optimize inference in OpenVINO™.   

There are different performance targets for various use case scenarios. For example, video conferencing usually requires the latency to be as short as possible. While for high-resolution video/image analysis, high throughput is typically the performance target. As a result, different optimization tricks should be applied to achieve other performance targets.
In this notebook, we’ll show a set of performance tricks for optimizing inferencing latency. 

## Notebook Contents

1. [Performance tricks in OpenVINO for latency mode](latency-tricks.ipynb)

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/openvinotoolkit/openvino_notebooks/blob/latest/notebooks/performance-tricks/latency-tricks.ipynb)

This notebook demonstrates how to optimize the inference latency in OpenVINO™.  A set of optimization tricks, including model conversion with different data precision, “AUTO” device with latency mode, shared memory, inference with a further configuration, inference on GPU, etc., are introduced.

![](https://user-images.githubusercontent.com/4547501/229120774-01f4f972-424d-4280-8395-220dd432985a.png)

1. [Performance tricks in OpenVINO for throughput mode](throughput-tricks.ipynb)

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/openvinotoolkit/openvino_notebooks/blob/latest/notebooks/performance-tricks/throughput-tricks.ipynb)

This notebook demonstrates how to optimize the inference throughput in OpenVINO™.  A set of optimization tricks, including bigger batch size, “AUTO” device with throughput and cumulative throughput mode, asynchronous inference mode, etc., are introduced.

![](https://github.com/openvinotoolkit/openvino_notebooks/assets/4547501/ac17148c-bee9-43aa-87fc-ead61ac75f1d)

## Installation Instructions

This is a self-contained example that relies solely on its own code.</br>
We recommend running the notebook in a virtual environment. You only need a Jupyter server to start.
For details, please refer to [Installation Guide](../../README.md).
