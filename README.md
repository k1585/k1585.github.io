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

FORMDOT. 로고나 스마트스토어 버튼을 3초 이상 누르고 4자리 입력. 주소 끝에 `#admin`을 붙여 열어도 돼요.
