# Kooq
# <img src="https://user-images.githubusercontent.com/68576681/177258571-64e4855d-bdca-4335-b221-e23d54708cbe.jpg" width="30" height="30"> 몰입스타그램
> 2분반 2주차(2022.07.06~07.12) By 김아나스타시야, 정재모
# Table Of Contents
* [Project Summary](#project-summary)
* [Developer Information](#developer-information)
* [Development Environment](#development-environment)
* [Application Information](#application-information)
  * [0. Login & Kakao Login](#0-login--kakao-login)
  * [1. Tab1 - Home](#1-tab1---home)
  * [2. Tab2 - Find](#2-tab2---find)
  * [3. Tab3 - Post](#3-tab3---post)
  * [4. Tab4 - My Posts](#4-tab4---my-posts)
  * [5. Future Work(언젠가)](#5-future-work언젠가)
***
***# Project Summary
* 같은 대학 사람들과 전공 서적을 중고 거래할 수 있는 '당근 마켓 & KAIST OTL' 컨셉의 어플리케이션입니다.
* Login 할 때 MySql에 로그인 정보가 있어야 로그인 할 수 있습니다
* Home 탭에서 과목 구분, 학과, 학년을 선택하여 학교 시간표를 볼 수 있습니다
* Find 탭에서 전체 책의 정보를 볼 수 있고, 원하는 책을 검색할 수도 있습니다
* Post 탭에서 중고로 거래하고 싶은 책을 올릴 수 있습니다!
* My 탭에서 내가 업로드한 책들의 정보를 볼 수 있습니다
** Home 탭에서 과목 클릭 시 교재 구매 사이트로 이동 혹은 중고 거래를 할 수 있습니다.

***# Developer Information
* [정재모](https://github.com/JaemoJeong) (KAIST 전산학부)
* [김아나스타시야](https://github.com/anista13) (부산대학교 정보컴퓨터공학과)
***# Development Environment
* OS: Android & iOS
* Language: Java Script
* IDE: React Native
* Target Device: iPhone X, 11
* Server: NodeJs + Express
* Database: MySQL
***# Application Information
## 0. Login & Kakao Login// add here screens of Login and kakao Login pages### Major Features* Login 할 때 DataBase에 로그인 정보가 있어야 로그인 할 수 있습니다
* ID와 비밀번호를 입력받아 로그인을 할 수 있습니다
* 계정이 없을 시, Kakao 로그인을 통해 계정을 생성할 수 있습니다### Technology Used
* Node JS 웹 서버에 MySql를 사용하여 모든 유저들의 정보, 시간표 정보, 중고 책 정보를 서버에 저장해놓았습니다.
* 따라서 다른 기기에서도 동일한 ID로 로그인 할 수 있습니다## 1. Tab1 - Home// add images of home page### Major Features
* Home 탭에서 과목 구분, 학과, 학년을 선택하여 학교 시간표를 볼 수 있습니다
* MySQL
  * 원하는 과목 구분, 학과, 학년을 선택하여 MySql에서 알맞은 과목을 불러옵니다.
* 검색 결과에 따라서 화면상단에는 과목 Card를 볼 수 있습니다
  * Card에서 과목 이름, 교수, 구분, 학과, 교제까지 확인 할 수 있습니다
  * Buy 버튼을 누르면 중고 장터로 이동하며 자동으로 해당하는 책을 장터에서 검색합니다.
  * E-buy 버튼을 누르면 교재 구매 사이트로 이동합니다.### Technology Used
* Flat List를 사용해 모든 요소들이 같이 움직일 수 있도록 하였습니다.## 2. Tab2 - Find// add images of find page### Major Features
* MySQL에 있는 책 정보를 불러와 책 정보 카트를 볼 수 있습니다.
  * '판매자에게 쪽지 보내기' 버튼을 터치하여 카카오톡 오픈채팅 화면으로 돌아갈 수 있습니다
* 중고 장터에서 책 이름 검색을 통해 원하는 책을 찾을 수 있습니다.
* ScrollView를 사용해 모든 요소들이 같이 움직일 수 있도록 하였습니다
* '+' 터치시 Post 탭으로 이동합니다## 3. Tab3 - Post// add image of post page here### Major Features
* Post 페이지에서 팔고 싶은 책을 장터에 올릴 수 있습니다.
* 'See my posts' 터치 시 자기 게시물을 확인할 수 있습니다### Technology Used
* Firebase를 통해 사용자들이 보낸 메세지들을 서버에 모두 저장합니다 //EDIT HERE## 4. Tab4 - My Posts
// add images of my posts page### Major Features//EDIT HERE### Technology Used
* Firebase를 통해 사용자들이 보낸 메세지들을 서버에 모두 저장합니다 //EDIT HERE## 5. Future Work
학교 API와 연동 시 바로 사용할 수 있는 앱이라고 생각합니다.
카카오 로그인 대신 학교 메일과 연동.
금융 거래 시스템 구축.

![Image from iOS (2)](https://user-images.githubusercontent.com/98383656/178478256-d07830d0-bed3-4f48-9104-bc1357d86f18.png)
![Image from iOS (1)](https://user-images.githubusercontent.com/98383656/178478261-cc1a33b3-5a30-4434-812c-db0eb1f37f7d.png)
![Image from iOS](https://user-images.githubusercontent.com/98383656/178478264-18330f69-a5c4-4a4a-9604-5f6079ade018.png)
![Image from iOS (2)](https://user-images.githubusercontent.com/98383656/178478267-5e77e4a5-9070-4586-b9a2-c460fb189b46.jpg)
![Image from iOS (1)](https://user-images.githubusercontent.com/98383656/178478271-b078730b-87b7-4b80-95cd-4c6d2739e90b.jpg)
![Image from iOS](https://user-images.githubusercontent.com/98383656/178478274-a2779cdb-7c38-45d7-afd5-f2ec18a3b71c.jpg)
