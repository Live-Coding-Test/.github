## 진행 방식

문제 선정 순서   
    ```지민 → 선재 → 지은 → 우희 → 희경```

### 문제 마감기간 : 일요일 18시까지 문제 제출

---
## 제출 방법
1. organization 리포지토리(원본 리포로 지칭)를 fork한다.

2. fork한 개인 리포를 로컬에 clone한다.

    예시) git clone https://github.com/gmlrude/Algorithm-study.git


3. fork한 repository 최신화 방법
    -  git remote add upstream https://github.com/Team-Joon-CodingTest/Algorithm-study.git (초기 1회만)
    - git remote -v ( 연결 확인 용도 )  

4. git fetch upstream ( 원본과 동기화 작업 )
5. git merge upstream/main ( 본인 레포에 적용 )

<br>
 
6. fork한 저장소의 각 주차에 해당되는 과제 폴더에 소스 코드를 commit 후 push 합니다. 
    - `파일명`은 문제번호_이름으로 합니다. ex) 박희경_1299.java
    - `commit 메세지`는 다음과 같이 합니다. "N주차 문제번호 문제풀이"

        ex) 1주차 1299번 문제풀이

<br>
    
7. 문제를 다 풀었으면 PR을 올립니다.   
 PR 제목은 "[이름] N주차 과제 제출" 로 합니다.   
 ex) [박희경] 1주차 과제 제출

- 한 명 이상의 코드를 리뷰합니다.
