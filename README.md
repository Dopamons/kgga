# KGGA 홈페이지 개편 목업 — 배포 세트

한국괌골프협회(KGGA) 홈페이지 개편안 목업입니다. 정적 HTML이라 GitHub Pages에 그대로 올리면 됩니다.

## 파일 구성
| 파일 | 페이지 |
|---|---|
| `index.html` | 홈 (첫 화면) |
| `golf.html` | 골프장 상세 (5개 코스 탭·스펙·편의시설·가로 갤러리) |
| `hotels.html` | 골프 연계 호텔 12곳 (PHR CCP 할인) |
| `weather.html` | 괌 날씨 (라운딩 지수·16일 예보) |
| `about.html` | 협회 소개 (활동·임원·운영사무국) |
| `qna.html` | QnA (자주 묻는 질문) |

모든 페이지 상단 메뉴로 서로 연결됩니다. 사진은 HTML에 내장(base64)되어 별도 이미지 폴더가 필요 없습니다.

## GitHub Pages 올리는 법
1. 저장소(예: `kgga`)에 이 폴더 안의 파일들을 업로드 (폴더째 말고 파일만).
2. Settings → Pages → Source: `main` 브랜치, `/ (root)` → Save.
3. `https://<아이디>.github.io/kgga/` 접속. `index.html`이 첫 화면.

## 실서버 반영 전 교체할 것
- 실촬영 고화질 사진 (현재는 가이드북 PDF 추출본). 웨스틴·하얏트·크라운은 저해상도라 공식 사진 권장.
- 프로모션 가격·예약 링크 파라미터(`/guamfree/golf/?strGolf=...&intSeq=...`) 실판매 기준 확정.
- 푸터·상단바 사업자/전화(현재 1234-5678 placeholder) 실제 값.

ⓒ 한국괌골프협회(KGGA) · 개편 목업
