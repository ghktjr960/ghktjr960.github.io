---
layout: default
---

# **Trip Diary**
### **2021.9.23 ~ 2021.11.10** 
---
## **프로젝트 소개**
### KG IT뱅크에서 진행한 팀프로젝트입니다. 
 * 여행이라는 큰 주제를 가지고 사용자들에게 가장 도움이 될 수 있는 정보를 제공하는 사이트입니다.
 * 자신이 다녀온 여행에 대한 기록을 일기처럼 남겨 지난 여행에 대한 기록을 확인할 수 있습니다.
 * 다른 사용자들과 다녀온 여행을 공유하며 필요한 정보를 교환할 수 있습니다.  

## **프로젝트 주요기능**
**관리자**
> 회원 신고 처리  
> 게시글 신고 처리  
> 댓글 신고 처리  
> 탈퇴 회원 관리  

**사용자**
> 회원가입 및 로그인  
> 게시글 작성 및 수정  
> 게시글 열람 및 검색   
> 좋아요, 찜하기, 엠블럼 획득   
> 다녀온 장소 확인  
> 회원, 게시글, 댓글 신고  

## **담당 파트**
* 요구분석 정의서 작성
* 데이터베이스 설계(테이블 정의서) 및 ERD작성
* 카카오오븐을 활용해 사이트의 전체적인 UI설계 진행
* 게시글 정렬, 페이징 구현
* 지역별 카테고리, 검색어, 게시글 해시태그(#)를 구분하여 게시글 검색 기능 구현
* 관리자 페이지에서 회원, 게시글, 댓글 관리 기능 구현

## **담당 파트 구현 영상**
![main_page](https://user-images.githubusercontent.com/88276563/149528861-e9bbcc64-48ae-4d0b-b797-4a98f61e3d40.gif)

![pick_page](https://user-images.githubusercontent.com/88276563/149529520-580403e7-0859-40f4-bd5a-54345e3cab1a.gif)

![admin_page](https://user-images.githubusercontent.com/88276563/149529577-3b66553e-db9d-4981-8db1-915d203ea0de.gif)

## **사용한 기술**
Java, Spring, Oracle DB, Github, Javascript, JQuery  

## **참고링크**
[Trip Diary 사이트](http://cmh93.synology.me:49158/main)  
[DB설계(ERD Cloud)](https://www.erdcloud.com/d/fKvpacZ6HFLBX5C2S)  
[UI설계(kakaoOven)](https://ovenapp.io/view/HCQC9wnUpKLxnmZfDU1sIZyLpJroaMEH/)  
[개발코드(Github)](https://github.com/ghktjr960/TripDiaryTeam)  
[기타설계문서(Github)](https://github.com/ghktjr960/TripDiary)  
[발표자료](https://docs.google.com/presentation/d/1sP1d0vG8pp4Txwh2A_AsKIe3wMnhdOGct6V3qYySQYA/edit#slide=id.p1)  

## **프로젝트 진행 후 느낀점**
**프로그래밍 언어 및 웹 동작 과정에 대한 이해도 증가**
* 웹 개발에 관한 공부를 한지 4~5개월 차에 진행한 프로젝트였던 만큼 기본적인 프로그래밍 언어, 웹 동작 과정에 대한 이해도가 부족했었지만, 프로젝트를 진행하는 과정에서 요구분석설계를 시작으로 최종 프로젝트 설계까지 각각의 과정을 하나씩 풀어서 생각하고 직접 만들어보면서 프로그래밍 언어와 웹 동작 과정에 대해 이해할 수 있게 되었습니다.

**오류를 읽어보는 습관**
* 개발과정에서 java, Javascript, SQL 등등 오류가 정말 자주 발생했습니다. 그 이유도 오타, 변수의 타입을 잘못 선언한 것, 의존주입이 안 되어 있던 것, pom 파일에서 버전 설정을 잘못한 것 등등 너무나 다양하게 존재했습니다. 여러 번에 오류를 보다 보니 콘솔 창에 나와 있는 오류 메시지를 천천히 읽어보면 왜 오류가 발생했는지 어디서 문제가 있는 건지 이해가 되기 시작했습니다. 그 이후부터는 오류가 발생하면 대충 보는 것이 아니라 오류를 꼼꼼하게 읽고 해결하게 되었습니다.

**객체지향의 장점**
* 각자의 파트를 구분하여 코드를 작성한 뒤 하나로 합치는 방식으로 프로젝트를 진행했는데 각자 만든 코드가 독립적으로 동작할 수 있게 모듈화를 시킨 후 합치는 방식을 통해 객체지향의 장점을 이해할 수 있게 되었습니다.

**팀원간 커뮤니케이션**
* 코드, 결과물에 대한 피드백을 주고받으면서 서로에 대한 응원과 격려를 아끼지 않았고 문제가 발생했을 때 다 같이 해결하기 위해 노력하면서 팀원 간 커뮤니케이션이 얼마나 중요하고 그로 인해 오는 장점이 많다는 것을 알게 되었습니다.

[back](./)
