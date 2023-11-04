# titanic
2020100401 최종수 이 프로젝트는 titanic dataset을 이용한 생존 예측 ml이다.

#test는 생략하였다.

사용된 라이브러리 및 도구 :import pandas as pd import numpy as np import matplotlib.pyplot as plt import seaborn as sns from sklearn.linear_model import LogisticRegression from sklearn.tree import DecisionTreeClassifier from sklearn.impute import SimpleImputer

#모델링에 필요한 라이브러리 #knn,decision,random forest, Naive Bayes, SVM 사용 from sklearn.neighbors import KNeighborsClassifier from sklearn.tree import DecisionTreeClassifier from sklearn.ensemble import RandomForestClassifier from sklearn.naive_bayes import GaussianNB from sklearn.svm import SVC

import numpy as np

from sklearn.model_selection import KFold from sklearn.model_selection import cross_val_score
