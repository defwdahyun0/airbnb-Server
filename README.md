# :star2: airbnb project
- 클라이언트 1명, 서버 2명이 개발을 진행했습니다.

### :file_folder: 디렉토리 구조
```bash
📂 config
 ├── 📄baseResponseStatus.js 
 ├── 📄database.js
 ├── 📄email.js
 ├── 📄express.js
 ├── 📄googleMap.js
 ├── 📄jwtMiddleware.js
 ├── 📄resEmail.js
 ├── 📄response.js
 ├── 📄secret.js
 ├── 📄winston.js
📂 src
 └── 📂 Chat 
      ├── 📄chatController.js
      ├── 📄chatDao.js
      ├── 📄chatProvider.js
      ├── 📄chatRoute.js
      ├── 📄chatService.js
 └── 📂 Experience 
      ├── 📄experienceController.js
      ├── 📄experienceDao.js
      ├── 📄experienceProvider.js
      ├── 📄experienceRoute.js
      ├── 📄experienceService.js
 └── 📂 Room
      ├── 📄roomController.js
      ├── 📄roomDao.js
      ├── 📄roomProvider.js
      ├── 📄roomRoute.js
      ├── 📄roomService.js
 └── 📂 Search 
      ├── 📄searchController.js
      ├── 📄searchDao.js
      ├── 📄searchProvider.js
      ├── 📄searchRoute.js
      ├── 📄searchService.js
 └── 📂 Trip 
      ├── 📄tripController.js
      ├── 📄tripDao.js
      ├── 📄tripProvider.js
      ├── 📄tripRoute.js
      ├── 📄tripService.js
 └── 📂 User 
      ├── 📄userController.js
      ├── 📄userDao.js
      ├── 📄userProvider.js
      ├── 📄userRoute.js
      ├── 📄userService.js
 └── 📂 WishList 
      ├── 📄wishListController.js
      ├── 📄wishListDao.js
      ├── 📄wishListProvider.js
      ├── 📄wishListRoute.js
      ├── 📄wishListService.js
📄 .gitignore
📄 README.md
📄 index.js
📄 package.json
📄 TemplateExplanation.md
```

### :bar_chart: ERD 설계
- AqueryTool Link: URL : https://aquerytool.com/aquerymain/index/?rurl=f17ec6fa-037e-4891-bb83-01f380b936f5&
- AqueryTool Password : m87261
- 본 ERD 설계는 실제 에어비앤비와는 무관합니다
<img src="./.images/db.png"/>

### :computer: API 개발
- API List Link : https://docs.google.com/spreadsheets/d/e/2PACX-1vSqfvTmUYXq0pSixQ-sConHUhJv21LI_1u-yWSmwc_lJGF1i3EZuF2D4bpXotoskg/pubhtml

### :exclamation: Role
- :page_with_curl: ERD 설계
- :man: 사용자 API 개발
- :woman: 소셜 로그인 API 개발
- :phone: 채팅 기능 API 개발
- :computer: AWS EC2, RDS 서버 생성 (개발에는 다른 개발자의 개인 서버를 활용)
- :pencil: Refactoring
  - 비밀번호 암호화 방법 수정 : hashed -> hashed + salt
  - 이메일 로그인 로직 수정 : DB의 salt 값 활용

### :rocket: 사용한 외부 API
- :earth_americas: node-Geocoder
- :mailbox: nodeMailer
- :phone: NCP Simple & Easy Notification Service
- :seedling: Naver Developers 네이버 로그인
- :sparkles: Kakao Developers 카카오 로그인
- :globe_with_meridians: Google Developers 구글 로그인
### :clipboard: Architecture
<img src="./.images/architecture.png"/>

### :memo: Git Logs
<img src="./.images/git.png"/>
