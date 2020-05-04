# 298rl-project

Setting up Windows environment:

1. install Anaconda from the following link https://www.anaconda.com/downloads

2. install pytorch 1.3.0
```sh
pip install torch==1.3.0+cu92 -f https://download.pytorch.org/whl/torch_stable.html
```

3. install ptan, gym, numpy, tensorboard

```sh
pip install ptan gym numpy tensorboard
```

4. install pybullet

```sh
pip install pybullet
```

You might get an error 'error: Microsoft Visual C++ 14.0 is required. Get it with "Build Tools for Visual Studio"', in which case Visual Studio Build tools must be installed which can be downloaded from "https://visualstudio.microsoft.com/visual-cpp-build-tools/". Install the following packages...

![Visual Build Tools Packages](assets/vsbuildtools.PNG)

You may have to restart your machine to complete the installation.

