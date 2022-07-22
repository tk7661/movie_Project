## 영화 예매 및 리뷰 사이트 제작 프로젝트(●'◡'●)

>본 프로젝트는 cgv 홈페이지를 참고하여 제작하였습니다.

 [🚗 cgv.co.kr](https://www.cgv.co.kr) 


## 사용한 기술 스택🎫  

<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
 <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
<img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">
<br>
<img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> 
<img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> 
<img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">


## 개발 기간 

2022.04.28- 2022.06.10 (6주)

## 프로젝트 실행🚍

프로젝트 내부에 있는 Wallet_Ezenac1 폴더를 C드라이브에 두고 실행해야 정상 작동됩니다.

##  주요 기능 🐱‍🏍
### client
   1. 회원가입 
      -    ID중복확인
      -    이메일 인증
   2. 로그인
   3. 마이페이지
      -    회원 정보 수정
      -    회원 탈퇴 하기
      -    예매 내역 보기
      -    리뷰 관리(수정/삭제)
      -    문의 내역 보기, 답변 확인
   4. 영화 예매 하기
      -    영화 ,극장, 시간,좌석 선택
      -    카카오페이 결제
      -    선택 좌석 처리
      -    예약 좌석 처리
   5. 영화 리뷰 작성
      -    리뷰,별점 작성
      -    수정
      -    삭제
      -    신고 하기
      -    추천 하기
   6. 문의하기
      -    문의 작성
      -    파일 업로드
### admin
   1. 영화 관리 
      -    영화 등록
      -    수정
      -    삭제
   2. 회원 관리
      -    회원 정보 보기
      -    예매 내역
      -    리뷰 내역
      -    문의 내역
      -    회원 정지
      -    회원 탈퇴
   3. 문의 관리
      -    문의 삭제
      -    답변 작성
      -    파일 다운로드
   4. 리뷰 관리
      -    리뷰 수정
      -    삭제
   5. 신고 처리(미흡)
      -    신고 유저 정지 기간 설정
      -    신고 삭제
      -    신고 중복 처리 , 경고 기능 (미완성)
<br>  

 --- 
 
내가 개발한 부분

관리자 로그인 후
홈페이지에서 영화 수정 삭제 버튼 눌렀을떄 화면 구현( 수정은 팀장님의 도움을 조금 받음)
삭제에서 삭제 버튼 눌렀을 때 데이터베이스에서 영화 삭제

회원관리 버튼 눌렀을 때 화면 구현
회원 로그인 정지 기능 추가
스케쥴러를 이용해 매일 0시 정각에 정지 해제일과 오늘 날짜를 비교하여 정지를 해제시킴 

