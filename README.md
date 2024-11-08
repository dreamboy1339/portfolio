# 프로젝트

## Amondz(아몬즈)

- Company: Bejewel(비주얼)
- 주얼리 커머스 서비스 안드로이드 앱
  - [아몬즈](https://www.amondz.com/)
  - [아몬즈 – 주얼리, a부터 z까지](https://play.google.com/store/apps/details?id=com.amondz)
- Tech Spec
  - Language: Kotlin
  - Architecture
    - MVVM 기반 AAC ViewModel, LiveData, DataBinding; Clean Architecture Oriented
    - XML-based and Jetpack Compose-based UI
    - ADS(Amondz Design System)
  - Dependency Injection: Hilt
  - Network: Rest API-based Retrofit
  - Asynchronous Processing: Kotlin Coroutine, Flow
  - External Service, API & Tools
    - Firebase
      - Cloud Messages, RemoteConfig, Analytics, CrashLytics, App Distribution, Dynamic Links, Performance, A/B Test
    - SNS login
      - Kakao, Naver, Facebook
  - Version Control & Deployment: Git, Github Actions
  - Issue Tracking & Analysis: Firebase Crashlytics, Android Vital
  - User Analysis: Firebase Analytics, AppsFlyer, Braze, Amplitude, Airbridge
  - Etc: Zai(Recommendation), Channel Talk
- [세부사항](amondz/amondz.md)

## Wavve(웨이브)

- Company: Contentwavve(콘텐츠웨이브)
- OTT 서비스 안드로이드 앱
  - [Wavve](https://www.wavve.com/)
  - [Wavve(웨이브)](https://play.google.com/store/apps/details?id=kr.co.captv.pooqV2)
- Tech Spec
  - Language: Kotlin, Java
  - Architecture
    - MVP + MVVM 기반 AAC ViewModel, LiveData, DataBinding
    - XML-based and Jetpack Compose-based UI
  - Dependency Injection: Hilt
  - Network: Rest API-based Retrofit
  - Asynchronous Processing: Kotlin Coroutine, Flow
  - External Service, API & Tools
    - Firebase
      - Cloud Messages, Analytics, CrashLytics, Dynamic Links
    - SNS login
      - Kakao, Naver, Facebook, T ID, Apple
  - Version Control & Deployment: Git, Gitlab
  - Issue Tracking & Analysis: Android Vital
  - User Analysis: Google Analytics, Braze

## 키친보드(도도카트)

- Company: Spoqa(스포카)
- 식자재 유통 중계 플랫폼 서비스 키친보드 매장 안드로이드 앱
  - [키친보드](https://kitchenboard.co.kr/)
  - [식자재 명세표 자동 정리](https://youtu.be/XdRuzcY46uI) : 23' 3월 기능 종료
  - [키친보드(도도카트) - 비용관리, 주문](https://play.google.com/store/apps/details?id=com.spoqa.ops)
- Tech Spec
  - Language: Kotlin, Java
  - Architecture: MVVM 기반 AAC ViewModel, LiveData, DataBinding; Clean Architecture Oriented
  - Dependency Injection: Hilt
  - Network: GraphQL using Apollo
  - Asynchronous Processing: Kotlin Coroutine, Flow
  - External Service, API & Tools
    - Firebase
      - Cloud Messages, RemoteConfig, Analytics, CrashLytics, App Distribution, Dynamic Links
    - Kakao
      - Kakao Login
    - Sendbird Chat
  - Version Control & Deployment: Github, CircleCI
  - Issue Tracking & Analysis: Sentry
  - User Analysis: Google Analytics, AppsFlyer, Insider

## 키친보드 유통사

- Company: Spoqa(스포카)
- 식자재 유통 중계 플랫폼 서비스 키친보드 유통사 안드로이드 앱
  - [키친보드](https://kitchenboard.co.kr/)
  - [키친보드 - 유통사](https://play.google.com/store/apps/details?id=com.spoqa.app.vendor)
- Tech Spec
  - Language: Kotlin, Java
  - Architecture: MVVM 기반 AAC ViewModel, LiveData, DataBinding; Clean Architecture Oriented
  - Dependency Injection: Hilt
  - Network: GraphQL using Apollo
  - Asynchronous Processing: Kotlin Coroutine, Flow
  - External Service, API & Tools
    - Firebase
      - Cloud Messages, RemoteConfig, Analytics, CrashLytics, App Distribution
    - Sendbird Chat
  - Version Control & Deployment: Github, CircleCI
  - Issue Tracking & Analysis: Sentry
  - User Analysis: Google Analytics

## 마카롱 택시

- KST 모빌리티
- 마카롱 기사 앱 개발 및 유지 보수.
  - [마카롱택시(기사님용)](https://play.google.com/store/apps/details?id=kst.macaron.chauffeur)

- 사용 기술
  - 언어: Kotlin
  - 아키텍처: MVVM; AAC ViewModel, LiveData + DataBinding + DI(Hilt)
  - ConstraintLayout, RecyclerView, MDC
  - Coroutines, RxAndroid, RxBinding4
  - Database: Room
  - Firebase: Crashlytics, App Distribution, Google Analytics, FCM
  - 네트워크: Retrofit, Okhttp, gRPC, Protobuf
  - 라이브러리: Glide, Lottie, Gson, jackson, stetho, strikt, leakcanary, kotlin-coroutines-test, inavi-maps-sdk, inavi-navigation-sdk
  - 버전 관리 및 배포: 관리(Gitlab), CI/CD(GitLab Runner, Firebase App Distribution)
  - 이슈 분석 및 도구: Sentry, Kibana

<img src="/image/macaron1.png" width="20%" height="20%"></img> <img src="/image/macaron2.png" width="20%" height="20%"></img> <img src="/image/macaron3.png" width="20%" height="20%"></img>

## 나우웨이팅

- 나우버스킹
- 나우웨이팅 웰컴 앱 개발 및 유지 보수
  - [나우웨이팅 웰컴](https://play.google.com/store/apps/details?id=com.nowbusking.nowwaiting.welcome)

  - [서비스 소개 영상](https://youtu.be/KF7h1pO6ypM)

<img src="/image/nw1.png" width="20%" height="20%">

- 나우오더 키오스크 앱 개발 및 유지 보수
  - [나우웨이팅 매니저](https://play.google.com/store/apps/details?id=com.nowbusking.nowwaiting.manager)

  - [서비스 소개 영상](https://youtu.be/CC_2aRE1bdw?t=6)

- 사용 기술
  - 언어: Kotlin, Java
  - 아키텍처: MVP, MVVM; AAC ViewModel, LiveData + DataBinding
  - ConstraintLayout, RecyclerView, Preference, MDC
  - DataBase: Room
  - Firebase: Crashlytics, App Distribution, Analytics, FCM
  - 네트워크: Retrofit, Okhttp
  - 라이브러리: Glide, Lottie, Gson, EventBus, flexbox, circleimageview, fresco, stetho, leakcanary, mockito, uiautomator
  - 버전 관리 및 배포: 관리(Github), CI/CD(CircleCI, Firebase App Distribution)
  - 이슈 분석 및 도구: Sentry, Fabric, NewRelic

<img src="/image/nw2.png" width="20%" height="20%"> <img src="/image/nw3.png" width="20%" height="20%"> <img src="/image/nw4.png" width="20%" height="20%">

## 디지털페이지

- 파수 (구 파수닷컴)
- 디지털페이지 안드로이드 개발 및 유지 보수
  - [DigitalPage](https://play.google.com/store/apps/details?id=com.fasoo.digitalpage)

  - [서비스 소개 영상](https://youtu.be/vjYpCTEYfyA)

- 사용 기술
  - 언어: Java
  - 아키텍처: MVC
  - RecyclerView, Exifinterface, ConstraintLayout
  - Database: SQLite
  - Firebase: Crashlytics, App Distribution, FCM
  - 네트워크: Retrofit, Okhttp
  - 라이브러리
    - GMS: Google Plus, maps, location, auth, places, GA
    - AWS: aws core, s3
    - Facebook SDK - login
    - Kakao SDK - kakaolink, kakaostory, kakaotalk
    - Lombok, ButterKnife, TagSoup, Apache commons, Picasso, EventBus, ez-vcard, PhotoView
    - leakcanary-android, squareup-haha
    - JgraphT, Glide
    - Custom Library: Calendar, Tooltip, FloatingActionButton, SwipeLayout, SlideDateTimePicker, GoogleMapsAndroidMarkerClustering
    - ProGuard
  - 버전 관리: Subversion -> Git, Github
  - 이슈 분석 및 도구: Sentry, Fabric, adbrix

<img src="/image/dp1.png" width="20%" height="20%"> <img src="/image/dp2.png" width="20%" height="20%"> <img src="/image/dp3.png" width="20%" height="20%">
<img src="/image/dp4.png" width="20%" height="20%"> <img src="/image/dp5.png" width="20%" height="20%"> <img src="/image/dp6.png" width="20%" height="20%">
<img src="/image/dp7.png" width="20%" height="20%"> <img src="/image/dp8.png" width="20%" height="20%"> <img src="/image/dp9.png" width="20%" height="20%">
<img src="/image/dp10.png" width="20%" height="20%"> <img src="/image/dp11.png" width="20%" height="20%"> <img src="/image/dp12.png" width="20%" height="20%">
<img src="/image/dp13.png" width="20%" height="20%"> <img src="/image/dp14.png" width="20%" height="20%"> <img src="/image/dp15.png" width="20%" height="20%">
<img src="/image/dp16.png" width="20%" height="20%"> <img src="/image/dp17.png" width="20%" height="20%">

## 베가 뮤직

- 팬택
- 안드로이드 스마트폰 뮤직 플레이어 개발 및 유지 보수.
- 국내(SKT), 북미 및 일본 시장용 스마트폰 멀티미디어 통신사 스펙 시험 진행 및 해외 업무 대응.
- 멀티미디어 3rd 파티 업체와의 협업 및 이슈 대응.
- [SKY-IM100 소개 영상](https://youtu.be/TRG9usdJWJ4?t=35)

- 사용 기술
  - 언어: Java
  - 아키텍처: MVC
  - 버전 관리: Plastic SCM
  - Android Support Library, appcompat, design, palette, recyclerview
  - Jdom, U+appMarketExternalLib(LG U+용)
  - SKY SDK - ListView, Button 등등 디자인 컴포넌트 위주.
  - Custom library - GenreRepresent, MultimediaDataClient, TagParser, LEDControl
  - proguard

<img src="/image/m12.png" width="20%" height="20%"> <img src="/image/m11.png" width="20%" height="20%">
<img src="/image/m1.png" width="20%" height="20%"> <img src="/image/m2.png" width="20%" height="20%"> <img src="/image/m3.png" width="20%" height="20%">
<img src="/image/m4.png" width="20%" height="20%"> <img src="/image/m5.png" width="20%" height="20%"> <img src="/image/m6.png" width="20%" height="20%">
<img src="/image/m7.png" width="20%" height="20%"> <img src="/image/m8.png" width="20%" height="20%"> <img src="/image/m9.png" width="20%" height="20%">
