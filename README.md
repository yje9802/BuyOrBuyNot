# 💸 BuyOrBuyNot
이 물건을 사야할 지, 말아야 할 지 고민될 때! BuyOrBuyNot에 공유하고 다른 사람들의 조언을 구해볼 수 있는 서비스입니다.

<br>

## 프로젝트 기능 및 설계
#### ☑️ 회원가입/로그인 기능
- 소셜 로그인 제공
- 로그인 하지 않은 유저의 게시글 작성, 의견 표시 기능 제한
- 일반적으로 모든 사용자는 회원가입시 USER 권한 (일반 권한)을 지닌다.

#### ☑️ 회원 정보 조회 기능
- 회원 기본 정보 조회
- 회원 활동 관련 정보 조회
	- 올린 게시글 조회
		- 진행 중인 게시글인지 마감된 게시글인지 표기
		- 진행 중인 게시글일 경우 수정 기능 제공
	- 포인트 조회
 		- 포인트 사용 내역 확인 기능
			- 획득 날짜, 사용 날짜 등 표기
#### ☑️ 게시글 작성 기능
- 게시글 작성
	- 로그인한 사용자만 가능
	- 제목, 상품 이미지, 설명, 카테고리, 마감 기한(사람들의 의견을 받을 수 있는 기한), 선착순 설정 여부는 필수
- 선착순 기능 설정
	- 현재 사용가능한 포인트 표시
	- 설정을 ON할 경우 작성자 포인트 차감
	- 선착순 안에 의견을 표시한 사람은 포인트 획득
#### ☑️ 게시글 조회 기능
- 기본적으로 최신순으로 게시글 보여주기
	- 카테고리, 조회수, 게시글 제목, 선착순 여부, 마감 여부 표시
- 카테고리별 게시글 목록 보여주기도 가능
- 게시글 제목, 유저 아이디를 이용해 게시글 검색 가능
- 게시글 조회는 로그인 하지 않은 유저도 가능
#### ☑️ 게시글 의견 표시 기능
- 추천, 비추천 버튼
- 선착순 안에 의견을 표시한 사람에게 포인트 적립

<br>

## ERD
![ERD](doc/img/erd(2).png)

<br>

## Trouble Shooting
👉🏻 [여기서 확인할 수 있습니다.] (.)

## Tech Stack
✔️ Backend

<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/springsecurity-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"> 

✔️ Database

<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"> <img src="https://img.shields.io/badge/elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white"> <img src="https://img.shields.io/badge/amazons3-569A31?style=for-the-badge&logo=amazons3&logoColor=white">

✔️ Config

<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
