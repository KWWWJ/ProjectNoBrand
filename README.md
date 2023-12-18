# ProjectNoBrand

## 프로젝트 목적
  클론코딩  
  원본사이트 : SSG쇼핑몰 - Nobrand (https://emart.ssg.com/specialStore/nobrand/main.ssg)
<br><br><br>
## 팀원 및 역할분담
  한상윤 (메인페이지, 상품목록페이지, 상픔등록페이지)  
  김동선 (DB, Bean, DAO, 로그인/아웃, 회원가입)  
  권원준 (페이지 공통배너, 장바구니, 상품상세페이지, 상품구매페이지)
<br><br><br>
## 프로젝트 기간
  10/30(월) ~ 11/10(금)  
  <11/10 발표>  
    
  -변경-  
  10/30(월) ~ 11/13(월)  
  <11/13 발표>
<br><br><br>
## 진행일정
### 10/30  
  * 기획회의  
  * 파트분배
<br><br><br>
### 10/31
  * 세부일정 확인  
  * 공통 페이지 작성  
  * DB 테이블 작성
<br><br><br>
### 11/1
  * 메인 페이지 작성
  * 장바구니페이지 작성  
  * Bean, DAO 클래스 작성
<br><br><br>  
### 11/2
  * 상품목록페이지 작성  
  * 장바구니페이지 CSS 추가수정
  * 로그인/아웃 페이지 작성
<br><br><br>  
### 11/3
  * 회원가입 페이지 작성
  * 상품등록페이지 작성
  * 상세페이지 작성 
<br><br><br>
### 11/4
  * 로그인/아웃 회원가입 페이지 CSS 수정
  * 이미지 업로드 구현(CKEditor5 사용)
  * 장바구니페이지 수정
<br><br><br> 
### 11/6
  * 상품등록페이지 CSS 추가수정
  * 상세페이지 CSS 추가수정
  * 장바구니 페이지 DB 연결
 <br><br><br>
### 11/7  
  * 장바구니 페이지 CSS 추가수정
  * 상품목록페이지 테스트
  * 상세페이지 테스트
<br><br><br>
### 11/8
  * 상품목록페이지 CSS 추가수정
  * 공통 상단바 수정(로그인/아웃 회원가입)
  * 로그인/아웃 회원가입 테스트
  * 장바구니 페이지 테스트
<br><br><br>
### 11/9
  * 상세페이지 CSS 추가 수정
  * 문서작성
<br><br><br>
### 11/10
  *
<br><br><br>
## 이슈
### Merge 중 Maven update 오류
  * 서버 실행에서 오류문구를 출력하며 서버실행 불가
  * 원인 : merge 중 xml 문서에 잘못된 문구가 삽입되어 오류 발생
  * 해결방법 : 메모장으로 직접수정하여 해결
   
### SQL query문 오류
  * 상품삭제 DB 처리 중 SQL 문 관련 오류 발생
  * 테이블에서 데이터는 삭제되나 오류메세지가 생겨 브라우저상에서 500에러 발생
  * 원인 : jdbcTemplate 메서드 잘못사용
  * 해결방법 : 메서드 query -> update 으로 수정하여 해결

## 정리 문서
 * https://www.canva.com/design/DAF0H7Mu9ro/eJqCJih-0lidOyE1J7iwkg/edit?utm_content=DAF0H7Mu9ro&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton


  
