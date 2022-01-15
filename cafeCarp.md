---
layout: default
---

# **cafe_Carp**
### **2021.11.17 ~ 2022.01.05** 
---
## **프로젝트 소개**
### 스터디그룹을 통해 백엔드개발자 3명이서 진행한 팀프로젝트입니다. 
- 카페에서 사용되는 키오스크, 포스기를 사용한 결제과정을 표현한 웹 사이트입니다.
- 키오스크에서 결제를 진행했을 경우 웹 소켓을 통해 포스기에서 주문을 확인할 수 있습니다.
- 메뉴선택부터 결제 후 영수증 출력까지 과정을 표현했으며 매출에 관한 정보를 확인할 수 있습니다.

## **프로젝트 주요기능**
**사용자**
> 메뉴주문  
> 회원가입 및 포인트 조회(회원로그인)  
> 포인트 적립 및 사용  
> 결제 및 영수증 출력  

**관리자**
> 관리자 로그인  
> 주문내역 확인  
> 메뉴주문  
> 결제 및 영수증 출력  
> 회원가입 및 포인트 조회  
> 포인트 적립 및 사용  
> 매출관리  
> 메뉴관리  
> 회원관리  
> 관리자 계정 관리  

## **담당 파트**
* 프로젝트 기획 및 설계 참여
* kiosk-pos 결제과정을 Websocket으로 구현
* 관리자 로그인 상태 확인을 위한 Interceptor 설계 및 구현
* 공통에러페이지 구현
* 관리자 페이지에서 메뉴 주문, 결제 및 주문취소, 결제취소 기능
* 관리자 페이지에서 회원등록 및 조회 기능
* 관리자 페이지에서 포인트 조회 및 사용 기능

## **담당 파트 구현 영상**
![menuOrder_page](https://user-images.githubusercontent.com/88276563/149607886-9703999c-bc33-4199-adc4-fb3195a510ca.gif)
![point_page](https://user-images.githubusercontent.com/88276563/149607887-a77b40a5-e330-40ab-8398-137bd0e05e51.gif)
![register_page](https://user-images.githubusercontent.com/88276563/149607888-30cd3e0b-6814-47c1-9e4a-ac576ad9c508.gif)
![orderList_page](https://user-images.githubusercontent.com/88276563/149607889-dede49fd-175b-4435-8430-1b27e4cc3bef.gif)
![kiosk_pos_socket](https://user-images.githubusercontent.com/88276563/149607885-ab2a2157-1a51-4a80-b9b0-2c4407325208.gif)


## **사용한 기술**
Java, Spring, Oracle DB, Github, Javascript, JQuery, Bootstrap, Websocket  

## **참고링크**
[cafeCarp Full Video](https://youtu.be/CpvzPEnTHfg)  
[DB설계(ERD Cloud)](https://www.erdcloud.com/d/aQX5XH6FSpQ5boebz)  
[UI설계(kakaoOven)](https://ovenapp.io/view/o6qhI0UDdZZMsPge61fidf2eYWlOeL7D/)  
[개발코드(Github)](https://github.com/JinSolKwon/cafeKiosk-code-)  
[기타설계문서(Github)](https://github.com/JinSolKwon/cafeKiosk)  
[PPT자료](https://docs.google.com/presentation/d/1YpJmQV32lOIxAVv9igVgFp07jJFyp8jbgdyOlBOHsNg/edit#slide=id.p1)  
[세부일정계획표](https://docs.google.com/spreadsheets/d/1QmlWY-MhG9CwIqt_5TTt8NeKvUeNJZz743VhFsjidyg/edit?usp=drive_web&ouid=101429968988774976735)  

## **프로젝트 진행 후 느낀점**
**Bootsatrap에 대한 이해도 증가**
* 이전에 했던 프로젝트에서는 kakaoOven을 통해 전체적인 UI 설계에 틀을 잡고 실제 구현 시 디자인 쪽 코드는 다른 팀원이 진행했던 것을 받아서 사용했었지만, 이번 프로젝트에서는 Bootstrap을 통해 직접 디자인 부분에 코드까지 작성했습니다. 이를 통해 Html, CSS에 대한 기본 지식을 얻을 수 있게 되었습니다.

**Github 숙련도 증가**
* Github Desktop을 사용해 협업 및 관리를 진행했습니다. 이를 통해서 브렌치 연결 및 사용을 자유롭게 할 수 있게 되었습니다.

**Websockek에 대한 이해**
*  kiosk에서 주문한 내용을 pos에서 바로바로 확인하는 방법을 고민하다가 생각된 것이 Web socket을 통해 주문정보를 주고받는 것이었습니다. Web socket을 통해 채팅할 수 있는 페이지를 구현하고 자유롭게 내용을 보낼 수 있는 기능 대신 주문마다 발생하는 주문번호를 고정적으로 보내면 될 것 같아 구현해보았습니다. Web socket에 대한 코드와 자료를 공부하고 정리하는 과정에서 Web socket을 사용하는 이유와 문제점들에 대해 이해할 수 있게 되었습니다. *[블로그 정리 글](https://blog.naver.com/ghktjr960/222600323563)*

[back](./)
