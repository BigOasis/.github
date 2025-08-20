# 🌴 BigOasis 알고리즘 스터디

| 구분       | 내용 |
|------------|------|
| **언어** | Java / Python |
| **진행 기간** | 2025.08.19 ~ 2025.09.26 (6주) + 이후 기출 문제 풀이 |
| **진행 공간** | Discord / GitHub |
| **정기 스터디 시간** | 매주 **화요일** 오전 10:00 ~ 12:00 |

<br/>

## 📅 진행 일정

| 주차  | 날짜                | 주제 |
|-------|--------------------|------|
| 1주차 | 08.19 ~ 08.25      | 완전탐색, 순열, 조합, 재귀 |
| 2주차 | 08.26 ~ 09.01      | 스택, 큐, 그래프, DFS, BFS |
| 3주차 | 09.02 ~ 09.08      | DFS, BFS |
| 4주차 | 09.09 ~ 09.15      | 다익스트라, 힙, 위상정렬 |
| 5주차 | 09.16 ~ 09.22      | 문자열, 해시테이블 |
| 6주차 | 09.23 ~ 09.26      | DP |
| 7주차~| 09.27 ~            | 기출문제 풀이 |

> 📌 매주 **화요일 오전 10시**에 [노션 페이지](https://www.notion.so/BigOasis-250672106a20807ca6e0f592c364e091?source=copy_link)에 문제 공개

<br/>

## 🙋‍♂️ 정규 스터디 참여 방법

1. **디스코드 참여**  
   - 화 정규 스터디 시간에 참여 (질문은 상시 가능)
2. **문제 풀이 & 리뷰**  
   - 각 주차 문제를 정규 시간 전까지 풀고, PR에 리뷰 코멘트를 작성
   - **정규 시간 진행**  
     - 60분: 공통 문제 1개 풀이  
     - 60분: 이전 주차 모든 내용 PR 한번에 올리기 (예제, 과제, 스터디 포함)  
       → 과제, 스터디 문제 위주 코드 리뷰
3. **레포지토리 브랜치 생성 규칙**  
   - Java: `java/영문이름`  
   - Python: `python/영문이름`  
     예) `java/EunseoPark`, `python/YoungjuLee`
4. **주차별 문제 분류**
   * **예제**: 필수로 전부 풀이
   * **과제**: 필수로 전부 풀이
   * **스터디**: 스터디 당일에 공개되며, **스터디 장이 랜덤으로 선정**하여 진행

## 🛠 진행 순서

### Python 반

1. **main 브랜치 pull**
2. `git checkout -b python/이름` 으로 개인 브랜치 생성
3. 지정 폴더 구조로 문제 코드 작성
   예) `EunseoPark/Week1/BOJ_1018_체스판다시칠하기.py`
4. 각 주차 **이슈 생성**
   예) `[Week1] BOJ_1018_체스판다시칠하기`
5. 문제 풀이 후 **PR 생성**

   * 예제, 과제, 스터디 문제 풀이 후 정규 스터디 시간에 **PR 생성 1회**
   * [자체 코드조짜기 프로그램](https://big-oasis-team-divider.vercel.app/)으로 이번 주 코드리뷰 조 배정
   * 본인을 제외한 나머지 2명을 리뷰어로 지정
   * 문제를 풀지 못했을 경우에도 접근 방법을 PR에 작성하기
6. 이번 주 **조원들에게 코드 리뷰 작성 (필수)**

   * 본인이 속한 조가 아니어도 선택적으로 리뷰 가능
7. 본인의 PR 리뷰를 모두 확인한 뒤, **본인이 최종 머지**
   
<br/>

### Java 반

1. **main 브랜치 pull**
2. `git checkout -b java/이름` 으로 개인 브랜치 생성
3. 지정 폴더 구조로 문제 코드 작성
   예) `EunseoPark/Week1/BOJ_1018_체스판다시칠하기.java`
4. 각 주차 **이슈 생성**
   예) `[Week1] BOJ_1018_체스판다시칠하기`
5. 문제 풀이 후 **PR 생성**

   * 예제, 과제, 스터디 문제 풀이 후 정규 스터디 시간에 **PR 생성 1회**
   * 리뷰어는 **모든 팀원**을 지정
   * 문제를 풀지 못했을 경우에도 접근 방법을 PR에 작성하기
6. 모든 팀원들이 **코드 리뷰 작성 (필수)**
7. 스터디장/부장이 최종 머지

<br/>
## 📂 폴더 구조

> 플랫폼 태그  
> - BOJ: 백준  
> - PGS: 프로그래머스  
> - LTC: 리트코드

```

이름 /
└── Week1 /
├── BOJ_1018_체스판다시칠하기.java
├── PGS_게임.java
└── LTC_문제명.java

```

<br/>

## 📌 Commit 컨벤션
> {태그}: {클래스 이름(플랫폼_문제번호_문제제목)}
```

feat: BOJ_1018_체스판다시칠하기_체스판

```

<br/>

## 📌 PR 규칙

> [주차] 영문_이름 - {푼문제개수}문제  

예시:  
```

[1주차] YoungjuLee - 8문제

```

<br/>

## 스터디 멤버

### 🐍 Python

| 이영주 <br/> *(스터디장)* | 배지아 | 안민지 | 정다희 | 최희승 | 허준호 |
|---------------------------|--------|--------|--------|--------|--------|
| <img src="https://avatars.githubusercontent.com/u/77565980?v=4" width="96"> | <img src="https://avatars.githubusercontent.com/u/124412137?v=4" width="96"> | <img src="https://avatars.githubusercontent.com/u/195983909?v=4" width="96"> | <img src="https://avatars.githubusercontent.com/u/55499429?v=4" width="96"> | <img src="https://avatars.githubusercontent.com/u/195768537?v=4" width="96"> | <img src="https://avatars.githubusercontent.com/u/127181459?v=4" width="96"> |
| [@abyss-s](https://github.com/abyss-s) | [@qowldk](https://github.com/qowldk) | [@minji-38](https://github.com/minji-38) | [@alotofhee](https://github.com/alotofhee) | [@choi-hi](https://github.com/choi-hi) | [@gichulLimitLess](https://github.com/gichulLimitLess) |


<br/>


### ☕ Java

| 박은서 <br/> *(스터디장)* | 박교녕 | 이은채 | 서보인 |
|---------------------------|--------|--------|--------|
| <img src="https://avatars.githubusercontent.com/u/88071251?v=4" width="96"> | <img src="https://avatars.githubusercontent.com/u/80964083?v=4" width="96"> | <img src="https://avatars.githubusercontent.com/u/171488704?v=4" width="96"> | <img src="https://avatars.githubusercontent.com/u/63088266?v=4" width="96"> |
| [@arty0928](https://github.com/arty0928) | [@kny0ng125](https://github.com/kny0ng125) | [@eunchrri](https://github.com/eunchrri) | [@sbi1024](https://github.com/sbi1024) |

<br/>

## 📎 참고
- **노션 문제집**: [바로가기](https://www.notion.so/BigOasis-250672106a20807ca6e0f592c364e091?source=copy_link)
- **진행 공간**: Discord / GitHub

