# Intelligence_


인공지능 수업에서 

선형회귀 (Linear Regression Model) 

- dataset : sklearn.load_diaberes
- Model : From sklearn.linear_model import LinearRegression

  HW#02
  : BMI와 혈당에 대한 선형 회귀 문제를 numpy를 사용하여 풀이하시오.
    코랩으로 풀이하여, 링크를 업로드할 것.

[데이터 다운로드 코드]

import numpy as np
from sklearn import datasets
X, y = datasets.load_diabetes(return_X_y=True)
X_new = X[:, np.newaxis, 2]
