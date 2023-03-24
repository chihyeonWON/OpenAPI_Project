# OpenAPI_Project
건강보험심사평가원의 OpenAPI를 활용한 Flutter 앱 프로젝트
```
개발 툴 : Flutter
개발 언어 : Dart
개발 일시 : 2023-03-24 - ~ 
개발자 : Won Chi Hyeon
```

## 건강보험심사평가원_병원평가정보서비스 OpenAPI 신청하기
[건강보험심사평가원_병원평가정보서비스 OpenAPI 사이트](https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15094093)

![image](https://user-images.githubusercontent.com/58906858/227527756-c12a7506-800b-4916-b8fc-c3a52d636cb4.png)

```
API를 발급받기 위해서 사이트에 접속 후 활용신청을 하면 인증키를 발급받을 수 있습니다.
```

## 데이터 형식
![image](https://user-images.githubusercontent.com/58906858/227532806-e39c26c7-fc45-4ecc-be59-33ed71a69d33.png)

```
건강보험심사평가원_병원평가정보서비스에서 제공하는 데이터의 형태는 XML입니다.
따라서 GET 방식으로 데이터를 요청하고 쓸만한 응답 데이터들을 앱 UI에 보여지도록 하면 될 것 같습니다.
```
