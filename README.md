# RRC 허브 — 설정 가이드

## 📁 파일 구조

```
rrc-hub/
├── index.html       # 메인 페이지
├── faq.html         # FAQ
├── gallery.html     # 갤러리 (준비 중)
├── app.css          # 스타일
├── logo.png         # RRC 로고 (직접 추가)
└── character.png    # 로켓보이 캐릭터 (직접 추가)
```

---

## 🚀 배포 순서

### 1. 이미지 준비

- **`logo.png`** — RRC 로고 (원형, 첫 번째 이미지)
- **`character.png`** — 로켓보이 달리는 캐릭터 (두 번째 이미지)

다운받은 이미지 2개를 `logo.png`, `character.png` 이름으로 저장!

### 2. GitHub 새 repo 생성

- repo 이름: `rrc-hub` (또는 원하는 이름)
- Private 선택
- 파일 5개 전부 업로드 (이미지 포함)

### 3. Vercel 배포

- Vercel → New Project → repo 연결
- Framework: Other
- Build command: (비워두기)
- Deploy

### 4. 카테고리 링크 확인

`index.html` 안에서 다른 사이트 URL이 맞는지 확인:

- 대회: `https://rrc-race.vercel.app`
- 런럭: `https://rrc-runluck.vercel.app`
- 로또런: `https://rrc-lotto.vercel.app`

실제 배포된 URL과 다르면 `index.html` 수정 필요!

---

## ⚙️ 커스터마이징

### FAQ 수정

`faq.html` 안의 `FAQ` 배열에서 질문/답변 추가/수정 가능.

### 색상 변경

`app.css` 상단 `:root` 안의 CSS 변수 수정.

### 텍스트 수정

`index.html` 안의 텍스트 직접 수정.
