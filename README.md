# Financial Pseudonymization

## 1. What is pseudonymization?

## 2. How do we pseudonymize?  
### 2.1 수치형 변수  
- 상단처리(상위 99.9% 이상의 값 처리)  
- 상하단처리(상하위 99.9% 값 처리)  
- 내림 또는 라운딩: Erase last 2 digits in numbers (ex. $1223.00 -> $1200)  
### 2.2 날짜형 변수: Erase "day" part of date info (ex. 1991.02.23 -> 1991.02)  
### 2.3 범주형 변수: 특정 값이 1,2개인 경우 주변 카테고리 값으로 대체  
  
## 3. 특이값 처리
- 특이값은 제외하고 가명처리를 하는 경우 (ex. 카드 항목 999999991 : 카드 2개 이하 사용자의 공유 정보 제한)

## 4. Pseudonymization with "class" 

## 5. 시간 단축 방법

## 6. 메모리 효율성 높이는 방법
  
