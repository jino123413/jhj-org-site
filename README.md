# 조직 웹사이트 (Google Play 조직 인증용)

이 폴더는 Google Play 조직 계정의 웹사이트 인증을 위한 최소 정적 사이트입니다.

## 포함 파일
- `index.html`: 조직 소개/사업자 정보/문의
- `privacy.html`: 개인정보처리방침
- `terms.html`: 이용약관
- `styles.css`: 공통 스타일

## 배포 전 필수 수정
1. `nusence01@gmail.com`을 실제 운영 이메일로 변경
2. `index.html`의 JSON-LD `url` 값을 실제 사이트 URL로 변경
3. 사업자 정보 오탈자 점검

## GitHub Pages로 배포
1. 새 저장소 생성 (예: `jhj-org-site`)
2. 이 폴더 파일을 저장소 루트에 업로드
3. GitHub `Settings > Pages`
4. `Deploy from a branch` 선택
5. Branch: `main`, Folder: `/ (root)` 선택 후 저장
6. 발급된 URL 확인 (예: `https://<username>.github.io/jhj-org-site/`)

## Play Console 인증 순서
1. Search Console에 배포 URL 등록/소유권 확인
2. Play Console 계정 세부정보에 같은 URL 입력
3. 웹사이트 인증 요청 전송

중요: Search Console URL과 Play Console URL은 `https`, `www`, 경로까지 완전히 동일해야 합니다.


