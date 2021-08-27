# TIL
모각코 TIL

### :four_leaf_clover: 21/07/10
* front-end, back-end 기본적인 환경 구축
* 구현할 웹페이지의 구성을 Adobe XD 사용하여 제작
* 1개의 메인 페이지 및 4개의 상세 페이지 구성
  
  <details>
  <summary>메인 페이지</summary>
  <div markdown="1">       
  
  <img width=50%, height=70%  src="https://user-images.githubusercontent.com/79586634/125152397-40dd1f80-e187-11eb-8914-c4642b26175d.PNG"/>
  
  </div>
  </details>
  <details>
  <summary>상세 페이지 1 - '기초학습' 및 '심화학습' 페이지</summary>
  <div markdown="1">       

  <img width=50%, height=70%  src="https://user-images.githubusercontent.com/79586634/125152664-14c29e00-e189-11eb-989b-85b2be8007c0.png"/>
  
  </div>
  </details>
  <details>
  <summary>상세 페이지 2 - '퀴즈' 페이지</summary>
  <div markdown="1">       

  <img width=50%, height=70%  src="https://user-images.githubusercontent.com/79586634/125152684-3c196b00-e189-11eb-8f32-17582fa3d3a2.png"/>
  
  </div>
  </details>
  <details>
  <summary>상세 페이지 3 - '질문하기' 페이지</summary>
  <div markdown="1">       

  <img width=60%, height=70%  src="https://user-images.githubusercontent.com/79586634/125152698-45a2d300-e189-11eb-8f26-662ecba54c20.png"/>
  
  </div>
  </details>
  <details>
  <summary>상세 페이지 4 - 게시글 작성 페이지</summary>
  <div markdown="1">       

  <img width=50%, height=70%  src="https://user-images.githubusercontent.com/79586634/125152700-4f2c3b00-e189-11eb-97d3-4604cbee51a6.png"/>
  
  </div>
  </details>
* 다음 스터디 시간까지 웹페이지 템플릿 찾아오기

### :four_leaf_clover: 21/07/17
* xd website template 공유
* 각 페이지 별 xd website template 선정
* Adobe xd로 template 수정
* 각 페이지 별 구현 사항
  * 메인 페이지
    1. 상단 메뉴 바: 소개, 기초학습, 심화학습, 질문하기, 마이페이지, 로그인(버튼)
    2. 기초/심화학습 및 질문 게시판: 도형 클릭시 페이지 이동
    3. 콘텐츠 미리보기: 캡쳐된 콘텐츠 미리보기 가능
  * 로그인 페이지
    1. 아이디/비밀번호 입력 칸
    2. 로그인 버튼
    3. 회원가입 클릭 시 회원가입 창으로 페이지 이동
    4. 홈 버튼: 홈으로 이동
  * 회원가입 페이지 
    1. 이름, 아이디, 비밀번호, 학년 설정(토글), 완료(버튼) 
    2. 홈 버튼: 홈으로 이동
  * 기초학습 및 심화학습 페이지
    1. 사이드바: 원하는 차시 선택시 해당 차시 콘텐츠로 전환 가능
    2. 콘텐츠: 콘텐츠를 나타냄
    3. 홈 버튼: 홈으로 이동
    4. 페이지 이동 버튼: 이전/다음 페이지 이동
    
### :four_leaf_clover: 21/07/21
  * Adobe xd로 마이페이지 제작 회원가입 완료 페이지 제작
    * 마이페이지
      1. 상단 메뉴 바: 소개, 기초학습, 심화학습, 질문하기, 마이페이지, 로그인(버튼)
      2. 프로필
      3. 차시 별 진도율: 매 차시 별 진도율 나타냄
      4. 전체 진도율: 학습 전체 진도율 나타냄
    * 회원가입 완료 페이지: 회원가입 완료 후 이 페이지를 거쳐 홈으로 이동
  * 그 외 페이지는 21/07/17의 페이지 별 구현 사항과 동일
    <details>
    <summary>전체 페이지</summary>
    <div markdown="1">       

    <img width=60%, height=40%  src="https://user-images.githubusercontent.com/79586634/126729982-fa25895f-71f9-4006-abd9-23815c2279d7.PNG"/>
  
    </div>
    </details>

### :four_leaf_clover: 21/07/24
  * Adobe xd로 마이페이지 - 내 글 목록 및 질문게시판, 질문하기 페이지 제작
  * 상단 메뉴 바 - 로그인 버튼: 로그인 시 프로필과 이름이 보이도록 수정
    * 마이페이지
      1. 상단 메뉴 바: 소개, 기초학습, 심화학습, 질문하기, 마이페이지, 로그인(버튼)
      2. 프로필
      3. 차시 별 진도율: 매 차시 별 진도율 나타냄
      4. 전체 진도율: 학습 전체 진도율 나타냄
      5. 내 글 목록: 질문게시판에 등록된 내 글 확인 가능
    * 질문게시판
      1. 상단 메뉴 바: 소개, 기초학습, 심화학습, 질문하기, 마이페이지, 로그인(버튼)
      2. 서치 박스, 서치 버튼: 게시판 내 글 검색
      3. 글 목록: 작성자 프로필, 작성자 이름, 글 제목, 작성 일시
      4. 질문하기 버튼: 질문하기 모달창 띄움
      5. 페이지 넘기는 번호
    * 질문하기(모달창)
      1. 제목 입력: 글 제목 입력
      2. 질문 입력: 질문할 내용 입력
      3. 저장하기 버튼: 질문게시판에 게시
      4. 나가기 버튼: 모달창
    <details>
    <summary>전체 페이지</summary>
    <div markdown="1">       

    <img width=60%, height=30%  src="https://user-images.githubusercontent.com/79586634/126861217-07f9d8c0-be18-4cd5-9376-aacb2a85bc23.PNG"/>
  
    </div>
    </details>
      
### :four_leaf_clover: 21/07/28
* 학습 콘텐츠 개수 설정 (1 - 3차시)
* 학습 콘텐츠 기획
* 기초학습 및 심화학습 사이드 바 변경
  * 프로필: 마이페이지에서 사용자가 설정한 프로필이 나타남
  * 목차: 1차시/ 2차시/ 3차시로 구성
  * 소통하기: 질문하기로 구성
  <details>
  <summary>전체 페이지</summary>
  <div markdown="1">       


  <img width=60%, height=30%  src="https://user-images.githubusercontent.com/79586634/127661958-9a08bdc7-5181-4b5e-bc12-67160e7f0aaf.png"/>
  
  </div>
  </details>
  
### :four_leaf_clover: 21/08/04
* Adobe XD - 최종 플로우 확인 및 수정
  * 메인페이지 디자인 수정
  * 마이페이지 - 재생 버튼: 학습 페이지로 이동
  * 질문하기 - 저장 버튼: 질문게시판 페이지로 이동
* 플러그인(Export as React Componet) 사용해 xd 파일을 React파일로 내보냄

### :four_leaf_clover: 21/08/07
* Adobe XD 요소 이름 수정
* Adobe XD 파일 HTML 파일로 내보냄
* React 렌더링 방법 학습

### :four_leaf_clover: 21/08/11
* Home 페이지 및 Signin 페이지 구현
* Signin 페이지: 리액트 함수형 컴포넌트 & Hooks 이용해 로그인 input 상태 관리
* 라우터 기능 추가
  ```
  yarn add react-router-dom
  ```
  
### :four_leaf_clover: 21/08/18
* Signup 페이지 및 Mypage 페이지 구현
* Styled Components 이용해 요소 css
 * javascript에서 css 사용 가능하게 하는 CSS-in-JS 라이브러리
 ```
 yarn install styled-components
 ```
* flexbox를 이용한 반응형 웹 디자인
  * 외부 엘리먼트에 ```display: flex;``` 적용하면 외부 엘리먼트는 flex container / 내부 엘리먼트는 flex item으로 설정한다.
  * 이후 ```flex-direction: row | column ```를 적용해 flexbox의 방향성을 결정하여 내부 엘리먼트를 배치한다.
* React Router 컴포넌트
  * Link: ```<Link>``` 컴포넌트의 ```to``` prop을 통해 이동할 경로를 지정하고, ```<Link>``` 컴포넌트 클릭시 다른 페이지로 이동한다.

### :four_leaf_clover: 21/08/27
* 로그인 시 Topbar에 나타나는 프로필: dropdown 형식으로 로그아웃/회원정보 item 나타나도록 구현
* Signin 페이지 background-image 오류 수정
* 기초학습 1차시 - 마이크로비트 소개 페이지 구현
