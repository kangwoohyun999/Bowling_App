# 🎳 BowlTrack — 볼링 기록 웹앱

## 서버 접속
```
https://bowl-track-bay.vercel.app/login
```
---

## 파일 구조
```
bowling_app/
├── app.py              # Flask 서버 (백엔드)
├── data.json           # 자동 생성되는 사용자 데이터 파일
├── requirements.txt
└── templates/
    ├── base.html       # 공통 레이아웃 (상단바, 하단 네비게이션)
    ├── login.html      # 로그인 페이지
    ├── register.html   # 회원가입 페이지
    ├── home.html       # 홈 (3개 메뉴 박스)
    ├── calendar.html   # 볼링 점수 달력 기록
    ├── stats.html      # 투구 통계 (스트라이크/스페어/미스 확률)
    ├── info.html       # 볼링 정보 (쇼핑몰, 구질별 장단점, 팁)
    ├── profile.html    # 프로필 설정
    └── settings.html   # 앱 설정 (구질 선택, 다크모드)
```

## 기능
- ✅ 로그인 / 회원가입
- ✅ 홈 화면: 구질 배지, 3가지 메뉴 박스
- ✅ 달력 점수 기록: 날짜별 점수 + 스트라이크/스페어/미스 횟수 + 메모
- ✅ 투구 통계: 도넛 차트 + 확률 바
- ✅ 볼링 정보: 쇼핑몰 링크, 구질별 장단점, 꿀팁
- ✅ 프로필: 닉네임 / 상태메시지 편집, 로그아웃
- ✅ 설정: 구질 선택, 다크모드 전환
