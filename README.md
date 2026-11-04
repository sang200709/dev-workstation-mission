


@'
# Dev Workstation Mission

## 1. CLI 명령어 실습

사용한 명령어:

pwd
dir
dir -Force
mkdir dev-workstation-mission
cd dev-workstation-mission
pwd

설명:

현재 위치 확인
파일과 폴더 목록 확인
숨김 파일 포함 목록 확인
작업 폴더 생성
작업 폴더로 이동
2. Git 설정 및 사용
사용한 명령어:

powershell

git init
git status
git add README.md
git commit -m "docs: add README"
Git 저장소를 초기화하고 README 파일을 커밋했습니다.

3. GitHub 원격 저장소 연결
GitHub 저장소 주소:


https://github.com/sang200709/dev-workstation-mission.git
사용한 명령어:

powershell

git remote -v
git push -u origin main
4. Docker 확인
사용한 명령어:

powershell

docker --version
Docker 설치 여부를 확인했습니다.

5. 실행 권한 테스트
파일:



permission-test.sh
확인 명령어:

powershell

git ls-files --stage permission-test.sh
결과:


100755 permission-test.sh
100755는 Git에서 실행 권한이 있는 파일로 추적된다는 뜻입니다.

6. 최종 상태 확인
사용한 명령어:

powershell

git status
정상 상태:


nothing to commit, working tree clean
'@ | Set-Content README.md -Encoding utf8

code


---


## 작업 폴더 생성 및 현재 위치 확인

작업 폴더를 생성하고 해당 폴더로 이동한 뒤, 현재 경로를 확인했다.

```powershell
pwd
```

```text
Path
----
C:\Users\sanghyun0709201618\dev-workstation-mission
```

### 디렉토리 파일 목록 확인

```powershell
dir
```

```text
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
...
-a----        ...                         README.md
-a----        ...                         permission-test.sh
...
```