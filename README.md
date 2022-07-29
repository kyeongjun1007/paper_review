# paper_review
### THOC
Dilated RNN과 hierarchical network를 결합한 deep timeseries anomaly detection model.   
   
### DTWNet
DTW layer를 추가한 neural network로 pretrained patterns(features)를 추출.   
### NeuralWarp
Time-series를 deep representation space에 표현하여 index context 정보를 반영시킨 뒤, context vector끼리 align하여 similarity 계산.   

### THOC
spatial correlation을 가지는 randomness based 3D data에 대해
데이터를 주변 값으로 모델링하여 residual을 계산하고 이에 대해 binarization 진행.
이 binarized matrix의 분포를 가정하고 이 pdf를 KL divergence로 유사도를 측정하는 방식.
data간의 KL divergence 값을 이용해 anomaly detection 진행.
