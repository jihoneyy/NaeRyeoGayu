<span style="font-size:30px">내</span><span style="font-size:25px">려</span><strong style="font-size:20px">가</strong><strong style="font-size:17px">유</strong>

SSAFY 4기 자율 1반 3팀 <span style="color: green; font-size: 25px">더치페이</span>입니다.

<p align="center">
<img src="https://user-images.githubusercontent.com/77089164/121697057-a5b14580-cb07-11eb-9b7a-aad37a08393d.png">


<p style="padding: 15px">
<img src="https://img.shields.io/static/v1?label=SSAFY&message=4%EA%B8%B0&color=0ABAB5">
<img src="https://img.shields.io/static/v1?label=Seoul&message=Class1&color=00a3d2">
<img src="https://img.shields.io/static/v1?label=Domain&message=AutonomyProject&color=ABF200">
</p>

- 리퍼브 상품에 하향식 경매를 이용해 판매하는 쇼핑몰 프로젝트입니다.
- 저희가 취급하는 리퍼브 상품이란 소비자 기준에 미치지 못하는 상품들로 <br />
  못난이 농산품, 포장 불량 이나 상품 흠집들이 존재하는 공산품, 유통기한 임박상품이 있습니다.
-  하향식 경매는 최고가로 시작되어 시간이 지나면서 값이 점점 내려가는 경매 입니다.
- 리퍼브 상품들은 재고로 처리되며 시간이 지나면 점점 가치가 하락한다는 공통점이 있습니다.
- 따라서 리퍼브 상품에 하향식 경매를 적용해 시간에 따라 가치가 달라지는 점을 반영했습니다.
</p>

&nbsp;
&nbsp;
---
&nbsp;
&nbsp;


## 📗목차

- [기획배경](#💡기획배경)
- [기획](#💾기획)
  - 와이어프레임
  - ERD
  - API Table
- [주요기능](#🛒주요기능)
- [기술스택](#🛠기술스택)
- [개발환경](#📂개발환경)
  - 소스트리(Sourcetree)
  - Git 컨벤션
- [시작하기](#🐣시작하기)
- [만든사람들](#만든사람들)

&nbsp;
&nbsp;
---
&nbsp;
&nbsp;


# 💡기획배경


<img src="https://user-images.githubusercontent.com/77089164/121698872-6552c700-cb09-11eb-9a44-71ff11729189.png">

&nbsp;
&nbsp;
---
&nbsp;
&nbsp;

# 💾기획

## [와이어 프레임](https://www.figma.com/file/6Qi8Xm9QdUBCSITZJSI4Qw/%EC%9E%90%EC%9C%A8-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8?node-id=0%3A1)

<img src="https://user-images.githubusercontent.com/77089164/121699515-f88bfc80-cb09-11eb-8f93-3da6284a56d3.jpg">

## [ERD](https://www.erdcloud.com/d/Q2J7PtKbnRL55vnw4)

<img src="https://user-images.githubusercontent.com/77089164/121700074-7ea84300-cb0a-11eb-9d99-c74520d61236.png">

## [API Table](https://www.notion.so/API-ad638aad80a84f769262a9eabb2930d0)

<img src="https://user-images.githubusercontent.com/77089164/121701437-de531e00-cb0b-11eb-986a-0bc9cd258664.jpg">
<br />
<img src="https://user-images.githubusercontent.com/77089164/121701445-df844b00-cb0b-11eb-8c90-b2c434b84117.jpg">
<br />
<img src="https://user-images.githubusercontent.com/77089164/121701451-e0b57800-cb0b-11eb-827a-ec7c7f4d0e24.jpg">

&nbsp;
&nbsp;
---
&nbsp;
&nbsp;

# 🛒주요기능

<img src="https://user-images.githubusercontent.com/77089164/121702048-7d781580-cb0c-11eb-8f79-33e5f3454d92.jpg">
<br />
<img src="https://user-images.githubusercontent.com/77089164/121702038-7c46e880-cb0c-11eb-8bcf-681c1d96f5cb.jpg">
<br />
<img src="https://user-images.githubusercontent.com/77089164/121702045-7d781580-cb0c-11eb-916d-e58153cc59c0.jpg">

## 1. 테마 별 상품 조회
## 2. 상품 카드화로 간편하게 정보 확인
## 3. 마이페이지를 통해 활동 내역 확인
## 4. 스케쥴러를 통해 지속적인 가격 변동, 경매 기간 확인, 예약 구매 기능


&nbsp;
&nbsp;
---
&nbsp;
&nbsp;


# 🛠기술스택

## FrontEnd

```
  
    "axios": "^0.21.1",
    "core-js": "^3.6.5",
    "eslint-config-prettier": "^8.2.0",
    "firebase": "^8.4.2",
    "jwt-decode": "^3.1.2",
    "moment": "^2.29.1",
    "swiper": "^5.3.7",
    "vue": "^2.6.11",
    "vue-awesome-swiper": "^4.1.1",
    "vue-infinite-loading": "^2.4.5",
    "vue-router": "^3.2.0",
    "vuetify": "^2.4.11",
    "vuex": "^3.4.0"
  
```

## [BackEnd](https://www.notion.so/Version-e100ebc4cd9640128633f853f336202e)

```
    "jdk" : "zulu-1.8.0_192",
    "sts" : "^3.9.14",
    "spring starter" : "^2.4.2",
    "lombok" : "^1.18.12",
    "jwt" : "^0.9.1",
    "swagger" : "^2.9.2",
    "spring security" : "^2.4.4",
    "JPA" : "^2.4.5"
```



&nbsp;
&nbsp;
---
&nbsp;
&nbsp;


# 📂개발환경

### 소스트리(Sourcetree)

<img src="https://user-images.githubusercontent.com/77089164/121702227-a8626980-cb0c-11eb-957c-7b9156d67457.png">

- 소스트리를 활용하여 깃을 체계적으로 관리했습니다.
- branch를 쉽게 생성하며, 어떤 branch가 존재하는지 파악하기 쉽습니다.
- stash, push, pull, commit 등 알기 쉽게 구성되어 있고, 현재 어떤 상태인지 쉽게 파악할 수 있습니다.

### Git 컨벤션

```

    Commit : #<JIRA issue number> <type>:<subject>
    Branch : <type>/<Fe/Be><summary>  ⇒ Pascal 표기법으로 적기
    MR(PR) : <JIRA issue number> <description>
    
```


&nbsp;
&nbsp;
---
&nbsp;
&nbsp;


# 🐣시작하기
exec dir 를 참조해주세요!

---
&nbsp;
&nbsp;


# 👨‍💻만든사람들

## 팀장 : 하태민 (BackEnd + DevOps)
##  팀원 
## 1. 김명규 (BackEnd)
## 2. 권영일 (BackEnd)
## 3. 송지헌 (FrontEnd + 최종 발표)
## 4. 천창민 (FrontEnd + 중간 발표)

<h2>지금까지 <strong style="color: green; font-size: 45px;">더치페이</strong>의 리드미였습니다. <br/> 감사합니다!</h2>

<img src="https://user-images.githubusercontent.com/77089164/121702330-bd3efd00-cb0c-11eb-8737-d644f53769f1.jpg">
