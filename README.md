# LFAI AI KIT — 온디바이스 AI 키트 (소상공인 · 실버)

`carusworks-SMOS`의 쌍둥이 래퍼. 같은 디자인·같은 엔진, **두 가지 판**.

## 두 트랙

| 트랙 | 모듈 5개 | 결제자 |
|---|---|---|
| **소상공인** | 홍보 영상 · SNS · 디자인·메뉴판 · 고객 응대 · 장부·매출 | 사장님 |
| **실버** | 복약·병원 · 가족 연락 · 말로 쓰는 일지 · 행정·금융 · 지출 리포트 | **자녀·지자체** |

- 히어로 오른쪽 시뮬레이터에서 **소상공인/실버 토글**로 모듈이 바뀝니다 (실제 동작).
- 하단 라인업: LFAI · LFAI AI KIT · carusworks.

## 협업 표기
- 구축·설치·운영 = **동선 파트너**
- 엔진·모듈·표준 = LFAI

## 로컬 미리보기
```bash
cd ~/lfai-aikit
python3 -m http.server 8899
# http://127.0.0.1:8899/
```

## 배포 (GitHub Pages)
```bash
cd ~/lfai-aikit
git init && git add -A && git commit -m "feat: LFAI AI KIT — 소상공인/실버 투트랙 래퍼"
git remote add origin https://github.com/dimas-40/lfai-aikit.git
git branch -M main && git push -u origin main
# Settings → Pages → Deploy from branch: main / (root)
```
→ `https://dimas-40.github.io/lfai-aikit/`

## 파일
```
index.html          랜딩 (hero · 두 판 · 시뮬레이터 · 확인사항 · 라인업)
assets/p.css,p.js   제품 라인 공통 (SMOS에서 복사)
assets/hero.jpg,... 히어로 이미지
.nojekyll           Pages Jekyll 비활성
```

## 문의 연결
- 상담 CTA → `https://carusworks.com/contact/` (그대로)
- 실버는 상담 폼에 "실버" 표기 권장
