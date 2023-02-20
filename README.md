
# AIFFEL X SOCAR PROJECT
* 모두의연구소 산하 인공지능 교육기관 AIFFEL과 카셰어링 기업 SOCAR가 협력하여 진행된 기업 연계 해커톤 프로젝트로서, 
  <br> [미시적 수요 분석과 모델링] 주제에 대해 SOCAR로부터 제공 받은 예약 데이터를 기반으로 프로젝트를 진행하였습니다.
* 단, SOCAR 제공 데이터 EDA 및 시각화 자료는 저작권 및 보안 이슈 문제로 비식별화 처리 되었음을 참고 바랍니다.

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
  * 이용시간_상관관계_경기도_230130.ipynb
  * 이용시간_상관관계_울산_230125.ipynb
* 외부데이터2
  * 수요분석정리_외부데이터_230129.ipynb
* 모델링
  * 230131_모델(경기).ipynb
  * 230131_모델(울산).ipynb


<br/>

## 프로젝트 설명

<br/>

### 프로세스
![image](https://user-images.githubusercontent.com/106140951/216910143-43b39989-ad94-4ff8-a8d2-c8d5e33d2c6f.png)

<br/>

### ERD
!![0](https://user-images.githubusercontent.com/112140344/220112452-f234f137-674e-433b-bb0b-2583aec1568b.PNG)

<br/>

### 수요분석
* 이용시간 분포 확인
!![0220214929307574](https://user-images.githubusercontent.com/112140344/220112982-0b1c7066-0619-4f86-87a2-5e91d4071a49.jpg)

<br/>

* 경기도 기준 분석/예측
![image](https://user-images.githubusercontent.com/106140951/216999909-47ce6530-1c08-4078-a734-2927d6574b9c.png)

<br/>

* 목적함수: 이용시간 → 매출로 변환
![16p_매출변환](https://user-images.githubusercontent.com/106140951/216993339-b9d231d1-9327-4fca-aef1-385799789544.png)

<br/>

### folium 시각화
* 경기도: 아파트 반경 500m & 쏘카존 위치 시각화
![22p_경기도시각화](https://user-images.githubusercontent.com/106140951/216994689-a42e2c91-455f-4032-836d-72ebe909de28.png)

<br/>

### 상관분석
* 상관계수 가중치 계산
![image](https://user-images.githubusercontent.com/106140951/216994968-e8b107ea-316f-43be-8f86-2ec7f0684819.png)

<br/>

### 모델링
* 모델 로드맵
![29p_모델로드맵](https://user-images.githubusercontent.com/106140951/216995329-5334f334-6568-4c22-b160-05f879b9df7f.png)

<br/>

* 모델 예측 & 검증 확인
![image](https://user-images.githubusercontent.com/106140951/216995481-ade466d2-4c8e-4fde-82af-f9f79a3d1b8d.png)

<br/>

### 결론
* 신규 쏘카존 위치 예시
![image](https://user-images.githubusercontent.com/106140951/216998161-7f300cc2-3b64-4d07-96ba-7fce4a407cd2.png)

<br/>

* 마케팅 전략
![41p_마케팅](https://user-images.githubusercontent.com/106140951/216995827-f11db2da-1b36-4190-8975-ec576277a6c9.png)

<br/>

* 활용 시나리오
![42p_활용시나리오](https://user-images.githubusercontent.com/106140951/216995859-ab541792-700a-4cd3-890d-7e2de642082b.png)

<br/>

### 회고 
* 보완 및 개선 가능성
![43p_보완점](https://user-images.githubusercontent.com/106140951/216995929-28376051-641a-4c06-939f-c6f196dd3906.png)






