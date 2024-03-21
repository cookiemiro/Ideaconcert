<h2>2. GitHub 사용법</h2>

<h4>환경설정</h4>

**유저 이름 설정**<br/>
git config --global user.name "your_name"

**유저 이메일 설정(Github 이메일 사용)**<br/>
git config --global user.email "your_email"

**정보 확인**<br/>
git config --list

---

<h4>Github에 처음 코드 업로드시</h4>

**초기화**<br/>
git init

**추가할 파일 더하기**<br/>
모든 파일 : git add .<br/>
선택적(예) : git add index.html

**상태 확인**<br/>
git status

**히스토리 만들기**<br/>
git commit -m "first commit"

**Github repository랑 내 로컬 프로젝트랑 연결**<br/>
git remote add origin https://github.com/m1kkang/Ideaconcert.git

**잘 연결됐는지 확인**<br/>
git remote -v

**Github로 올리기**<br/>
git push origin master<br/>
git push origin heajeong

---

<h4>Github에 계속 업데이트 하는 법</h4>

**추가할 파일 더하기**<br/>
git add .

**히스토리 만들기**<br/>
git commit -m "first commit"

**Github로 올리기**<br/>
git push origin master
git push origin heajeong

<h4>Github로 팀프로젝트 하는 법</h4>

**Github에서 소스코드 다운로드**<br/>
git clone 주소 폴더이름(선택)

**Github에서 내 브렌치(branch)만들기**<br/>
git checkout -b heajeong

**내 브렌치에 소스코드 업데이트하기**<br/>
git add .<br/>
git commit -m "first commit"<br/>
git push origin heajeong

**마스터 브렌치에 소스 가져오기(pull)**<br/>
git pull origin master

**브렌치끼리 이동하는 법**<br/>
git checkout 브렌치이름
