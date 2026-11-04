



# Dev Workstation Mission



## 1. 작업 폴더 생성



### 실행한 명령어



```powershell

pwd

dir -Force

mkdir dev-workstation-mission

cd dev-workstation-mission

pwd

```



### 결과



작업 폴더 `dev-workstation-mission`을 생성하고 해당 폴더로 이동했다.



현재 위치:



```powershell

C:\\Users\\sanghyun0709201618\\dev-workstation-mission

```



---



## 2. README.md 생성



### 실행한 명령어



```powershell

New-Item README.md -ItemType File

dir

notepad README.md

```



### 결과



`README.md` 파일을 생성하고 메모장으로 열어 실습 내용을 기록했다.



---



\## 3. 배운 내용 정리



\- `pwd`: 현재 위치 확인

\- `dir`: 현재 폴더의 파일/폴더 목록 확인

\- `dir -Force`: 숨김 파일까지 포함해서 목록 확인

\- `mkdir`: 새 폴더 생성

\- `cd`: 폴더 이동

\- `New-Item`: 새 파일 생성

\- `notepad`: 메모장으로 파일 열기

---

## 4. Git 설치 확인

### 실행한 명령어

```powershell```
git --version

결과
Git 버전을 확인했다.

git version 2.56.0.windows.4

#  Git 저장소 만들기

### 실행한 명령어

```powershell```
git --version
git init
git status
git add README.md
git status
git commit -m "docs: add README"

Docker 설치를 확인했다.

text

Docker version 29.0.2, build ae82528
Docker Compose version v5.6.1

