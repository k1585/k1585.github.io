# FORMDOT.

**아이디어를 형태로.** 3D 모델링부터 프린팅까지, 당신의 아이디어를 현실로 구현합니다.

사이트: https://k1585.github.io/

## 파일

| 파일 | 내용 |
|---|---|
| `index.html` | 사이트 전체 (주문·견적·관리자 화면). 이 파일 하나로 동작해요. |
| `firebase-rules.json` | Firebase Realtime Database 보안규칙 (콘솔 › Realtime Database › 규칙에 붙여넣고 게시) |

## 설정값 (index.html 위쪽 `<script>` 안)

- `SMARTSTORE_URL` 스마트스토어 주소
- `FIREBASE_CONFIG` Firebase 연결 정보
- `ADMIN_EMAIL`, `ADMIN_PW_SUFFIX` 관리자 계정 (비밀번호 = 4자리 + 접미사)
- `NTFY_TOPIC` 주문 알림을 받을 ntfy 채널 이름
- `FILAMENT_PRICE`, `PRINT_PRICE`, `DESIGN_FEE`, `STUDENT_RATE` 가격 기준

## 관리자

화면 맨 위 FORMDOT. 로고나 스마트스토어 버튼을 3초 이상 누르고 4자리 입력. 주소 끝에 `#admin`을 붙여 열어도 돼요.

## 사이트 문구 · 하단 정보

관리자 › 사이트 문구에서 시작 화면의 모든 문구(서비스 소개, 이용 방법, 재료 소개, FAQ 등)를 바꿀 수 있어요.
**하단 정보 › `footer.biz`** 칸에 상호·대표자·사업자등록번호·주소 등을 적으면 사이트 맨 아래에 표시돼요 (비워 두면 숨김).

## 디자인 구조

`index.html`의 `<style>`은 번호 붙은 15개 구역(토큰 → 기본 → 버튼 → … → 반응형)으로 정리되어 있어요.
색상·모서리·글꼴은 맨 위 `:root` 토큰만 바꾸면 사이트 전체에 적용돼요.
