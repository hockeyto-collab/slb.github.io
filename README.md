# Senior Life Business 프로필 사이트

이 프로젝트는 시니어 라이프 비즈니스 교육·강연 신청과 컨설팅 의뢰가 들어오도록 설계된 정적 웹사이트입니다.

## 파일 구조
- `index.html` – 홈(히어로 + 서비스 요약)
- `about.html` – 소개/프로필/비전
- `services.html` – 서비스 상세
- `contact.html` – 문의(메일to: hockeyto@gmail.com)
- `style.css` – 전역 스타일
- `images/hero.png` – 히어로 배경 이미지

## 배포 (GitHub Pages 예시)
1. 새 저장소 생성 후, 위 파일을 루트에 업로드
2. Settings → Pages → `Deploy from a branch` → `main` / `/ (root)` 선택
3. 배포 URL 접속 (CNAME으로 커스텀 도메인 연결 가능)

## 커스터마이징
- 메타태그/OG 이미지 수정 → 각 HTML `<head>`
- 폰트: Google Fonts 추가 가능
- 분석: GA4 스니펫 삽입
- 폼 백엔드: Formspree 등 서버리스 서비스로 교체 가능
