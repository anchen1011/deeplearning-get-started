# Deeplearning Get Started
A concrete get started for deep learning in Vthree.AI (Chinese required)

## Prerequisite
Python2.7: http://www.runoob.com/python/python-tutorial.html

Python3.6: http://www.runoob.com/python3/python3-tutorial.html

Git: http://www.runoob.com/git/git-tutorial.html

.gitignore: https://git-scm.com/docs/gitignore

unix: http://linuxcommand.org/lc3_learning_the_shell.php

## Documentation
Official Doc: https://mxnet.apache.org

Best Practice: https://mxnet.incubator.apache.org/faq/security.html

CheatSheet: https://github.com/anchen1011/Awesome-MXNet/blob/master/apache-mxnet-cheat.pdf

## Very Good Tutorials
Web Tutorial: https://zh.gluon.ai/index.html

Video Tutorial: https://www.youtube.com/channel/UCjeLwTKPMlDt2segkZzw2ZQ

## 1. Install MXNet
http://mxnet.incubator.apache.org/install/

## 2. Get Started with an Example
http://mxnet.incubator.apache.org/test/tutorials/python/mnist.html

## 3. Hands-on
https://github.com/opringle/multivariate_time_series_forecasting

## 4. Math
Basics: https://zh.gluon.ai/chapter_appendix/math.html

Applied: https://github.com/zackchase/mxnet-the-straight-dope/blob/7a00d1ec253129d844055870d59266a8a502f5c4/chapter06_optimization/gd-sgd.ipynb

## 5. Actually Learn to Build Something
https://blog.csdn.net/u012436149/article/details/78047278

## 6.1 Focused Topics
NLP-toolbox: http://gluon-nlp.mxnet.io

NLP-tutorial: https://zh.gluon.ai/chapter_natural-language-processing/index.html

CV-toolbox: https://gluon-cv.mxnet.io

NLP-toolbox: https://zh.gluon.ai/chapter_computer-vision/index.html

## 6.2 Vthree.AI Specific Topics
CNN: https://zh.gluon.ai/chapter_computer-vision/bounding-box.html

LSTM: https://zh.gluon.ai/chapter_recurrent-neural-networks/lstm.html

## 7. Deliverables Guidelines
### Training Procedure (optional)
Clear execution flow (example: https://github.com/opringle/multivariate_time_series_forecasting)

### Inference Procedure 
Clear handler, where input format is clearly defined. Should be runnable with:
```
>>> from inference_module import handler
>>> handler(input, context=None)
```

### Dependency
Document all dependencies with version information (example: mxnet==0.12.3)

### Environment
Document the environment information including machine image/AMI information
