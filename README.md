# Titanic Dataset 분석

## 필요 모듈
```python
pip install numpy
pip install pandas
pip install seaborn
pip install missingno
pip install plotly
pip install matplotlib
```

## 목차
1. 데이터 불러오기
2. 데이터 살펴보기
   * 2-1. 범주형 특징
   * 2-2. 수치형 특징
3. 데이터 분석
   * 3-1. 각 특징별 생존자 비율
   * 3-2. Embarked
   * 3-3. Pclass - Age / Sex - Age
   * 3-4. Age - Fare
4. 전처리
   * 4-1. 이상치 검출
   * 4-2. 결측치 처리
5. 상관관계 분석
6. 특징 조합
7. Modeling

## 참고
* [kaggle-DataiTeam Titanic EDA](https://www.kaggle.com/code/kanncaa1/dataiteam-titanic-eda)
* [kaggle-🚀Spaceship Titanic -📊EDA + 27 different models📈](https://www.kaggle.com/code/odins0n/spaceship-titanic-eda-27-different-models)
* [kaggle-A Statistical Analysis & ML workflow of Titanic](https://www.kaggle.com/code/masumrumi/a-statistical-analysis-ml-workflow-of-titanic)
* [wikidocs-Plotly Tutorial](https://wikidocs.net/185374)
* [블로그-outlier detection(이상값 탐지) 구현](https://velog.io/@choonsik_mom/outlier-detection%EC%9D%B4%EC%83%81%EA%B0%92-%ED%83%90%EC%A7%80-%EA%B5%AC%ED%98%84)
* [블로그-파이썬 데이터 이상치 제거 방](https://bigdaheta.tistory.com/82)
* [블로그-신뢰구간추정](https://kongdols-room.tistory.com/152)
* [wikipedia-RMS 타이타닉](https://ko.wikipedia.org/wiki/RMS_%ED%83%80%EC%9D%B4%ED%83%80%EB%8B%89)
