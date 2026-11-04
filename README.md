


@'
# Dev Workstation Mission

## 1. CLI 명령어 실습

사용한 명령어:

```powershell
pwd
dir
dir -Force
mkdir dev-workstation-mission
cd dev-workstation-mission
pwd

설명
pwd: 현재 위치 확인
dir: 파일과 폴더 목록 확인
dir -Force: 숨김 파일 포함 목록 확인
mkdir dev-workstation-mission: 작업 폴더 생성
cd dev-workstation-mission: 작업 폴더로 이동

2. Git 설정 및 사용
사용한 명령어: 
bash

git init
git status
git add README.md
git commit -m "docs: add README"
Git 저장소를 초기화하고 README 파일을 커밋했습니다.

3. GitHub 원격 저장소 연결
GitHub 저장소 주소: https://github.com/sang200709/dev-workstation-mission.git
사용한 명령어:

bash

git remote -v
git push -u origin main
설명
로컬 Git 저장소를 GitHub 원격 저장소와 연결하고 push했다.


4. Docker 확인
사용한 명령어:

bash

docker --version
Docker 설치 여부와 버전을 확인했다.



5. 실행 권한 테스트
테스트 파일

text
permission-test.sh
사용한 명령어
bash

chmod +x permission-test.sh
git ls-files --stage permission-test.sh
결과

text
100755 permission-test.sh
100755는 Git에서 실행 권한이 있는 파일로 추적된다는 뜻이다.

6. 최종 상태 확인
사용한 명령어
bash

git status
정상 상태

text
nothing to commit, working tree clean



---

## 수정 후 할 일

README 수정했으면 다시 커밋하고 push 하세요.

```bash
git add README.md
git commit -m "docs: clean up README"
git push
그리고 마지막 확인:

bash

git status
정상 결과:

text

nothing to commit, working tree clean
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
