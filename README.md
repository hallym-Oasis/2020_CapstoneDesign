# 2020-2 한림대학교 캡스톤 디자인
# 비상시 공공시설 위치조회 앱 : Oasis

***
## 팀 구성
- 팀명 : Oasis
- 지도교수 : 이원철
- 팀장 : 백수민
- 팀원 : 신수진 배건희 강예정

***
## 앱 소개
### 앱 로고
![앱로고](https://user-images.githubusercontent.com/71078577/101245409-14c07280-3750-11eb-8270-9f8f9a57e745.png)     
- 사이렌과 오아시스의 시원함, 청량감을 나타낸다.

### 앱 슬로건
“사막에 떨어진 것처럼 막막한 상황에서 당신의 오아시스를 찾아드립니다＂     
비상시 공공시설 위치조회 앱, Oasis

***
## 프로젝트 요약
 일상생활 속에서 비상시 공공시설의 위치조회가 필요할 때 한번에 조회 및 신고할 수 있는 기능을 포함한 애플리케이션으로 크게 사이렌기능, 신고기능, 위치조회 기능으로 나뉜다. 사이렌 기능에서는 위급상황 시 사이렌이 재생되도록 하여 주변에 자신의 위험을 알릴 수 있도록 도와준다. 

 신고기능에서는 앱에서 버튼을 누르면 바로 112에 전화 연결과 문자 보내기 기능이 가능하고, 112 신고 시 사전에 등록해 놓은 연락처로 연락할 수 있도록 구현하였다.

 위치조회 기능은 원하는 공공시설의 위치 정보 버튼을 누르면 구글 맵을 통해 자신과 가까운 공공시설의 위치를 보여준다. 조회하는 공공시설을 지도상에 마커로 표시하였고, 마커 클릭 시 구글맵으로 연동되어 네비게이션 기능을 사용할 수 있다.
 
***
## 목적 및 기대효과
### 목적
 - 목적 1. 각 공공시설의 위치조회 기능으로 비상시 손쉽게 공공시설의 위치를 조회하고 시설의 상세정보를 파악할 수 있도록 한다.
 - 목적 2. 비상시 사이렌이 작동되도록 하여 주변에 자신의 위험을 알릴 수 있도록 한다.
 - 목적 3. 문자 메시지와 112 신고기능을 통해 위급상황 시 위치 정보를 포함한 문자를 112로 전송하여 원활한 112 신고가 이루어질 수 있도록 도와준다.
 
 ### 기대효과
 - 위급상황 시 사이렌을 활용해 주변에 도움을 요청함으로써 위급상황을 바로 알릴 수 있게 해주며, 비상전화번호 저장 기능과 112 문자, 전화 기능을 이용해 쉽고 빠르게 112 신고가 가능하여 범죄도 예방할 수 있어 국민들의 **안전과 치안유지에 효과가 있을 것이다.**
 - 공공시설의 위치를 직접 검색할 필요 없이 빠르게 버튼 하나로 조회가 가능하여 현재 자신의 위치와 가까운 공공시설의 위치를 파악하고 네비게이션 기능을 통해 길도 쉽게 찾을 수 있어 **공공시설의 활용도와 앱 필요도가 증가하는 효과를 얻을 수 있다고 생각한다.**     
 
***
## 앱 개발환경
- Android Studio
- SQLite
- GoogleMap Api

***
## 앱 전체 구조
![앱구조](https://user-images.githubusercontent.com/71078577/101245601-56055200-3751-11eb-8b8c-a7f289ea414a.png)

***
## 앱 주요기능
![image](https://user-images.githubusercontent.com/71078577/101270710-15442200-37bf-11eb-8a84-228411fb8760.png)
***
## 사용 데이터 및 출처
![image](https://user-images.githubusercontent.com/71078577/101270979-fc893b80-37c1-11eb-828b-f52dad2e0a79.png)

### 출처
- [공공데이터포털_공중화장실](https://www.data.go.kr/data/15012892/standard.do)
- [공공데이터포털_무료와이파이](https://www.data.go.kr/data/15013116/standard.do)
- [공공데이터포털_여성안심지킴이집](https://www.data.go.kr/data/15034535/standard.do)
- [공공데이터포털_졸음쉼터](https://www.data.go.kr/data/15028203/standard.do)
- [공공데이터포털_여성안심택배함](https://www.data.go.kr/data/15034534/standard.do)

***
## 개발코드
[완성코드 링크](https://github.com/hallym-Oasis/Oasis_Android)

### 개별코드
- [백수민 - 위치조회_구글맵](https://github.com/Sumniling/Oasis_Sumin)     
- [신수진 - 전체 레이아웃](https://github.com/Suzzn2/Oasis)     
- [배건희 - 신고기능](https://github.com/baennigans/oasis_bae)     
- [강예정 - 위치조회_DB연동/조회](https://github.com/bananana0118/Oasis_YeaJeong)     

***
## Index
- [회의록](https://github.com/hallym-Oasis/2020CapstonDesign-Oasis/tree/master/%EA%B4%80%EB%A6%AC)
- [주간보고](https://github.com/hallym-Oasis/2020CapstonDesign-Oasis/tree/master/%EC%A3%BC%EA%B0%84%EB%B3%B4%EA%B3%A0)
- [설계](https://github.com/hallym-Oasis/2020CapstonDesign-Oasis/tree/master/%EC%84%A4%EA%B3%84)
- [데이터](https://github.com/hallym-Oasis/2020CapstonDesign-Oasis/tree/master/%EB%B6%84%EC%84%9D)
- [제출물](https://github.com/hallym-Oasis/2020CapstonDesign-Oasis/tree/master/%EC%A0%9C%EC%B6%9C)

