# StrokeNet  
Check out this work, neural renderer + RL works better
https://github.com/hzwer/SARA_DDPG

A neural network that learns to draw digits by strokes  
The environment relies on node.js and puppeteer  
Needs tweaking to get it work  
MNIST (left MNIST sample, middle generator output, right Draw Web App reconstruction)  
![avatar](https://github.com/vexilligera/strokenet/blob/master/figures/mnist_result.png?raw=true)  
Omniglot  
![avatar](https://github.com/vexilligera/strokenet/blob/master/figures/omniglot_result.png?raw=true)  


## Dataset preparing for StrokeGenerator

For making dataset you should create directory:

```bash
mkdir enviroment/threebody
``` 

install `nodejs`, `npm` and required packages:
```bash
sudo apt install nodejs npm
npm install koa
npm install koa-views
npm install koa-json
npm install koa-onerror
npm install koa-bodyparser
npm install koa-logger
npm install puppeteer
npm install koa-router
npm install koa-static
``` 

After that, you can run `threebody.py` in enviroment directory: 

```bash
cd enviroment
python3 threebody.py
```
OR download exist dataset from:  

```
https://disk.yandex.ru/d/7Dd8b12gCH1KpA
```

Now you can run training.
