
#  Data Crawling

> 프로젝트 기간 : 2021.12.01 ~ 2021.12.23
> 
> 
> 팀 프로젝트 ( 조원: 하연, 숭인, 정훈 - iOS 3명 )
> 
> 프로젝트명 : 🧻  Separate_Collection_AlphaGo  🧻
> 
> 4학년 데이터크롤링 과목 기말고사 팀 프로젝트로, 머신러닝, 크롤링, API 등을 이용하여 프로젝트를 기획 및 개발하였습니다.
> 



## 📌 목차

- 프로젝트 소개
- Skills
- Contributions
    - 핵심 기능 소개
    - 세부 구현
- 개발일지
- 상세 화면
- 과제중 어려웠던 점
- 참고자료

## 프로젝트 소개

### 기획의도 ( 선정 이유 )

<aside>
🗣 코로나 바이러스가 장기화되면서 여러 문제들이 대두가 되고있는데, 그 중에 심각한 골칫거리가 바로 쓰레기 문제입니다. 오래전부터 쓰레기 문제로 몸살을 앓고 있었지만 코로나가 낳은 소비변화, 즉 온라인 쇼핑과 배달음식 주문 같은 비대면 소비가 늘면서 일회용품 사용이 폭발적으로 증가하고 재활용 쓰레기도 급증하여 더욱 악화되어 있습니다. 하지만, 이렇게 증가된 쓰레기들을 올바르게 분리수거한다면 조금이나마 쓰레기도 줄일 수 있고 환경도 보호할 수 있습니다.

</aside>

### 프로젝트 설명

<aside>
🗣 따라서 저희 앱은 분리수거를 해야할 상황이 놓여져 있을때, 생각보다 많은 사람들이 재활용이 가능한 쓰레기인지, 재활용인 척하는 일반쓰레기인지 명확하게 모른다는 점을 파악하여 위와 같은 고민을 해결해주며 재활용이 가능한 쓰레기를 분리수거할 때 해당 쓰레기의 재활용 종류를 알려주어 올바르게 분리수거를 할 수 있게 도와줍니다. 또 마지막으로 주변 분리수거장을 지도로 표시하여 보다 편리하게 사용할 수 있습니다.

</aside>

## Skills

- iOS Platform (macOS- Xcode), Swift, UIKit, SwiftUI, Combine
SnapKit, Then, Git, Github
- Lottie-ios, NMapsMap, Kingfisher, Charts
- API : PostMan, Alamofire, JSON, SWXMLHash
- 데이터크롤링 : SwiftSoup, Selenium
- AwesomeUI
- MVVM 패턴

## 개발 일지

|날짜|내용|팀원|수행여부|
|------|---|---|---|
| 12.09 | 아이디어 회의 및 역할 분담 | 공통  | ⭕️ |
| 12.10  | 프로젝트 초기 설정 | 숭인  | ⭕️ |
| 12.10  | 깃 올가니제이션 파기 | 숭인  | ⭕️ |
| 12.10  | 화면 설계 및 자료 조사  | 하연  | ⭕️ |
| 12.11  | 지도 연동 테스트 | 정훈  | ⭕️ |
| 12.11  | 현 위치 가져오기 기능 테스트 | 정훈  | ⭕️ |
| 12.12  | ML에 대한 자료 조사 완료 | 하연 | ⭕️ |
| 12.13  | 분리수거 종류 선별 | 숭인,하연  | ⭕️ |
| 12.13  | 셀레니움을 통한 웹 이미지 동적 크롤링 | 숭인  | ⭕️ |
| 12.13  | CoreML로 이미지 학습시키기 | 하연  | ⭕️ |
| 12.14  | 추가 이미지 데이터 수집 | 숭인| ⭕️  |
| 12.14  | 두번째 탭바 화면 구조 수정 | 숭인| ⭕️  |
| 12.14  | TrashService 추가 작업 | 정훈  | ⭕️  |
| 12.14  | Response Entity 추가 | 정훈  | ⭕️  |
| 12.14  | info.plist에 API 키 추가 | 정훈  | ⭕️  |
| 12.14  | 카메라 기능 테스트 완료(개) | 하연  | ⭕️  |
| 12.14  | 사진 찍고 난 후 저장 테스트 완료(개) | 하연  | ⭕️ |
| 12.14  | 로딩 화면 테스트 완료(개) | 하연  | ⭕️ |
| 12.14  | 앱 아이콘 테스트 완료(개) | 하연  | ⭕️ |
| 12.14  | 화면 구체적인 회의 및 역할 재분배 | 숭인,하연  | ⭕️ |
| 12.15  | 테스트 이미지로 올바르게 학습됬는지 확인  | 하연  | ⭕️ |
| 12.15  | 구현한 카메라로 다시한번 확인 작업(개) | 하연  | ⭕️ |
| 12.15  | 머신러닝으로 한 작업 화면에 띄우기(개) | 하연  | ⭕️ |
| 12.16  | conflict : 다시 초기 환경 세팅  | 숭인 | ⭕️ |
| 12.16  | 재활용품 관련 모델, 크롤러 추가  | 숭인 | ⭕️ |
| 12.16  | API Endpoint 변경  | 정훈  | ⭕️ |
| 12.16  | XMLresponse 파싱 (SWXMLHash)  | 정훈  | ⭕️ |
| 12.16  | 사진첩에서 사진 가져와서 띄우기(개)  | 하연  | ⭕️ |
| 12.16  | 정확도 높이기 위한 사진 배경 제거 구현(개) | 하연  | ⭕️ |
| 12.16  | 분석한 결과를 텍스트로 띄우기(개) | 하연  | ⭕️ |
| 12.16  | 분석한 결과를 차트로 표시하기(개) | 하연  | ⭕️ |
| 12.16  | 1차 리팩토링 작업 및 테스트 완료(개) | 하연  | ⭕️ |
| 12.16  | 앱 이용 설명서 페이징처리로 구현(개) | 하연  | ⭕️ |
| 12.16  | cache 삭제 | 숭인 | ⭕️ |
| 12.16  | 분리수거 분류, 배출요령 크롤러 추가 | 숭인 | ⭕️ |
| 12.16  | info.plist http 권한 부여 | 숭인 | ⭕️ |
| 12.16  | 분리수거 요령 rootView 추가 | 숭인 | ⭕️ |
| 12.16  | 재활용품 분리배출 요령 이미지보기 뷰 추가 | 숭인 | ⭕️ |
| 12.16  | 재활용품 분리배출 요령 텍스트로 보기 뷰 추가 | 숭인 | ⭕️ |
| 12.16  | API Response Decoding 작업 | 정훈 | ⭕️ |
| 12.16  | Location을 활용하여 시군구 가져오기 기능 추가 | 정훈 | ⭕️ |
| 12.16  | 현위치 시/군/구를 통해 정보 가져오기 | 정훈 | ⭕️ |
| 12.17  | Waste 리스트 뷰 추가 | 정훈 | ⭕️ |
| 12.17  | 쓰레기 상세 매출요령 뷰 추가 | 정훈 | ⭕️ |
| 12.17  | 카메라 및 사진 권한 info.plist 설정(팀) | 하연  | ⭕️ |
| 12.17  | 카메라 PreviewView 추가(팀) | 하연  | ⭕️ |
| 12.17  | JSON 파일 추가, 로딩화면 구현(팀) | 하연  | ⭕️ |
| 12.17  | 홈 화면 구현, 다른 화면과 연결(팀) | 하연  | ⭕️ |
| 12.17  | 이용 가이드 화면 구현(팀) | 하연  | ⭕️ |
| 12.17  | ML 관련 ImagePredictor 추가(팀) | 하연  | ⭕️ |
| 12.17  | ML 관련 기타 파일들 추가(팀) | 하연  | ⭕️ |
| 12.17  | 학습시킨 CoreML Model 및 기타 자료 추가(팀) | 하연  | ⭕️ |
| 12.17  | 카메라 화면 구현(팀) | 하연  | ⭕️ |
| 12.17  | 카메라 사진촬영, 사진캡쳐, 화면전환 등 기능 구현(팀) | 하연  | ⭕️ |
| 12.17  | 캡쳐한 사진 사진첩에 저장(팀) | 하연  | ⭕️ |
| 12.17  | 사진 등록 및 편집 화면 구현(팀) | 하연  | ⭕️ |
| 12.17  | 사진 등록하는 기능 추가(팀) | 하연  | ⭕️ |
| 12.17  | 사진 배경제거 기능 추가(팀) | 하연  | ⭕️ |
| 12.17  | Toast로 지연 발생 시간 알림(팀) | 하연  | ⭕️ |
| 12.17  | 분석하는 화면 생성 및 이동 연결(팀) | 하연  | ⭕️ |
| 12.17  | 앱과 내가 만든 ML 적용 후 텍스트로 보여주기(팀) | 하연  | ⭕️ |
| 12.17  | 앱과 내가 만든 ML 적용 후 차트로 보여주기(팀) | 하연  | ⭕️ |
| 12.17  | 테스트 및 리팩토링(팀) | 하연  | ⭕️ |
| 12.19  | 환경부 가이드라인 뷰 추가 | 숭인  | ⭕️ |
| 12.21  | 앱 아이콘 설정 | 하연  | ⭕️ |
| 12.21  | 로딩 화면 구현 완료 | 하연  | ⭕️ |


## Contributions

- ppt에 내용 적혀있음

## 시연 영상

- 추후 유튜브 영상으로 올릴 예정

 

## 상세 화면

<img width="668" alt="스크린샷 2021-12-22 오후 2 11 48" src="https://user-images.githubusercontent.com/55241258/147039234-5b5c9be9-b1fa-4551-92de-b7b91451c69b.png">
<img width="689" alt="스크린샷 2021-12-22 오후 2 11 52" src="https://user-images.githubusercontent.com/55241258/147039240-6878e50c-6608-471a-bfc7-ac0ffbb6bb5c.png">
<img width="703" alt="스크린샷 2021-12-22 오후 2 11 56" src="https://user-images.githubusercontent.com/55241258/147039244-d1125a6c-ef63-4508-953b-6b528660a4f5.png">
<img width="683" alt="스크린샷 2021-12-22 오후 2 12 00" src="https://user-images.githubusercontent.com/55241258/147039246-31bbcf26-a36a-4df3-9787-0b163cc84ca9.png">


## 후기

저희 또한 제대로 된 분리수거 배출요령에 대해서 다시한번 깨닫게 되는 의미있는 프로젝트였습니다. 또한, 같은 분야 사람들끼리 이 프로젝트를 Git을 이용해 협업을 진행하게 되어 좋은 경험이였습니다.

- 과제 중 어려웠던 점 :
    - 데이터 수집 부분에 있어서 몇가지 어려웠던 점이 있었습니다. 원하는 자료들을 크롤링하기 위해 많은 사이트를 들어갔지만, 크롤링이 막아져있는 웹사이트가 많았습니다. 또한, 수집된 데이터의 양이 적어 이미지 트레이닝을 하기에 부족하였습니다. 이는 dataset 사이트를 찾아 보충하여 마무리하였습니다.
    - API부분도 간략하게 말씀드리겠습니다. 처음에는 내 주변 분리수거장을 지도에 띄우려고 설계하였고 지도 API까지 구현하였지만 찾은 open API에 lat, lon 부분이 없어 포기하고 앞서 보여드린 것과 같이 내가 사는 동네의 쓰레기 배출 정보로 변경하였습니다.
    - 마지막으로 팀원 모두 공통점으로 iOS 플렛폼을 사용하지만, 각자 사용하는 구조, 언어 사용법 등이 달라 Git을 Merge할때 Conflict에 대한 우려가 많았고, 이에 따른 시행착오도 발생하였습니다. 이를 Git commit시 Git 컨벤션을 지키거나, Pr에 개발일지를 같이 올려 모든 팀원이 approve 후 merge하는 등 노력하였습니다. 또한 개발함에 있어 협업시 Merge할 때 가장 문제가 많이 발생하는 Storyboard를 사용하지 않고 SwiftUI, Combine, SnapKit, Then 등을 활용하여 코드로 모든 개발을 작업하였습니다. + 탭으로 역할을 나눠 진행