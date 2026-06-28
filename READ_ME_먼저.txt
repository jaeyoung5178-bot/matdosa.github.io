맛도사 홈페이지 — 클라우드 저장 + 앱 아이콘(PWA) 최종본
======================================================
이 폴더 파일 "전부"를 깃허브에 올리세요(아이콘 png와 manifest 포함).

[파일]
 index.html            ← 메인
 portfolio.html        ← 포트폴리오 탭
 hub.html              ← 카페 탐방 허브 탭
 card.html             ← 명함(독립)
 manifest.webmanifest  ← 앱 정보(아이콘 연결)  ★꼭 같이 올리기
 icon-192.png / icon-512.png / icon-180.png / icon-maskable-512.png ← 앱 아이콘 ★꼭 같이
 logo_full.png / logo_mark.png ← 로고 원본(보관용)

[올리는 법]
 1) 깃허브 저장소 → Code → Add file → Upload files
 2) 이 폴더 안 파일 "전부" 끌어다 놓기 (index.html 등 덮어쓰기)
 3) Commit changes → 1~2분 뒤 시크릿창에서 확인

[휴대폰에 앱 아이콘으로 추가하는 법]
 ● 아이폰(사파리): 사이트 열기 → 하단 '공유' 버튼 → '홈 화면에 추가'
    → 맛도사 핀 아이콘으로 추가됨
 ● 안드로이드(크롬): 사이트 열기 → 우상단 ⋮ → '홈 화면에 추가' / '앱 설치'
    → 맛도사 핀 아이콘으로 추가됨
 ※ 반드시 https 주소(github.io)에서 해야 아이콘이 떠요. 한번 추가 후
   아이콘이 옛것이면, 추가된 아이콘 지우고 캐시 비운 뒤 다시 추가.

[파이어베이스 규칙] Realtime Database → 규칙:
   { "rules": { ".read": true, ".write": true } }  → 게시(Publish)
[네이버 지도] index.html 상단 NAVER_CLIENT_ID="" 에 키 넣고 재업로드.
