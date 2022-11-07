Thanks for your interests!

__Efficient-Edge-AI__ is a toolkit to help deep learning engineers/researchers to _train/optimize/deploy/test_ their pre-trained Pytorch/TensorFlow models with advanced inference engines (TensorRT, ONNX, TorchScript) on Nvidia Triton server automatically. Specifically, we provide some bash scripts to _train/optimize/deploy/test_ your models in fewer lines of code in a docker container. Thus, there is no need to worry dependency related issues. 😆

![arch](https://github.com/efficient-edge/.github/blob/master/media/architecture.png)

#<div align=center><img src="https://github.com/efficient-edge/.github/blob/master/media/architecture.png"></div>

> Notice: Because TensorFlow models have multiple issues about version conflict on Triton, we first convert them to TensorRT formats and execute on Triton. For Pytorch models, you can select any inference engines. To help you find the most suitable inference engine, we also provide the benchmark script to evaluate their performance using different engines.
