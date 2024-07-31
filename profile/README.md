## 진행 방식

### 라이브 코딩 테스트 일정
- 화요일 23:59
- 목요일 23:59 
- 토요일 14:00
  
2시간동안 진행합니다. (라이브 코테 + 코드 리뷰)

---
## 제출 방법
1. organization 리포지토리(원본 리포로 지칭)를 fork한다.

2. fork한 개인 리포를 로컬에 clone한다.

    예시) git clone https://github.com/gmlrude/Algorithm-study.git

3. fork한 repository 최신화 방법
    -  git remote add upstream https://github.com/Live-Coding-Test/Algorithm-study.git (초기 1회만)
    - git remote -v ( 연결 확인 용도 )  

4. git fetch upstream ( 원본과 동기화 작업 )
5. git merge upstream/main ( 본인 레포에 적용 )

<br>
 
6. fork한 저장소의 각 주차에 해당되는 과제 폴더에 소스 코드를 commit 후 push 합니다. 
    - `파일명`은 이름으로 합니다. ex) 박희경.java
    - `commit 메세지`는 다음과 같이 합니다. "N차 문제번호 문제풀이"

        ex) 1차 1번 문제풀이

<br>
    
7. 문제를 다 풀었으면 PR을 올립니다.   
 PR 제목은 "[이름] N차 라이브 코테 제출" 로 합니다.   
 ex) [박희경] 1차 라이브 코테 제출

