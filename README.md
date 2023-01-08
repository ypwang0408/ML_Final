# ML_Final - Tabular Playground Series - Aug 2022
This is the repository of my ML Final work, it is a [kaggle prediction competition](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/overview). I get 0.59021 on the private score, which is higher than the baseline of 0.58990. The following is the way to reproduce my work. 
## Requirements
To install requirements:

```setup
pip install -r requirements.txt
```
## Training
To train the model, what you need to do is to change the path for data and simply run all. 

## Inference
To infer the result, you need to change the directory if you modify the outputs directory in train.ipynb and run all, you will get '109550008.csv' as my prediction. 

## Results
My model achieves a score of 0.59021 on the private score.  
![image](https://github.com/ypwang0408/ML_Final/blob/main/Score.png)

### Appendix
The ```bad works.ipynb``` is the method I tried, but they all get poor scores, most of the just get 0.5, and some of them are just predict all not failure since the training set is imbalanced.
