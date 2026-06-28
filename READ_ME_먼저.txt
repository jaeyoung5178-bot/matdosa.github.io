맛도사 — 풀스크린 개편본 (포트폴리오=첫 화면 + 매거진 전환 + 앱아이콘 + 클라우드)
================================================================================
[새 구조 — iframe(화면 속 화면) 완전히 제거, 세 화면 풀스크린]
 • index.html  = 첫 화면. "공개 포트폴리오"가 풀스크린으로 보임(망고빙수 새 사진).
                 로고(맛도사) 또는 우측 "워크스페이스 →"를 누르면 → app.html
 • app.html    = 워크스페이스(관리). 좌하단
                 "공개 포트폴리오 →"  → index.html  (매거진 전환)
                 "카페 탐방 허브 →"   → hub.html    (매거진 전환)
                 ※ 파이어베이스·네이버 지도·콘텐츠 성과·PWA는 여기에 있음
 • hub.html    = 카페 탐방 허브 풀스크린. 로고를 누르면 → app.html
 • card.html   = 명함(독립, 인쇄용)

 전환 효과: 크림색 종이가 부드럽게 넘어가며 페이지가 가라앉듯 페이드인되는
           "고급 잡지" 스타일(과한 3D 책장넘김 X). 모션 최소화 설정 시 자동 비활성.

[올리는 법 — 전부 덮어쓰기]
 1) 깃허브 저장소(matdosa.github.io) → Code → Add file → Upload files
 2) 이 폴더 안 파일 "전부"(html + png 아이콘 + manifest) 끌어다 놓기
 3) Commit changes → 1~2분 뒤 시크릿창으로 확인
   접속 첫 화면이 포트폴리오(망고빙수)면 성공. 로고 누르면 워크스페이스로 넘어감.

[앱으로 추가 — 첫 화면이 포트폴리오로 열림]
 • 아이폰(사파리): 공유 → 홈 화면에 추가
 • 안드로이드(크롬): ⋮ → 홈 화면에 추가/앱 설치
 (https 주소에서 해야 핀 아이콘이 떠요)

[파이어베이스 규칙] Realtime Database → 규칙:
   { "rules": { ".read": true, ".write": true } } → 게시(Publish)
[네이버 지도] app.html 상단 NAVER_CLIENT_ID="" 에 키 넣고 app.html만 재업로드.

[파일 목록]
 index.html / app.html / hub.html / card.html
 manifest.webmanifest / icon-192.png / icon-512.png / icon-180.png / icon-maskable-512.png
 logo_full.png / logo_mark.png
