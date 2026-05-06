# 💵 Moni(가계부 앱)

## 프로젝트 구조

```
가계부앱/
├── src/              # 소스 코드
│   └── index.html    # 메인 앱 파일
├── assets/           # 이미지, 아이콘 등 리소스
├── docs/             # 기획서, 가이드 문서
├── backup/           # 버전별 백업 파일
└── README.md         # 프로젝트 설명
```

## 사용 방법

### 아이폰에서 앱처럼 사용하기
1. `src/index.html` 파일을 아이폰으로 전송
2. 파일 앱 → 파일 탭 → 공유 버튼 → Safari에서 열기
3. Safari 하단 공유 버튼 → 홈 화면에 추가

### 웹 배포 (권장)
- Netlify Drop: https://app.netlify.com/drop
- `src/index.html` 파일을 드래그앤드롭 → URL 즉시 생성

## 주요 기능
- 수입 / 지출 내역 추가, 수정, 삭제
- 카테고리별 차트 (도넛 차트 + 비중 테이블)
- 1월~12월 월별 수입/지출 추이
- 예산 설정 및 초과 알림
- 자산 관리 (주식, 배당금, 현금/예금)
- 커스텀 카테고리 추가
- 데이터 자동 저장 (localStorage)

## 버전 관리
| 날짜 | 파일명 | 변경사항 |
|------|--------|----------|
| $(date +%Y-%m-%d) | 가계부_$(date +%Y%m%d).html | 최초 배포 버전 |

## 기술 스택
- HTML5 / CSS3 / Vanilla JS
- Chart.js 4.4.0
- Google Fonts (Nanum Gothic)
