---
title: ✅ 달러인덱스와 환율의 상관계수 및 그래프 그리기
summary: 달러인덱스와 환율 간 상관계수를 구하고, 그래프를 그리는 과정을 소개합니다.
date: 2023-10-03
authors:
  - admin
tags:
  - Pandas
  - Data Analysis
  - Python
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'  
---

달러인덱스와 환율 간 상관계수를 구하고, 그래프를 그리는 과정을 소개합니다.

## 데이터 전처리

이 데이터셋은 달러인덱스와 환율의 일별 데이터를 기반으로 합니다.  
이상치를 제거하기 위해 각 항목의 전일대비 변동률을 구하고, 박스플롯을 사용해 이상치를 처리합니다.



# 데이터 읽어오기
dollar_index = pd.read_csv("달러인덱스.csv")  
krw_dollar = pd.read_csv("환율.csv")

# 전일대비 변동률 계산 후 이상치 제거
entire = pd.merge(dollar_index, krw_dollar, how="inner")  
entire.dropna(inplace=True)
```  
</code>  
</pre>  
</div>  

## 상관계수 계산

두 데이터 간의 상관계수를 피어슨 방법을 통해 계산합니다.

```python  
corr = entire.corr(method="pearson")  
print(corr)  
```

## 그래프 그리기

x축을 날짜로 설정하고, y축에 달러인덱스와 환율을 각각 표시한 그래프를 그립니다.


## 결과

이 그래프는 달러인덱스와 환율 간의 관계를 시각화한 것입니다.  
상관계수를 통해 두 변수 간의 관계를 확인할 수 있습니다.

## Todo lists

이 프로젝트에서 처리해야 할 항목들:

```markdown  
- [x] 데이터 전처리  
- [x] 상관계수 계산  
- [ ] 그래프 최적화  
```

## Did you find this page helpful? Consider sharing it 🙌

