# Air-quality-prediction
We propose to continuously predict the whole $station \times feature$ map in the next 1 to 48 hours with a non-stationary convolutional LSTM ( long short-term memory), which replaces the fully connected network in the classical LSTM with detrending and convolutional operations.

### Prediction on consecutive four frames

![Visualization of the one $station \times feature$ frame predicted by the seq2seq model (left) vs the ground truth (right).](https://github.com/bruce803/Air-quality-prediction/blob/master/figs/0.PNG)

![Visualization of the one $station \times feature$ frame predicted by the seq2seq model (left) vs the ground truth (right).](https://github.com/bruce803/Air-quality-prediction/blob/master/figs/1.PNG)

![Visualization of the one $station \times feature$ frame predicted by the seq2seq model (left) vs the ground truth (right).](https://github.com/bruce803/Air-quality-prediction/blob/master/figs/2.PNG)

![Visualization of the one $station \times feature$ frame predicted by the seq2seq model (left) vs the ground truth (right).](https://github.com/bruce803/Air-quality-prediction/blob/master/figs/3.PNG)

## Baseline 
### Prediction for seven cities of China, the Beijing, Shanghai, Chengdu, Wwuhan, Gguangzhou, Xi'an, and Nanjing.
![Visualization of the one $station \times feature$ frame predicted by the seq2seq model (left) vs the ground truth (right).](https://github.com/bruce803/Air-quality-prediction/blob/master/figs/predict-map-7city.png)
