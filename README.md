# jesusbloodchurch

실제 운영 중인 성혈교회 홈페이지 프로젝트

## 프로젝트 배경
친한 친구가 담임목사로 있는 작은 교회의 홈페이지가 없어 제작하게 되었습니다.
교회의 비전, 예배 시간, 위치 안내 등 교회 정보를 편리하게 제공하기 위해 개발되었습니다.

## 기술 스택
- Backend: Spring Boot <a href="https://spring.io/projects/spring-boot"><img src="https://cdn.simpleicons.org/springboot/6DB33F" width="15" height="15"></a>
- Frontend: Thymeleaf <a href="https://www.thymeleaf.org/"><img src="https://cdn.simpleicons.org/thymeleaf/005F0F" width="15" height="15"></a>
- Database: PostgreSQL <a href="https://www.postgresql.org/"><img src="https://cdn.simpleicons.org/postgresql/4169E1" width="15" height="15"></a>, JPA(Hibernate) <a href="https://hibernate.org/"><img src="https://cdn.simpleicons.org/hibernate/59666C" width="15" height="15"></a>
- Styling: Tailwind CSS <a href="https://tailwindcss.com/"><img src="https://cdn.simpleicons.org/tailwindcss/06B6D4" width="15" height="15"></a>
- Build Tool: Gradle <a href="https://gradle.org/"><img src="https://cdn.simpleicons.org/gradle/02303A" width="15" height="15"></a>
- Testing: JUnit <a href="https://junit.org/junit5/"><img src="https://cdn.simpleicons.org/junit5/25A162" width="15" height="15"></a>

## 운영 환경
- Server: AWS EC2 <a href="https://aws.amazon.com/ec2/"><img src="https://cdn.simpleicons.org/icloud/3693F3" width="15" height="15"></a> (t4g.micro)
- Web Server: NGINX <a href="https://nginx.org/"><img src="https://cdn.simpleicons.org/nginx/009639" width="15" height="15"></a> (Reverse Proxy)
- SSL: Cloudflare <a href="https://www.cloudflare.com/"><img src="https://cdn.simpleicons.org/cloudflare/F38020" width="15" height="15"></a>, Let's Encrypt <a href="https://letsencrypt.org/"><img src="https://cdn.simpleicons.org/letsencrypt/003A70" width="15" height="15"></a>
- DNS / CDN: Cloudflare <a href="https://www.cloudflare.com/"><img src="https://cdn.simpleicons.org/cloudflare/F38020" width="15" height="15"></a>
- Captcha: Cloudflare Turnstile <a href="https://www.cloudflare.com/"><img src="https://cdn.simpleicons.org/cloudflare/F38020" width="15" height="15"></a>
- Storage: AWS S3 <a href="https://aws.amazon.com/s3/"><img src="https://cdn.simpleicons.org/icloud/3693F3" width="15" height="15"></a>
- External API: Naver Maps API <a href="https://www.ncloud.com/v2/product/applicationService/maps"><img src="https://cdn.simpleicons.org/googlemaps/03C75A" width="15" height="15"></a>, OpenWeatherMap API <a href="https://openweathermap.org/"><img src="https://cdn.simpleicons.org/accuweather/FF6600" width="15" height="15"></a>
- Authentication: Spring Security <a href="https://spring.io/projects/spring-security"><img src="https://cdn.simpleicons.org/springsecurity/6DB33F" width="15" height="15"></a>, OAuth 2.0 <a href="https://developers.kakao.com/docs/latest/ko/kakaologin/common"><img src="https://cdn.simpleicons.org/kakaotalk/FFCD00" width="15" height="15"></a>
- Database Hosting: Neon DB <a href="https://neon.tech/"><img src="https://cdn.simpleicons.org/lightning/00E599" width="15" height="15"></a>
- Email Hosting: Zoho Mail <a href="https://www.zoho.com/mail/"><img src="https://cdn.simpleicons.org/zoho/ED1C24" width="20" height="20"></a>
- Domain: Gabia
- API Documentation: Swagger UI <a href="https://swagger.io/tools/swagger-ui/"><img src="https://cdn.simpleicons.org/swagger/85EA2D" width="15" height="15"></a> (OpenAPI 3.0)
- Logging: Logback
- Monitoring: Grafana <a href="https://grafana.com/"><img src="https://cdn.simpleicons.org/grafana/F46800" width="15" height="15"></a>

## 배포
- 실제 운영 사이트: [https://www.jesusbloodchurch.org](https://www.jesusbloodchurch.org)

## 주요 기능

### ⛪ 사용자 기능
- ✅ 오늘의 성경 구절
- ✅ 오늘의 날씨 (OpenWeatherMap API)
- ✅ 교회 비전 화면
- ✅ 담임목사 인사말 화면
- ✅ 교역자 소개 화면
- ✅ 예배 안내
- ✅ 오시는길 화면 (Naver Maps API)
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
- ✅ 로그인 화면 (Cloudflare Turnstile)
- ✅ 소셜로그인 기능 (Kakao OAuth 2.0)
- ✅ 관리자용 화면

### ⚙️ 운영 및 인프라
- ✅ Spring Boot JAR를 systemd 서비스로 관리
- ✅ NGINX Reverse Proxy 구성
- ✅ Cloudflare 기반 DNS / CDN / SSL 구성
- ✅ NGINX에 Let's Encrypt 기반 SSL 인증서 설치 (HTTPS 적용)
- ✅ 서버 로그 자동 로테이션 (Shell Script)
- ✅ Swagger (OpenAPI 3.0) 기반 API 문서화
- ✅ Grafana Cloud 기반 모니터링 대시보드 구축
- ✅ GitHub Actions 기반 CI/CD 파이프라인 구축
- ✅ Terraform 기반 IaC 구축 및 AWS 인프라 관리

### ⏳ 개발 예정 기능
- ⏳ 챗봇 기능
- ⏳ 온라인 신학교
