# git-practice

README 파일은 저장소에 대한 설명을 적는 곳입니다.


5.18 정리본
 TODAY I LEARN

# 📚 2026 05 18 오늘 배운 내용 총정리 (CMD / PowerShell / Git / VS Code)

# 💻 1. 터미널 기본 개념

#📌 `dir` (CMD)

현재 폴더의 파일 목록 보기

dir


#📌 `ls` (PowerShell / Git Bash)

파일 목록 보기

ls


# 📌 `cd` (폴더 이동)

cd 폴더이름


# ✔ 자주 쓰는 이동

cd .


👉 현재 위치

cd ..


👉 상위 폴더로 이동

cd ~


👉 홈 디렉토리 이동 (C:\Users\사용자)


# 📌 경로 개념


# ✔ 절대 경로

어디서든 바로 이동 가능

cd C:\Users\Administrator\Desktop


# ✔ 상대 경로

현재 위치 기준 이동

cd Desktop


# 📌 경로 구분자

* Windows: `\`
* Git Bash: `/`


# 📌 TIP

* `Tab` → 자동완성
* ↑ ↓ → 이전 명령어 보기


# ⚡ 2. PowerShell 명령어


# 📌 `pwd`

현재 위치 확인

pwd


# 📌 `mkdir`

mkdir [git]


# 📌 `ls`

파일 목록 보기

ls


# 📌 `~` (틸드)

👉 홈 디렉토리 의미

C:\Users\Administrator


# 🧠 3. Git 기본 개념


# 📌 Git이란?

👉 파일의 변경 이력을 저장하는 프로그램


# 📌 Git 시작

git init

👉 현재 폴더를 Git 저장소로 만듦


# 📌 상태 확인

git [status]


# 📌 파일 추가

git add .

또는

git add 파일이름


# 📌 커밋 (저장)

git commit -m "first commit"


# 📌 Git 사용자 설정 (필수)

git config --global user.name "Administrator"
git config --global user.email "admin@test.com"


# 📁 4. 파일 생성


# 📌 echo

echo 'first file'

👉 화면 출력


# 📌 파일 생성

echo 'first file' > first.txt

👉 파일 생성 + 내용 저장

# 🖥️ 5. VS Code Git 기능


# 📌 Source Control

* 변경된 파일 확인
* Stage (올릴 파일 선택)
* Commit 버튼으로 저장 가능


# 📌 에러 해결 [2026 05 18 오류 발생 원인]


# ❌ user.name / user.email 오류

👉 해결:

git config --global user.name "이름"
git config --global user.email "이메일"


# 📌 6. 중요 핵심 정리

# ✔ Git 기본 흐름

파일 수정 → git add → git commit

# ✔ 필수 5개

* `pwd` → 위치 확인
* `cd` → 이동
* `ls / dir` → 목록 보기
* `git init` → 시작
* `git add / commit` → 저장

# 🚀 한 줄 핵심

👉 Git은 “파일 저장 + 기록 관리 시스템”이다
👉 반드시 “폴더 안에서 시작(git init)” 해야 한다
👉 commit 전에 반드시 add 해야 한다



### 오늘 배운 내용

- git init
- git add
- git status
- ...

### 오늘 정리한 내용

