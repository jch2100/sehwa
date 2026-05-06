# Sehwa Branding Webpage

예술심리치료사 조세화의 기업/기관 담당자 대상 개인 브랜딩 웹페이지 초안입니다.

## 구성

- `index.html`: 정적 웹페이지
- `styles.css`: 반응형 스타일
- `assets/`: 블로그에서 다운로드한 로컬 이미지
- `brand-report.md`: 브랜딩 분석 리포트
- `content-inventory.md`: 블로그 콘텐츠 인벤토리
- `design-brief.md`: 디자인 브리프
- `page-spec.md`: 구현 설계서

## 로컬 실행

```bash
python -m http.server 5178
```

브라우저에서 `http://127.0.0.1:5178`을 엽니다.

## 이미지 정책

웹페이지는 외부 블로그 이미지 URL을 직접 참조하지 않고 `assets/` 폴더의 로컬 이미지 파일을 사용합니다.
최종 공개 전 블로그 이미지의 사용 권한과 출처 표기 정책을 확인해야 합니다.
