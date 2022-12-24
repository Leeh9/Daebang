### 🥇 SSAFY 1학기 관통 프로젝트 최우수상

# 📢 프로젝트 소개

### ✔️ **프로젝트 명**

### 대 방

### ✔️ **프로젝트 설명**

![슬라이드1](https://user-images.githubusercontent.com/40704078/206139865-303c6b0d-9b51-4808-b717-118b193d231e.PNG)

![슬라이드4](https://user-images.githubusercontent.com/40704078/206140000-fc1a3211-de35-4c7e-8f97-cee89e8674b5.PNG)

![슬라이드7](https://user-images.githubusercontent.com/40704078/206140220-13fb49ee-1684-4351-b806-441090482a77.PNG)

```
대방은 Backend는 SpringBoot , Frontend는 Vue로 구현하고 DB를 구축하여 데이터를 관리하는 프로젝트이다.

MVC + MVVM 기반의 웹 프로젝트를 설계하고 구현하며, Kakao Map API와 공공 데이터 포털을 통해 
대전지역의 전,월세 데이터를 가공하여 기능을 제공한다.

사용자는 원하는 지역을 검색하고 관심 지역에 등록하여 추천 시스템을 이용할 수 있다.

사용자가 선택한 지역의 전,월세 자료를 테이블 형태로 보여주며, 해당하는 집의 이름 클릭 시 
상세정보와 반경 1KM 지역 이내의 상권 위치를 확인할 수 있다.

편의 기능으로 교통, 날씨, 관광지 정보를 제공한다.
```

### ✔️ **실행**

### Vue
```
npm install

npm run serve
```


### ✔️ **프로젝트 일정**

### **2022-11-14 ~ 2022-11-24**

![일정](https://user-images.githubusercontent.com/40704078/205673452-8f75a479-d8ed-45c7-8778-0b9fe1f373e5.PNG)


## 📌 목표

- Web Architecture를 이해하고 활용하여 Web Project를 설계하고 구현할 수 있다.
- Spring & MyBatis Framework, Spring Boot, Vue.js를 이해하고 활용할 수 있다.

## ⭐ 프로젝트 기능

1. 주택 실거래가 정보 수집 (아파트, 다가구주택, 오피스텔)
2. 주택 실거래가 검색 (아파트, 다가구주택, 오피스텔)
3. 회원 관리 ( 회원가입, 회원탈퇴, 내 정보 수정)
4. 로그인 관리 ( 로그인 / 로그아웃 )
5. 관심 지역 추가 / 삭제 (회원 전용)
6. 주변 상권 정보 수집
7. 주변 상권 업종 정보 검색 (8가지 대 분류)
8. 주변 날씨 정보 수집 / 출력
9. 주변 관광지 정보 수집 / 출력
10. 사용자에게 상권 선호 지수를 입력 받아 관심 지역 추천 시스템 구현(회원 전용)
11. 점수 기반 관심 지역 랭킹 / 차트 출력
12. 주요 지역 실시간 교통 상황
13. 실시간 교통 상황 공유 게시판 (글 쓰기, 수정, 읽기, 회원 전용)
14. 버스 정류소 실시간 버스 도착 정보 (검색)
15. 지하철 역 상세 정보 확인
16. 주택, 관광지 썸네일 이미지 검색 기능

## 💥 기술 스택

 <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white">

## 📡 사용한 Open API
![슬라이드6](https://user-images.githubusercontent.com/40704078/206140383-991422e2-4292-489e-8110-9611f3e6ea54.PNG)
<details>
<summary>
API
</summary>

![%EB%8D%B0%EC%9D%B4%ED%84%B03](https://user-images.githubusercontent.com/40704078/205664753-ebfe4e32-006e-4e52-a1eb-5e063921691f.png)
![%EB%8D%B0%EC%9D%B4%ED%84%B01](https://user-images.githubusercontent.com/40704078/205664762-a809f512-ea0e-4983-a535-ff7efe86ecd0.png)
![%EB%8D%B0%EC%9D%B4%ED%84%B02](https://user-images.githubusercontent.com/40704078/205664763-ebd9427c-fd79-45cb-b972-0d45791ff3eb.png)
</details>

## 📜 UseCase Diagram

<details>
<summary>
UseCase Diagram
</summary>

![daebang_usecase](https://user-images.githubusercontent.com/40704078/205671331-66f9d05c-2974-400e-b484-46db7ee58d70.png)

</details>

## 📢 화면 구성
<details>
<summary>
화면 구성
</summary>

## [ 0. 메인 ]

- **화면**

![main-full](https://user-images.githubusercontent.com/40704078/205667024-6d3c35b3-e687-417c-8272-8cb90efed2cb.png)


- **기능 설명**
    
    페이지 첫 실행시 보여지는 화면으로 인사말, 서비스소개, 공공데이터, 팀원 소개로 이루어져있다.
    

## [ 1. 전,월세 실거래 조회]

- **화면**

![apt-search-keyword](https://user-images.githubusercontent.com/40704078/205667148-ce9e6e2c-12b9-486c-bd4c-e3b5346f3296.png)

![apt-search-1](https://user-images.githubusercontent.com/40704078/205667167-473841f4-1a16-48f5-8eb2-11fda3618a61.png)

![apt-search-2](https://user-images.githubusercontent.com/40704078/205667157-31ebe5f1-4079-4b67-88ea-2fbd1996b2c2.png)

- **기능 설명**
    
    로그인 하면 대전 지역 전,월세 실거래 조회 화면으로 넘어간다.
    
    타입, 구 , 연 , 월을 선택하면 해당하는 지역의 다음 selectbox가 표시된다.
    
    검색을 누르면 해당하는 지역의  전,월세 실거래 데이터가 조회된다.
    

## [ 2. 해당 주거형태의 이미지 불러오기 기능 ]

- **화면**
    
    ![apt-search-3](https://user-images.githubusercontent.com/40704078/205667238-fedc3ce1-17e5-4796-8b29-4fd691181594.png)
    

- **기능 설명**
    
    전월세 데이터를 조회한 후 해당 데이터를 클릭 시 상세정보가 출력되며 카카오 이미지 검색 api를 이용하여
    
    정확도 순으로 첫 번째에 있는 이미지를 가져온다.
    

## [ 3. 카카오맵에서 매물 위치 및 상세 정보 조회 ]

- **화면**
    
   ![detail-full](https://user-images.githubusercontent.com/40704078/205667340-f413b34c-eee9-491e-8cb7-2839919a7c36.png)

![detail-near-list-2](https://user-images.githubusercontent.com/40704078/205667382-83b4710e-b62a-4a9b-b11c-92de7e69f1c7.png)

![detail-near-button](https://user-images.githubusercontent.com/40704078/205667404-182c1aee-516f-4fdd-8f9d-4fe9bc2afe5f.png)

![detail-near-list-1](https://user-images.githubusercontent.com/40704078/205667407-3e3221e4-e74e-4ecc-b8d5-809c22ffc38a.png)

- **기능 설명**
    
    원하는 매물의 상세정보 페이지로 이동하여 카카오지도 위에서 매물 위치를 시각적으로 확인할 수 있다.
    
    상권 버튼을 눌러 사용자가 원하는 키워드 버튼을 클릭하면 해당 키워드에 맞는 상권 정보를 조회 가능하다. 각 상권 버튼을 누르면 상세정보가 보이며, 지도에서 인포윈도우로 정확한 위치를 파악할 수 있다. 상권 목록은 [접기]나 [상권모양버튼]으로 언제든 닫거나 열 수 있다.
    

## [ 4. 실시간 날씨 예보 조회 ]

- **화면**

![detail-near-weather](https://user-images.githubusercontent.com/40704078/205667474-376efc11-1481-4e04-a3bd-bcf37d5b14db.png)


- **기능 설명**
    
    중앙 상단의 날씨 버튼을 누르면 현재 페이지의 매물 위치 정보를 토대로 약 하루동안 날씨 예보를 시각적 아이콘으로 파악할 수 있다.
    

## [ 5. 주변 관광 정보 조회 ]

- **화면**
    
    ![detail-near-tour-1](https://user-images.githubusercontent.com/40704078/205667524-913152e6-6ef5-4db1-9779-5a59cf1932b0.png)

![detail-near-tour-2](https://user-images.githubusercontent.com/40704078/205667530-a7d9373b-1c44-4e36-b534-4afaccd145b6.png)

    

- **기능 설명**
    
    중앙 상단의 관광지 버튼을 누르면 현재 페이지의 매물 위치 정보를 토대로 동일한 구군 지역의 관광지를 리스트 형태로 보여준다. 각 항목을 클릭하면 우측 화면에서 관련 상세 정보를 조회할 수 있다.
    

## [ 6. 교통 상황 조회]

- **화면**

![traffic-road](https://user-images.githubusercontent.com/40704078/205667683-65b3e740-406d-4be3-ac5a-eed48f1195c3.png)


- **기능 설명**
    
    교통상황 버튼을 클릭하면 해당 페이지로 넘어간다.
    
    랜드마크 버튼을 클릭하면 해당 지역의 실시간 교통 상황을 보여준다.
    

## [ 7. 교통 상황 공유 게시판 ]

- **화면**
    
![traffic-road-board](https://user-images.githubusercontent.com/40704078/205667779-563a69cc-a1ca-4adc-9631-2093136b257c.png)

![traffic-road-board-success](https://user-images.githubusercontent.com/40704078/205667786-2d5504b4-de1e-4557-be6c-b543b9121dcf.png)

![traffic-road-board-write](https://user-images.githubusercontent.com/40704078/205667790-75da09c8-532b-486b-9833-51aa02a57a79.png)
    
![traffic-road-board-write-after-modifyable](https://user-images.githubusercontent.com/40704078/205667773-6df0ac81-ddf2-44b0-bf27-676cf9c08076.png)


- **기능 설명**
    
    랜드마크의 게시글 버튼을 클릭하면 오른쪽에 사이드바와 함께 해당하는 지역의 게시글 목록을 출력한다.
    
    각 게시판 별로 유저는 CRUD 기능을 이용할 수 있고 게시글을 클릭하면 내용이 출력된다.
    
    작성일시가 함께 출력되므로 실시간으로 교통 정보를 공유할 수 있다.
    

## [ 8. 실시간 버스정류소 조회 ]

- **화면**
    
![traffic-road-bus](https://user-images.githubusercontent.com/40704078/205668011-82c8fff2-e55a-4cb8-9c5a-9fc311ca412f.png)
    
![traffic-road-bus-search](https://user-images.githubusercontent.com/40704078/205668029-f9510aec-159c-405c-a47a-1bbe9c271447.png)
    
![traffic-road-bus-detail](https://user-images.githubusercontent.com/40704078/205668027-78498767-7e82-47ba-97a4-a0b0787e9225.png)
    
- **기능설명**
    
    대전광역시 3072개의 정류소 정보를 슬라이드쇼 형태로 조회할 수 있다.
    
    우측 상단의 검색창을 통해 원하는 키워드의 정류소만 모아서 볼 수 있다.
    
    원하는 정류소를 클릭하면 상세 정보를 모달창으로 확인할 수 있다.
    

## [ 9. 지하철 역사 정보 조회 ]

- **화면**
    
![traffic-subway](https://user-images.githubusercontent.com/40704078/205668105-e79b0384-aa0e-4ae1-a5ba-f813a153f370.png)

![traffic-subway-detail](https://user-images.githubusercontent.com/40704078/205668100-8d38fca9-1f2f-4deb-ab5a-8b69112679bf.png)

- **기능설명**
    
    대전시의 모든 도시철도 역사정보를 슬라이드쇼 형태로 확인할 수 있다. 
    
    원하는 역을 클릭하면 모달창으로 상세정보를 조회 가능하다.
    

## [ 10. 관심지역 설정 ]

- 화면
    
![wish-add-1](https://user-images.githubusercontent.com/40704078/205668213-da6f0c91-60c0-4fc4-a4f7-fd80b3a0461a.png)

![wish-add-2](https://user-images.githubusercontent.com/40704078/205668214-56768f96-c0c8-454c-9b29-ad48360fe961.png)
    
![wish-add-3](https://user-images.githubusercontent.com/40704078/205668208-a32300d5-7f06-4daf-ac55-1ee951cc6af2.png)
    
- 기능설명
    
    로그인을 하면 3번의 페이지에서 하트 버튼이 보인다. 빈 하트를 누르면 관심지역에 추가되고, 하트가 채워진다. 반대로 채워진 하트를 누르면 관심지역에서 삭제되고 하트가 비게 된다.
    
    해당 내역은 11번 관심지역 랭킹에서 상세하게 확인할 수 있다.
    

## [ 11. 관심지역 랭킹과 주변 상권 리스트 ]

- **화면**
    
![wishrank-1](https://user-images.githubusercontent.com/40704078/205668294-8369964d-bbe9-470e-aef7-c19c00029ce6.png)
    
![wishrank-2](https://user-images.githubusercontent.com/40704078/205668292-f29ece9b-4765-4185-9b37-35933d2c914f.png)
    

- **기능설명**
    
    사용자가 설정한 상권 선호도 점수를 바탕으로 점수화하여 시상대와 차트 형태로 표현했다.
    
     ( = 선호상권 유/무 + 반경500m 해당 상권 개수)
    
    1~3위 매물은 해당 정보를 클릭하면 주변 상권 목록을 키워드 별로 모아서 볼 수 있다.
    

## [ 12. 로그인/로그아웃/회원가입/회원탈퇴/마이페이지/정보수정 ]

- **화면**
    
![login-before](https://user-images.githubusercontent.com/40704078/205668433-c0a60cf9-c8af-44d4-9a88-0a9bdc4669d9.png)
    
![login-after](https://user-images.githubusercontent.com/40704078/205668426-85ef3aa0-c4fe-4eed-84cc-c37dc9a5810e.png)
    
![modify-1](https://user-images.githubusercontent.com/40704078/205668437-4c9174b6-97a9-4408-bc0d-447c0d112288.png)
    
![modify-alert-fail](https://user-images.githubusercontent.com/40704078/205668440-b521f6e2-f5fa-4651-90b0-3a9155b5da7c.png)
    
![modify-alert-success](https://user-images.githubusercontent.com/40704078/205668444-550c7b26-2977-498c-a5a1-c8b7dfc7e3f6.png)
    
![regist-alert-fail](https://user-images.githubusercontent.com/40704078/205668448-ccbaa49e-e58b-4e69-9ab4-4a815d55d495.png)
    
![regist-alert-success](https://user-images.githubusercontent.com/40704078/205668421-874fa2a1-e87f-42c1-b9a0-40d0ec061985.png)
    

- **기능설명**
    
    jwt 토큰 방식으로 로그인하여 안정성을 비교적 높였다.
    
    회원가입은 전용 페이지에서, 정보 수정과 회원 탈퇴는 마이페이지에서 가능하다.
    마이페이지 내에 있는 상권 선호도 정보를 통해 사용자가 점수를 커스터마이징 할 수 있다.
    

![login-refreshToken](https://user-images.githubusercontent.com/40704078/205668626-e50b9391-d624-43e1-80dd-b6e64766215b.png)
    
![wishscore-modify](https://user-images.githubusercontent.com/40704078/205668779-dfce203a-ee54-47fd-90aa-fc52a06e719f.png)
    
![wishscore-modify-after](https://user-images.githubusercontent.com/40704078/205668786-00af7cd5-fb29-4b24-9e7e-0d38ff57caac.png)
    
![wishscore-modify-success](https://user-images.githubusercontent.com/40704078/205668775-c720939d-8855-4402-882c-538fcbdcfce2.png)
    
</details>

## 🎉 **기대효과**
![슬라이드10](https://user-images.githubusercontent.com/40704078/206141072-896fbcce-208e-4dea-b2e4-a194a1f6d0dd.PNG)

## 🚢 **팀원**

![team](https://user-images.githubusercontent.com/40704078/205658314-0ae64e21-4fd3-4272-964b-f3db88208347.gif)


- **[이현구](https://github.com/Leeh9)**
- **[서현경](https://github.com/nanalyee)**
