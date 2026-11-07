# 호재 레이더 · Android 개인용 설치 파일

## 휴대폰에서 설치

**[안드로이드 APK 다운로드](https://github.com/vencent10004-droid/good-news-downloads/releases/latest/download/good-news-radar.apk)**

1. 휴대폰에서 위 링크를 누릅니다. 카카오톡에서 다운로드가 안 되면 Chrome으로 엽니다.
2. 다운로드한 `good-news-radar.apk`를 눌러 설치합니다. 필요한 경우 Android 화면 안내에서 해당 브라우저·파일 앱의 설치 권한을 확인합니다.
3. 앱의 **PC 없이 · 휴대폰 단독 수집 설정**에서 본인 한국투자 실전 APP KEY와 APP SECRET을 직접 입력합니다. 이 저장소·이슈·채팅에 키를 올리지 마세요.
4. PC 수집기를 종료한 뒤 휴대폰 수집을 시작하고 알림을 허용합니다.
5. 앱 설정의 **10초 후 테스트 알림 보내기**를 누른 뒤 화면을 잠가 수신을 확인합니다.

## 동작 범위

휴대폰이 한국투자 뉴스 API를 직접 조회하며 새로고침·로컬 알림을 제공합니다. 이 모드에는 PC·클라우드·Firebase가 필요 없습니다. DART·네이버의 별도 직접 수집은 포함하지 않습니다.

**Android 15 이상은 dataSync 포그라운드 서비스의 백그라운드 실행을 24시간 중 합계 6시간으로 제한합니다.** 휴대폰 전원만 켜 둔다고 화면을 끈 채 24시간 연속 수집이 보장되지는 않습니다. 제한에 도달하면 앱을 열고 수집을 다시 시작해야 합니다. 절전·네트워크·공급사 반영 지연도 영향을 줍니다. [Android 공식 실행 제한](https://developer.android.com/develop/background-work/services/fgs/timeout).

제목 규칙으로 분류한 호재 후보이며 매수 신호·수익 보장이 아닙니다. 원문과 발행 시각을 확인하세요. 이 APK는 개인용 개발 서명 파일이며 Google Play 배포 앱이 아닙니다. 실제 휴대폰의 API 인증·화면 잠금 수신·장시간 실행 검증은 아직 수행하지 않았습니다.

## 파일 확인

- 버전: 1.1.0 (versionCode 4)
- 파일 크기: 3,534,741 bytes
- SHA-256: `3094615729dbc19dddca9ba8f84beb2d5b0c36bbb191ebfbc65ea3e557bb9dd6`
- 실제 증권 API 키·시크릿·기기 토큰은 APK에 포함하지 않습니다.

이 저장소에는 설치 안내와 APK 배포 파일만 게시합니다. 소스·개인 DB·API 설정 파일은 올리지 않습니다.
