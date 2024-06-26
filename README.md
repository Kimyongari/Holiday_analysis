# Holiday_analysis

각 국가별 휴일 수와 근로 시간, 행복지수에 대한 관련성을 분석한 파일입니다.

### 사용 데이터
1. 나라별 공휴일 데이터
2. OECD 나라별 근로 시간 데이터
3. SDSN(Sustainable Development Solutions Network) 행복지수 2021 데이터

### 총평

각 나라의 휴일 수와 연 근로시간, 행복지수 순위를 엮어 하나의 데이터 프레임을 형성했다.

행복지수는 다양한 요인에 의해 결정되기에 단정지을 수는 없지만, 근로시간이 적을수록 행복지수의 순위가 높아지는 경향을 보였다.

행복지수와 휴일 수, 행복지수와 연 근로시간의 관계는 둘 다 스피어맨 검정결과 기준 p-value가 0.05미만으로, 나름의 관계성이 있음을 볼 수 있었다.


특히, 상관계수를 비교해 봤을 때, 휴일 수 보다는 연 근로시간과의 관계성이 더 두드러졌다.

각 변수들의 상관계수를 spearmanr 상관계수와 kendalltau 상관계수로 계산했을 때, spearmanr 상관계수의 값이 조금 더 높았다. 

p-value는 둘 다 0.05 미만으로 신빙성이 어느정도 보장된다고 볼 수 있었다.

-------------------------------------------------------------------------------

하지만 데이터 분석 결과, 내가 처음 생각했던 정도의 큰 상관관계가 있지는 않았다.

내 생각에 일을 덜 하고 많이 쉬는 것이 당연한 행복으로 이어질 것이라 생각하였지만 행복한 삶은 그런 단순한 계산들로 이어지지는 않는 듯 하다.

특히, 이스라엘은 휴일 수도 적지 않은 9개에, 연간 평균 근로시간은 1891.90시간으로 1901.00시간인 한국과 큰 차이가 없었는데도 행복지수가 무려 4등이었다


그렇다면 우리나라 사람들이 불행하다 느끼는 이유는 뭘까?

최근 기사에 따르면 우리나라의 출산율은 0.6대를 돌파했다고 한다.

남성 100명 여성 100명을 두고 100쌍의 커플에게 출산율 0.6을 적용하면

한 세대 뒤에 60명의 아이가 태어난다.

즉, 80년 뒤에는 우리나라의 인구가 200명에서 60명이 되어 30%만 남는다는 의미이다.

숫자들로 계산해보니 꽤 심각한 듯 하다. 

시간이 여유로워 진다면 다음 데이터 분석 주제는 다양한 요인들
(출산율이 떨어지는 요인을 과거 행복지수와 현재 행복지수, 과거 출산율이 높던 시절의 인당 GDP와 현재 GDP간의 차이 등)

등을 EDA를 하며 이유를 찾아보고 싶다.


 


