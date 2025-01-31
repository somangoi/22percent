# 에잇퍼센트를 모티브로 한 팀 프로젝트

## 프로젝트 소개
에잇퍼센트란, 대출형 크라우드 펀딩 스타트업으로 P2P 금융 서비스를 제공하는 기업이다.
에잇퍼센트의 금융 데이터 시각화 기능을 모티브로 진행한 프로젝트이다.

- 프론트엔드 github 링크
- 백엔드 github 링크

## 개발 인원 및 기간
- 개발기간: 2021/7/19 ~ 2021/7/30
- 개발인원: 프론트엔드 3명, 백엔드 3명
- 프론트엔드: 장운서, 정빛열음, 황소미
- 백엔드: 이동명, 이준영, 전수현

## 프로젝트 선정 이유
- 복잡한 데이터를 필요에 맞게 가공하는 연습이 가능했음
- 슬라이드, 페이지네이션, 검색, 필터링과 같은 웹 사이트에서 자주 사용되는 기능들을 다양하게 경험해 볼 수 있음
- 일반적인 커머스 사이트와는 다른 플로우를 경험할 수 있음

## 적용 기술 및 구현 기능

### 적용 기술
- Frontend: React.js, Styled-Components, Hooks
                Kakao Map API, Kakao Login API, Chart.js
- Backend: Python, Django, MySQL, Bcrypt, pyJWT
- Common: POSTMAN, Notion

### 전체 구현 기능
#### 메인페이지
슬라이드 무한 롤링 가능,
하나의 카드들에 hover 가 되면 이미지 스케일 커지는 모션,
css를 사용해 그래프 구현

#### 네비게이션 바
투자하기,전문투자 대출하기 로그아웃 마이페이지로 이동하는 기능 구현

#### 로그인, 회원가입
이메일 회원가입 완료,
다른페이지로가서 로그아웃을 하면 로그아웃 가능,
전체체크 기능 구현,
카카오톡을 이용한 소셜로그인 기능 구현

#### 투자하기
- 부동산: 
투자를 한 카드리스트는 체크 이미지로 표시,
더보기 버튼 클릭 시 추가 fetch
- 개인신용: 
양방향 레인지 슬라이더를 이용한 필터링 구현,
체크박스 기능 버튼 구현,
체크된 아이템이 있을 시 투자하기 버튼 노출

#### 상품 상세페이지
슬라이드 구현,
chart.js를 활용해 두가지 종류의 차트 구현,
옵션값 변경시 화면에 노출되는 데이터 변경

#### 전체 투자하기
체크박스 기능 구현,
POST method 활용,
투자하기 버튼 클릭시 id 값과 사용 예치금 서버로 전달

#### 마이페이지
- 투자요약: 
탭 이동을 통한 데이터 전환,
chart.js 를 이용한 차트 구현
- 투자내역: 
옵션 기능을 이용한 필터링 구현,
검색기능을 이용한 필터링 구현,
페이지네이션 구현

## Reference
이 프로젝트는 에잇퍼센트 사이트를 참조하여 학습 목적으로 만들었습니다.
실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
