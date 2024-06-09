## 2024-1-OSSProj-SOUP-10  
> 2024년 1학기, 오픈소스소프트웨어 프로젝트, SOUP 10조  

<br />  

## 팀 구성  

구분 | 성명 | 소속학과 | 연계전공 | 이메일
------|-------|-------|-------|-------
팀장 | 권일준 | 통계학과 | 융합SW연계전공 | jonkwon99@dongguk.edu         
팀원 | 김명하 | 산업시스템공학과 | 융합SW연계전공 | kk313s@dongguk.edu        
팀원 | 이승호 | 생명과학과 | 융합SW연계전공 | sholeept@dongguk.edu   

## 종합 정보  
### 프로젝트 제목  
휠체어도 사용 가능한 동국대학교 편한 길 찾기  

### 프로젝트 목표
* 동국대학교 서울캠퍼스는 남산자락에 위치하여 상당한 언덕과 건물간의 고저차가 존재하여 신입생, 외부인, 해당 건물에 처음 가는 사람의 경우 최적화된 경로를 알기 어려움
* 전동 휠체어 사용자을 위해 계단과 높은 경사도가 있는 길을 사용하지 않는 경로를 소개하는 프로그램을 개발하고 동국대학교의 구성도를 제공  

기존 프로젝트: [동국대학교 편한 길 찾기](https://github.com/CSID-DGU/2023-2-OSSP1-Entity-5)  

### 기대효과  

* 전력 기반 경로 최적화  
   * 시간이나 거리가 아닌 전력 소비를 최소화하여, 전동 휠체어 사용자가 가장 효율적으로 이동할 수 있는 경로 제공  
* 이동 편의성 증대  
   * 캠퍼스 내에서 휠체어 사용자의 자유로운 이동을 가능하게 하여 일상 생활의 질 향상  
* 접근성 개선  
   * 계단이나 경사로를 피하는 경로 선택으로 모든 건물 및 시설 접근 용이  
* 사회적 포용성 강화  
   * 장애를 가진 학생 및 방문객에게 평등한 교육 및 체험 기회 제공 

### 최종 결과물
 메인 페이지(MAIN) | 길찾기 페이지(NAV)
 -------------------------|------------------------------
<img width="550" alt="image" src="https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/ReferenceImages/main_page.png"> | <img width="550" alt="image" src="https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/ReferenceImages/nav_page.png">

 건물정보 페이지(INFO) | 편의시설 페이지(CONVENIENT)
 -------------------------|------------------------------
<img width="550" alt="image" src="https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/ReferenceImages/building_page.png"> | <img width="550" alt="image" src="https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/ReferenceImages/conv_page.png">

 [프로젝트 시연 동영상](https://www.youtube.com/watch?v=R1Z8yBF68Tw)

 [프로젝트 개발을 위한 소스코드](https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Src/Overview.md)

### 프로젝트 설계/구현 내용
* 계단과 높은 경사가 있는 길을 제외하고 전력소비량을 최소화하는 휠체어용 네비게이션 기능을 추가  
* 휠체어용 네비게이션으로 다익스트라 알고리즘을 활용  
* 동국대학교 충무로 방향 건물들에 대한 전체 구조도 작성  
    * 유스케이스 다이어그램(Usecase Diagram)  
    <img width="550" alt="image" src="https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/ReferenceImages/usecase_finalreport.jpg">  

    * 블록 다이어그램(Block Diagram)
    <img width="550" alt="image" src="https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/ReferenceImages/block_finalreport.jpg">  

    * 시퀀스 다이어그램(Sequence Diagram) 
    <img width="550" alt="image" src="https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/ReferenceImages/sequence.jpg">  

### Tech Stack
<img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat-square&logo=Visual Studio Code&logoColor=white"/> <img src="https://img.shields.io/badge/Intellij-000000?style=flat-square&logo=intellijidea&logoColor=white"/> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/>

<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"/> <img   src="https://img.shields.io/badge/Node.js-%235FA04E?style=flat-square&logo=node.js&logoColor=black"/> <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/> <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"/>

### 프로그램 요구사항 및 실행 방법

[프로그램 실행 방법](https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/4_3_OSSProj_10_SOUP_%EC%A0%9C%ED%92%88%EA%B5%AC%EC%84%B1%EB%B0%B0%ED%8F%AC%EC%9A%B4%EC%98%81%EC%9E%90%EB%A3%8C.md)

### 프로젝트 관리문서

1. 보고서 - [계획](https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/1_1_OSSProj_10_SOUP_%EC%88%98%ED%96%89%EA%B3%84%ED%9A%8D%EC%84%9C.md)  [중간](https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/2_1_OSSProj_10_SOUP_%EC%A4%91%EA%B0%84%EB%B3%B4%EA%B3%A0%EC%84%9C.md)  [최종](https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/3_1_OSSProj_10_SOUP_%EC%B5%9C%EC%A2%85%EB%B3%B4%EA%B3%A0%EC%84%9C.md)
2. 발표 자료 - [계획](https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/1_3_OSSProj_10_SOUP_%EC%88%98%ED%96%89%EA%B3%84%ED%9A%8D%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C.pdf)  [중간](https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/2_3_OSSProj_10_SOUP_%EC%A4%91%EA%B0%84%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C.pdf)  [최종](https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/3_2_OSSProj_10_SOUP_%EC%B5%9C%EC%A2%85%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C.pdf)
3. [범위/일정 및 이슈 관리](https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/4_1_OSSProj_10_SOUP_%EB%B2%94%EC%9C%84_%EC%9D%BC%EC%A0%95_%EC%9D%B4%EC%8A%88%EA%B4%80%EB%A6%AC.md)
4. [회의록](https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/4_2_OSSProj_10_SOUP_%ED%9A%8C%EC%9D%98%EB%A1%9D.md)
5. [제품의 구성, 배포 및 운영 관련 문서 자료](https://github.com/CSID-DGU/2024-1-OSSProj-SOUP-10/blob/main/Doc/4_3_OSSProj_10_SOUP_%EC%A0%9C%ED%92%88%EA%B5%AC%EC%84%B1%EB%B0%B0%ED%8F%AC%EC%9A%B4%EC%98%81%EC%9E%90%EB%A3%8C.md)
