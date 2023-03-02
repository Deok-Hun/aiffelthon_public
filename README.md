
# AIFFEL X SOCAR PROJECT
* 모두의연구소 산하 인공지능 교육기관 AIFFEL과 카셰어링 기업 SOCAR가 협력하여 진행된 기업 연계 해커톤 프로젝트로서, 
  <br> [미시적 수요 분석과 모델링] 주제에 대해 SOCAR로부터 제공 받은 예약 데이터를 기반으로 프로젝트를 진행하였습니다.
<br/><br/>
* **단, SOCAR 제공 데이터 EDA 및 시각화 자료는 저작권 및 보안 이슈 문제로 비식별화 처리 되었음을 참고 바랍니다.**

<br/><br/>

# 프로젝트명: [ 수요분석을  통한 쏘카존 전략 제안 ]
<br/>

## 프로젝트 배경 및 목적
* 수요분석 및 예측을 통해 매출 극대화를 목표로, 매출에 직접적인 요인 중 쏘카존을 적절한 위치에 배치함으로써 <br/>
  매출 극대화 가능성을 확인하고 Roadmap 및 활용 시나리오를 제시하고자 함  
  
<br/>
  
## 프로젝트 목표
* 주거지역 인근에 쏘카존을 배치한다면 그 외 지역에 배치했을 때보다 <br/>
  더 큰 매출 상승을 기대할 수 있음을 가정하고 데이터 분석을 통해 이를 증명한다
  
<br/>

## 프로젝트 작성 코드
* 수요분석
  * 수요분석정리_230128.ipynb
* 외부데이터1(상관분석)
  * 이용시간_상관관계_a지역_230130.ipynb
  * 이용시간_상관관계_b지역_230125.ipynb
* 외부데이터2
  * 수요분석정리_외부데이터_230129.ipynb
* 모델링
  * 230131_모델(a지역).ipynb
  * 230131_모델(b지역).ipynb


<br/>

## 프로젝트 설명

<br/>

### 프로세스
![image](https://user-images.githubusercontent.com/106140951/216910143-43b39989-ad94-4ff8-a8d2-c8d5e33d2c6f.png)

<br/>

### ERD
![0](https://user-images.githubusercontent.com/112140344/220112452-f234f137-674e-433b-bb0b-2583aec1568b.PNG)

<br/>

### 수요분석
* 이용시간 분포 확인
![0220220645300533](https://user-images.githubusercontent.com/112140344/220117293-6f7ef6de-e073-4c31-98b9-6888125f0b11.jpg)

<br/>

* 경기도 기준 분석/예측
![0220220816775945](https://user-images.githubusercontent.com/112140344/220117650-ce7a41d7-5f53-4959-90a0-9758b2bce499.jpg)

<br/>

* 목적함수: 이용시간 → 매출로 변환
![16p_매출변환](https://user-images.githubusercontent.com/106140951/216993339-b9d231d1-9327-4fca-aef1-385799789544.png)

<br/>

### folium 시각화
* a지역: 아파트 반경 500m & 쏘카존 위치 시각화
![KakaoTalk_20230220_215904882_14](https://user-images.githubusercontent.com/112140344/220119152-d23e53ed-5cf7-4142-8564-4e94b00a508e.jpg)

<br/>

### 상관분석
* 상관계수 가중치 계산
![0220221656972634](https://user-images.githubusercontent.com/112140344/220119443-f76cb742-cb85-46df-8c38-81478cfee297.jpg)

<br/>

### 모델링
* 모델 로드맵
![KakaoTalk_20230220_215904882_01](https://user-images.githubusercontent.com/112140344/220123156-17f4ceea-a888-4e09-899b-da609f6aab7b.jpg)

<br/>

* 모델 예측 & 검증 확인
![0220223731652743](https://user-images.githubusercontent.com/112140344/220123389-da22081d-f166-4534-b428-62c47443430a.jpg)

<br/>

### 결론
* 신규 쏘카존 위치 예시
![KakaoTalk_20230220_215904882_04](https://user-images.githubusercontent.com/112140344/220123668-ad7bbfc3-1091-4155-80c2-c70050f3f86d.jpg)

<br/>

* 마케팅 전략
![41p_마케팅](https://user-images.githubusercontent.com/106140951/216995827-f11db2da-1b36-4190-8975-ec576277a6c9.png)

<br/>

* 활용 시나리오
![KakaoTalk_20230220_215904882_06](https://user-images.githubusercontent.com/112140344/220123902-57e10eb5-0080-4a68-bb26-3a8f2bab902c.jpg)

<br/>

### 회고 
* 보완 및 개선 가능성
![43p_보완점](https://user-images.githubusercontent.com/106140951/216995929-28376051-641a-4c06-939f-c6f196dd3906.png)

* 회고
![image](https://user-images.githubusercontent.com/112140344/220128312-c9b4c20d-9bec-44cc-a19f-1b006c8039be.png)







