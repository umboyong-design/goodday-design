# 좋은날 디자인 | GOODDAY DESIGN

좋은날 디자인의 간판 디자인·시공 서비스 홈페이지 데모입니다.

## 홈페이지
- `index.html`: 회사 로고와 콘셉트 이미지가 포함된 단일 정적 웹페이지
- 간판 종류/시공사례 콘셉트, 간판 문구 및 색상 미리보기, PNG 저장
- 간편 참고 견적 계산, FAQ 안내 챗봇

> 실제 시공사진이 아닌 이미지에는 콘셉트 샘플임을 표시했습니다. 견적은 참고용이며 카카오톡 실제 채널·고객DB 자동접수는 아직 연결되지 않았습니다.

## GitHub Pages 배포
1. 저장소 **Settings → Pages**로 이동
2. **Build and deployment → Source → GitHub Actions** 선택
3. **Actions**에서 `Deploy Goodday Design Website` 작업 성공 확인
4. 공개 주소: https://umboyong-design.github.io/goodday-design/

`main` 브랜치에 새 커밋이 올라오면 `.github/workflows/deploy.yml`이 정적 사이트 배포를 자동 시도합니다.

## 정식 운영 전 설정
- 실제 시공사례 사진과 소개 내용 교체
- 실제 업체 연락처, 사업자 정보, 운영 견적 단가 확정
- 카카오톡 채널 URL/챗봇 및 고객 요청사항 스프레드시트 연동
- 개인정보 수집·이용 동의와 접수 보안 정책 마련
