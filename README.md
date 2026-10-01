# BruteForceGuard releases

BruteForceGuard 의 설치 파일(`BruteForceGuard.Setup.exe`)과 업데이트 버전 정보(`latest.json`, `latest.json.sig`)를 올리는 릴리스 전용 저장소입니다.
소스 코드는 이 저장소에 없습니다.

- 설치: [Releases](../../releases/latest) 의 `BruteForceGuard.Setup.exe` 를 관리자 권한으로 실행합니다.
- 받은 설치 파일은 릴리스 설명의 SHA-256 과 대조하세요: `Get-FileHash .\BruteForceGuard.Setup.exe -Algorithm SHA256`
- `latest.json` 은 서명돼 있습니다(`latest.json.sig`). 설치된 BruteForceGuard 가 새 버전을 확인하는 데 쓰므로 편집하지 마세요.