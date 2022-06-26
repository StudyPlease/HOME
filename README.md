# HOME

<h1>귀요미들 자료구조 복습</h1>

<h2>문제 풀이 사이트</h2>
백준 : https://www.acmicpc.net/

프로그래머스 : https://programmers.co.kr/

++ solved.ac(백준과 연동되어 티어 측정) : https://solved.ac/

<h2> 스터디 규칙</h2>
1. 주(월~일) 2문제 필수 더 풀고 싶은 사람 더 풀기 <br>
2. 규칙1 못지킬 시 벌금 5000원 <br>
3. 문제는 내가 정해줌 (쉬운 문제 1, 어려운 문제 1) 브론즈3~실버4 <br>
&nbsp;&nbsp;&nbsp;&nbsp;김성호는 어려운문제 1 같이 풀고 실버2 이상 문제 1문제<br>
4-1. 어떻게 풀지 알겠는 문제는 시간 걸리더라도 끝까지 본인 힘으로 풀기. 대신, 풀고 나서 구글링<br>
4-2. 어떻게 풀지 모르겠는 문제는 40분 정도 고민해보고 구글링 ex)백준 1406 cpp<br>
<br>
+코드 규칙<br>
1. 주석은 코드를 짜면서 동시에 쓰기 <br>
2. 문제 풀기 전에 어떤 자료구조를 써서 어떻게 풀지 코드 상단에 대충 써놓기<br>
3. 남과 공유한다고 생각하고 코드 최대한 예쁘게 짜기(일관성 있게, 가독성 좋게)<br>
4. 문제를 다 푼 후, 중복을 줄일 수 있는 부분을 최대한 줄여보기(최적화)<br>
<br><hr><br>
<h2>Repository 사용법</h2>    
<b>본인 이름으로 된 Repository</b>에서 
해당 주차의 branch를 생성하여 해당 주차의 branch에만 소스코드를 올릴 수 있도록 합니다.  

<details>
  <summary><h3>예시</h3></summary>
  
  <img src="https://user-images.githubusercontent.com/81570533/175817395-520597b9-8ded-4f18-9553-03c77c1606e0.png">
  <em><strong>예시를 위해 0week로 시작했고, 2022-06-27부터는 1week 시작!!!!!!!!!!!</strong></em>
</details>


<br><hr><br>

- **git init** -> "해당 폴더를 git으로 버전관리 하겠다." 라는 뜻의 명령어. .git파일이 버전을 관리하는 파일로 생성된다. 
- **git branch 브랜치명** -> 브랜치를 생성한다. 브랜치명은 해당주자+week. ex) git branch 1week
- **git checkout 브랜치명** -> 해당 브랜치로 이동. 처음에는 모두 디폴트값으로 master브랜치에 있을 것임. 반드시 해당 주차 브랜치로 이동 후 작업하기!!!!
- **git add 파일명** -> 해당 파일을 staging area로 올린다. <strong>꼭 다른 파일 말고 cpp, py파일만 올리기!!!</strong> ex) git add 1406.cpp 
- **git commit -m "백준 문제번호 문제이름 [난이도]"** -> 버전을 만든다. ex) git commit -m "백준 1158 요세푸스 문제 [실버2]" 
- **git branch** -> push 하기 전에 마지막으로 branch 확인. 현재 작업중인 branch 출력된다. 맞으면 넘어가기
- **git push origin 브랜치명** : 원격저장소에 push한다. ex) git push origin 1week

