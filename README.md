# jesusbloodchurch

실제 운영 중인 성혈교회 홈페이지 프로젝트

## 프로젝트 배경
친한 친구가 담임목사로 있는 작은 교회의 홈페이지가 없어 제작하게 되었습니다.
교회의 비전, 예배 시간, 위치 안내 등 교회 정보를 편리하게 제공하기 위해 개발되었습니다.

## 기술 스택
- Backend: Spring Boot
- Frontend: Thymeleaf, Tailwind CSS
- Database: PostgreSQL, JPA
- Build Tool: Gradle
- Testing: JUnit 5, Spring Boot Test

## 운영 환경
- Server: AWS EC2 (t4g.micro)
- Web Server: NGINX (Reverse Proxy)
- SSL: Let's Encrypt
- DNS / CDN / Security: Cloudflare Full (strict)
- Captcha: Cloudflare Turnstile
- Storage: AWS S3
- External API: Naver Maps API, OpenWeatherMap API
- Authentication: Spring Security
- Database Hosting: Neon DB
- Email Hosting: Zoho Mail
- Domain: Gabia

## 배포
- 실제 운영 사이트: [https://www.jesusbloodchurch.org](https://www.jesusbloodchurch.org)

## 주요 기능

### ✅ 현재 구현된 기능
- ✅ 오늘의 성경 구절
- ✅ 오늘의 날씨
- ✅ 교회 비전 화면
- ✅ 담임목사 인사말 화면
- ✅ 교역자 소개 화면
- ✅ 예배 안내
- ✅ 오시는길 화면
- ✅ 헌금 안내 화면
- ✅ 설교 게시판
- ✅ 강연 게시판
- ✅ 주보 게시판
- ✅ 교우소식 게시판
- ✅ 기도요청 화면
- ✅ 공지사항 게시판
- ✅ 입교 안내 화면
- ✅ 금요 성경공부 화면
- ✅ 신학스터디 안내 화면

### ⏳ 개발 예정 기능
- ⏳ 배포 자동화
- ⏳ Swagger 기반 API 문서화
- ⏳ 챗봇 기능
- ⏳ 관리자 화면
- ⏳ 온라인 신학교
