# dgWebSample

# VS에서 git 에서 열고 새로 고치기

## GitHub 리포지토리 클론
VS Code에서 GitHub 리포지토리를 클론하여 동기화하려면 다음 단계를 따르세요:

### 3.1. 리포지토리 URL 복사
GitHub에서 원하는 리포지토리의 Clone or Download 버튼을 클릭하고, HTTPS 또는 SSH URL을 복사합니다.

### 3.2. VS Code에서 리포지토리 클론
VS Code에서 리포지토리 클론:

Ctrl+Shift+P (Windows/Linux) 또는 Cmd+Shift+P (Mac)을 눌러 Command Palette를 엽니다.
"Git: Clone"을 검색하고 선택합니다.
클론하려는 리포지토리의 URL을 입력하거나 붙여넣고, 로컬 디렉터리를 선택하여 클론합니다.
리포지토리 열기: 리포지토리가 클론되면 VS Code에서 해당 폴더가 열리며 GitHub 리포지토리가 VS Code와 연결됩니다.

### 4. 변경 사항 커밋 및 푸시
### 4.1. 변경 사항 확인
VS Code에서 GitHub 리포지토리를 연 후, 소스 제어 (Source Control) 아이콘을 클릭하면 Git의 변경 사항을 확인할 수 있습니다. 파일을 수정한 후, 변경 사항이 표시됩니다.

4.2. 커밋
변경 사항을 커밋하려면 소스 제어 패널에서 "+" 아이콘을 클릭하여 변경된 파일을 스테이징합니다.
커밋 메시지를 입력하고 ✔ 아이콘을 클릭하여 커밋합니다.
4.3. 푸시
커밋 후, 세로 점 3개 아이콘 (소스 제어 상단에 있음)을 클릭하고 Push를 선택하여 원격 리포지토리에 변경 사항을 푸시합니다.
GitHub에 푸시된 변경 사항을 확인하려면 GitHub 웹 사이트에서 리포지토리를 새로 고침하세요.
5. 풀(Pull) 작업
원격 리포지토리에서 최신 변경 사항을 가져오려면 풀 작업을 수행해야 합니다.

5.1. 풀
세로 점 3개 아이콘을 클릭하고 Pull을 선택하여 GitHub에서 최신 커밋을 가져옵니다.
변경 사항을 로컬 리포지토리에 병합하여 최신 상태를 유지합니다.
6. 새로운 리포지토리 만들기
6.1. 새로운 Git 리포지토리 만들기
VS Code에서 새로운 프로젝트 폴더를 만듭니다.
폴더를 열고, 소스 제어에서 Git: Initialize Repository를 선택하여 새로운 Git 리포지토리를 초기화합니다.
6.2. GitHub에 새로운 리포지토리 업로드
GitHub에서 새 리포지토리를 생성합니다.
새 리포지토리를 생성한 후, VS Code에서 GitHub 리포지토리와 연결합니다.
터미널에서 아래 명령어를 사용하여 리모트 리포지토리를 추가합니다:
bash
코드 복사
git remote add origin https://github.com/username/repository-name.git
변경 사항을 커밋하고 푸시하여 새 리포지토리를 GitHub에 업로드합니다.
7. GitHub 리포지토리와 동기화하는 팁
자동으로 변경 사항 커밋: VS Code는 자동으로 변경 사항을 추적하고, 수동으로 커밋을 만들어야 하지만, 설정을 통해 자동화할 수 있습니다.
충돌 해결: 여러 개발자가 작업할 때는 Git 충돌이 발생할 수 있습니다. 충돌을 해결하려면 Source Control에서 해당 파일을 열고 충돌을 수동으로 해결해야 합니다.
GitHub Extensions 사용: GitHub Pull Requests and Issues 확장을 설치하여 GitHub에서 직접 풀 리퀘스트를 만들거나 이슈를 관리할 수 있습니다.