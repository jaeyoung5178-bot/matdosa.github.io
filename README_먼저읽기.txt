맛도사 홈페이지 — 깃허브 업로드 안내
=====================================

[이 폴더의 파일]
 ● index.html                  ← 메인 (스튜디오+지도+콘텐츠성과+탭). 주소의 첫 화면
 ● 맛도사_포트폴리오.html        ← index의 '포트폴리오' 탭이 불러옴 (필수)
 ● 맛도사_카페탐방_허브.html      ← index의 '탐방 허브' 탭이 불러옴 (필수)
 ● 맛도사_명함_인쇄시안.html      ← 명함(독립, 인쇄용). 없어도 사이트는 작동
 ● 맛도사_로고_full.png / _mark.png ← 로고 원본(보관용). 사이트엔 이미 박혀 있음

  ※ index.html 만 올리면 포트폴리오·허브 탭이 빈 화면이 됩니다.
    반드시 위 3개(.html)를 같은 폴더에 함께 올리세요.


[A. 깃허브에 올리기 — 명령어 없이 웹에서]
 1) github.com 로그인 → 우상단 '+' → New repository
 2) Repository name 칸에  아이디.github.io   형식으로 입력
    (예: 깃허브 아이디가 matdosa라면 → matdosa.github.io)
    · Public 선택 → Create repository
 3) 만들어진 저장소 화면에서  'uploading an existing file' 클릭
    (또는 Add file → Upload files)
 4) 이 폴더 안의 파일들을 전부 끌어다 놓기(드래그&드롭)
    · index, 포트폴리오, 허브, (명함, 로고) 한꺼번에
 5) 아래 'Commit changes' 초록 버튼 클릭
 6) 1~2분 뒤 접속:   https://아이디.github.io
    (예: https://matdosa.github.io)


[B. 네이버 지도 켜기 — 키 등록]
 1) index.html 을 열어 맨 위쪽
       const NAVER_CLIENT_ID = "";
    의 따옴표 안에 받아둔 네이버 클라우드 Client ID를 붙여넣고 저장
    → 그 파일을 다시 업로드(같은 방법, 덮어쓰기)
 2) 네이버 클라우드 콘솔 → Maps → Web 서비스 URL 에 아래 등록:
       https://아이디.github.io
       http://localhost   (내 PC 테스트용)
 3) 그러면 '장소 플래너'에 네이버 지도가 뜨고,
    장소 추가 시 [좌표 자동] 버튼으로 주소→좌표가 자동 입력됩니다.


[C. 콘텐츠 성과 최신화]
 · 클로드에게 "인스타 최신 성과 CSV로 줘" 라고 요청 → 받은 CSV를
   콘텐츠 성과 화면의 [CSV 가져오기]에 붙여넣으면 표가 갱신됩니다.


[D. 나중에 도메인(matdosa.com) 연결 시]
 · 저장소 Settings → Pages → Custom domain 에 matdosa.com 입력
 · 네이버 Web 서비스 URL 에도 https://matdosa.com 추가
