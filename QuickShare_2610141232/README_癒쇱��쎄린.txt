우리 반 학습 캘린더 — Android APK 빌드 프로젝트

이 압축 파일은 HTML 캘린더를 안드로이드 앱(WebView)으로 감싼 프로젝트입니다.
알림 기능은 포함하지 않았습니다. 앱 안의 일정 추가/검색 기능은 HTML 원본을 사용합니다.

APK 만드는 가장 간단한 방법(컴퓨터 필요)
1. GitHub에 로그인하고 새 저장소(repository)를 만듭니다.
2. 이 압축 파일을 풀고, 안의 파일과 폴더 전체를 저장소에 업로드합니다.
3. 저장소의 Actions 탭을 엽니다.
4. 'Build Android APK' 작업을 선택하고 'Run workflow'를 누릅니다.
5. 작업이 초록색 체크로 끝나면 실행 결과 화면 아래쪽의 Artifacts에서
   'class-learning-calendar-apk'를 다운로드합니다.
6. 다운로드한 ZIP을 풀면 app-debug.apk가 있습니다. Android 휴대폰으로 옮겨 설치하세요.

참고
- 빌드는 GitHub의 클라우드 환경에서 실행됩니다. 이 프로젝트 ZIP 자체는 APK가 아닙니다.
- APK 설치 시 Android에서 이 출처의 앱 설치 허용을 물어볼 수 있습니다.
- 일정은 앱의 로컬 WebView 저장소에 저장되므로 앱 데이터를 지우면 사라질 수 있습니다.
- 현재 버전은 알림 기능을 포함하지 않습니다.
