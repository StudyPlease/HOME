# HOME

<h1>귀요미들 자료구조 복습</h1>

<h2>문제 풀이 사이트</h2>
백준 : https://www.acmicpc.net/

프로그래머스 : https://programmers.co.kr/

++ solved.ac(백준과 연동되어 티어 측정) : https://solved.ac/

<h2>Repository 사용법</h2>    
개개인의 branch를 생성하여 본인의 branch에만 소스코드를 올릴 수 있도록 합니다.  

- **git clone** -> 현재 DataStructure_tutoring 이라는 레파지토리가 복제되어 해당 git bash here 한 위치에 폴더가 생성된다. (.git파일과 Readme파일 있음)
- **exit** -> git bash 종료
- 푼 문제의 소스코드(.c)만 DataStructure_tutoring 폴더에 추가
- DataStructure_tutoring 폴더 안에서 **git bash here**
- **git init** -> "해당 폴더를 git으로 버전관리 하겠다." 명령어. 하지만 우리는 clone을 해서 만들어진 폴더에서 버전관리 하는 것이기 때문에 이미 버전관리 진행중임. .git파일이 버전을 관리하는 파일. 
- **git branch 브랜치명** -> 브랜치를 생성한다. 브랜치명은 영어로 띄어쓰기 없이 본인 이름으로. ex) git branch seongho
- **git checkout 브랜치명** -> 해당 브랜치로 이동. 처음에는 모두 디폴트값으로 master브랜치에 있을 것임. 반드시 본인 이름으로 된 브랜치로 이동 후 작업하기!!!!
- **git add 파일명** -> 해당 파일을 staging area로 올린다. ex) git add 연결리스트.c  / 또는 **git add .** 이렇게 하면 모든 파일을 staging area로 올림
- **git commit -m "[해당 자료구조명] 백준 문제번호 문제이름"**  ex) git commit -m "[연결리스트] 백준1158 요세푸스 문제" -> 버전을 만듦.
- **git branch** -> push 하기 전에 마지막으로 branch 확인. 현재 작업중인 branch 출력됨. 본인 이름 맞으면 통과
- **git push origin 브랜치명** : 원격저장소에 push한다. ex) git push origin seongho
- **git pull origin 브랜치명** : 원격저장소의 최신 버전을 로컬저장소로 가져온다. 예를들어서, 제가 README.md파일을 원격저장소에서 수정을 했습니다. 그 후 로컬저장소와 원격저장소의 파일 내용을 같게 하기 위해서 git pull origin tutor_lec을 해서 로컬저장소를 최신화시켜줬습니다. 
