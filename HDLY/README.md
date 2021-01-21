# HDLY's logs



* <b>내일 할일</b>
  * DACON, LGBM으로 돌려보면서 데이터 형태 파악... EDA 해보기?



<hr>


#### 2021-01-21(목)

1. T 아카데미, [Pandas 기본기 다지기]

   1. 5강 Pandas 데이터 다루기 - 인덱싱/슬라이싱/불리언 인덱싱/삭제 - <a href="https://blog.naver.com/handuelly/222214672887">포스팅</a>
   2. 6강 Pandas 함수 I - Describe / Aggregate - <a href="https://blog.naver.com/handuelly/222214697057">포스팅</a>

2. 뉴스 클리핑

   1. <a href="https://blog.naver.com/handuelly/222214748353">[이데일리] 은행점포 폐쇄 브레이크‥금감원이 직접 관여한다</a>
   2. <a href="https://blog.naver.com/handuelly/222214755822">[머니투데이] 금감원, 디지털금융 감독 강화…'기울어진 운동장' 바로잡는다</a>
   3. <a href="https://blog.naver.com/handuelly/222214762918">[경향신문] 주식 공매도 금지 결국 연장되나···민주당 “연장이 다수···2월말~3월초 결정”</a>
   4. <a href="https://blog.naver.com/handuelly/222214774148">[ZDNetKorea] SK이노, 中 교체식 배터리 사업 진출</a>

3. DACON, [시스템 로그 분석, 사용자 불편 감지]

   1. 4차 회의(17:00~18:00)
   2. Quality_Data : int로 변환 마무리 후 변수로 추가(0.003 상승), 값 정규화는 아직(MH)
   3. fmver : 점(.)을 기준으로 펌웨어의 종류를 구분... 대신 다른 작업 중(JH)
   4. date & hour : err, problem, quality의 주기성 체크. 유의미한 해석이 필요(HD)

   

#### 2021-01-20(수)

1. T 아카데미, [Pandas 기본기 다지기]

   1. 3강 Pandas 데이터 입출력 I - Importing / Exporting (csv ,tsv, txt) - <a href="https://blog.naver.com/handuelly/222213431915">포스팅</a>
   2. 4강 Pandas 데이터 입출력 II - Importing/Exporting (Excel, 데이터베이스) - <a href="https://blog.naver.com/handuelly/222213450042">포스팅</a>

2. DACON, [시스템 로그 분석, 사용자 불편 감지]

   1. date & hour : 주기성 체크 -> 유의미한 연관성은 없어 보임

      

#### 2021-01-19(화)

1. T 아카데미, [Pandas 기본기 다지기]

   1. 1강 Pandas 데이터구조 I, Series - <a href="https://blog.naver.com/handuelly/222212237442">포스팅</a>
   2. 2강 Pandas 데이터구조 II, DataFrame - <a href="https://blog.naver.com/handuelly/222212279250">포스팅</a>

2. 뉴스 클리핑

   1. <a href="https://blog.naver.com/handuelly/222212464703">[ZDNetKorea] 네이버 쇼핑라이브 인기…6개월새 1억뷰 돌파</a>
   2. <a href="https://blog.naver.com/handuelly/222212477235">[ZDNetKorea] 서비스 안정 의무 기업에 구글‧페북‧넷플‧네이버‧카카오‧웨이브</a>

3. DACON, [시스템 로그 분석, 사용자 불편 감지]

   1. 3차 회의(19:00~20:00)

   2. Quality_Data : int로 변환 마무리 후 값 정규화. z-score / PCA 또는 다른 방식 적용Baseline에 변수 추가(MH)

   3. fmver : 점(.)을 기준으로 펌웨어의 종류를 구분. 수치화해서 값으로써 구분하고, 모델 학습에 적용(JH)

   4. date & hour : 주기성 체크. 유의미하다면 값으로 치환해섯 학습에 어떻게 적용시킬지 고민(HD)

      

#### 2021-01-15(금)

1. DACON, [시스템 로그 분석, 사용자 불편 감지]

   1. 데이터 파악

2. 뉴스 클리핑

   1. <a href="https://blog.naver.com/handuelly/222207737378">[파이낸셜뉴스] "개미만 피본다" "외국인 짐싼다".. 답없는 찬반 줄다리기 <증시·정치 블랙홀 된 공매도></a>

   

#### 2021-01-14(목)

1. T 아카데미, [인공지능을 위한 머신러닝 알고리즘]

   1. 14강 "Theano를 통한 머신러닝 구현" - <a href="https://blog.naver.com/handuelly/222206949682">포스팅</a>
   2. 15강 "Keras를 통한 딥러닝" - <a href="https://blog.naver.com/handuelly/222206962132">포스팅</a>
   3. 수강 확인 테스트 실시, 통과 - <a href="https://blog.naver.com/handuelly/222206996678">포스팅</a>

2. 뉴스 클리핑

   1. <a href="https://blog.naver.com/handuelly/222207714891">[코로나 실업] 지난해 취업자 21.8만명 감소, IMF 이후 최악… "일 좀 하고 싶다"</a>
   2. <a href="https://blog.naver.com/handuelly/222207737378">[파이낸셜뉴스] "개미만 피본다" "외국인 짐싼다".. 답없는 찬반 줄다리기 <증시·정치 블랙홀 된 공매도></a>

3. DACON, [시스템 로그 분석, 사용자 불편 감지]

   1. 2차 회의(16:30~17:00)

   2. EDA

   3. Baseline에 변수 추가(MH)

      

#### 2021-01-13(수)

1. T 아카데미, [인공지능을 위한 머신러닝 알고리즘]

   1. 12강 "딥러닝 응용 사례" - <a href="https://blog.naver.com/handuelly/222205746565">포스팅</a>
   2. 13강 "Weka를 이용한 머신러닝" - <a href="https://blog.naver.com/handuelly/222205756708">포스팅

2. 뉴스 클리핑

   1. <a href="https://blog.naver.com/handuelly/222206028466">[ESG] 삼성, LG, SK, 카카오의 ESG 경영 전략</a>

3. DACON, [시스템 로그 분석, 사용자 불편 감지]

   1. 대회 코드 공유 & 토론 게시판 follow up

   2. EDA

      

#### 2021-01-12(화)

1. T 아카데미, [인공지능을 위한 머신러닝 알고리즘]

   1. 09강 "컨볼루션 신경망" - <a href="https://blog.naver.com/handuelly/222204960303">포스팅</a>
   2. 10강 "재현 신경망" - <a href="https://blog.naver.com/handuelly/222205159823">포스팅</a>
   3. 11강 "메모리 네트워크" - <a href="https://blog.naver.com/handuelly/222205321972">포스팅</a>
2. 뉴스 클리핑

   1. <a href="https://blog.naver.com/handuelly/222205362958">[공매도 재개] 주가 폭등, 표심 노린 정치권, 그리고 동학개미들</a>




#### 2021-01-11(월)

1. T 아카데미, [인공지능을 위한 머신러닝 알고리즘]

   1. 06강 "신경망" - <a href="https://blog.naver.com/handuelly/222203522246">포스팅</a>
   2. 07강 "역전파" - <a href="https://blog.naver.com/handuelly/222203560916">포스팅</a>
   3. 08강 "비지도 학습" - <a href="https://blog.naver.com/handuelly/222203651409">포스팅</a>
2. 뉴스 클리핑

   1. <a href="https://blog.naver.com/handuelly/222203668808">[ZDNetKorea] 사상 첫 온라인 'CES 2021'…AI·모빌리티·로봇 주목</a>
   2. <a href="https://blog.naver.com/handuelly/222203683357">[이데일리] 국민 절반 유료OTT 봤고, 그 중 절반 넷플릭스 봤다</a>
   3. <a href="https://blog.naver.com/handuelly/222204041885">[챗봇] AI 챗봇 '이루다'에 대하여</a>
3. DACON, [시스템 로그 분석, 사용자 불편 감지]
   1. 1차 회의(16:30~17:00)
   2. Baseline 수행, 코드 공유 및 토론 게시물 숙지



#### 2021-01-10(일)

1. 자소서

   1. 02번 작성

      

#### 2021-01-08(금)

1. T 아카데미, [인공지능을 위한 머신러닝 알고리즘]

   1. 04강 "결정 트리" - <a href="https://blog.naver.com/handuelly/222200441160">포스팅</a>
   2. 05강 "서포트 벡터 머신" - <a href="https://blog.naver.com/handuelly/222200501175">포스팅</a>

2. 뉴스 클리핑

   1. <a href="https://blog.naver.com/handuelly/222200557401">[서울신문] 中, 쓰레기 수거함도 안면인식… ‘CCTV 지옥’ 탈출 나선 시민들</a>

   

#### 2021-01-07(목)

1. T 아카데미, [인공지능을 위한 머신러닝 알고리즘]
   1. 01강 "머신러닝 개요" - <a href="https://blog.naver.com/handuelly/222199342602">포스팅</a>
   2. 02강 "선형 회귀 모델" - <a href="https://blog.naver.com/handuelly/222199383159">포스팅</a>
   3. 03강 "로지스틱 회귀 모델" - <a href="https://blog.naver.com/handuelly/222199410046">포스팅</a>
2. 뉴스 클리핑
   1. <a href="https://blog.naver.com/handuelly/222199618503">[New1] 마윈 압박 본격화…시진핑이 원하는 건 따로 있었다</a>
   2. <a href="https://blog.naver.com/handuelly/222199634531">[ZDNetKorea] SK, 美 수소에너지 기업에 1조6천억원 투자</a>
   3. <a href="https://blog.naver.com/handuelly/222199649877">[ZDNetKorea] LG전자, 美 데이터 분석 업체 '알폰소' 인수</a>
3. 자소서
   1. 01번 작성

