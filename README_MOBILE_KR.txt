[중요] GitHub 모바일 업로드용 Vela Chat

1. 이 ZIP 안의 파일을 GitHub 저장소 main 브랜치에 업로드하세요.
2. 반드시 .github/workflows/android-apk.yml 파일이 포함되어 있어야 합니다.
3. GitHub -> Actions -> Build Vela Chat APK -> Run workflow를 누르세요.
4. 완료되면 Artifacts의 Vela-Chat-APK에서 APK를 받습니다.

API: OpenRouter 무료 라우터(openrouter/free)를 사용합니다. 무료 라우터도 OpenRouter API Key가 필요합니다.
유저노트/추가규칙은 system context로 전달됩니다.
출력 토큰과 추론량은 요청에 반영됩니다.
요약 메모리는 설정한 10/15/20턴마다 자동 생성됩니다.
