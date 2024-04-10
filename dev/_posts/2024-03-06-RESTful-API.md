---
layout: post
title: RESTful API 
description: >
  RESTful API에 대해서 알아보자!!!
sitemap: false
---

- Table of Contents
{:toc .large-only}


## CRUD !!알아야 할 것
- 데이터를 다룰때 큰 틀의 기준이 되는 4가지 요청
- 데이터의 처리 기능
  | CRUD      | 정의                     | Method     |
  |:----------|:------------------------|:-----------|
  | Create    | 리소스 생성                | POST       |
  | Read      | 리소스 조회 및 정보 가져오기   | GET        |
  | Update    | 리소스 수정                | PUT        |
  | Update    | 리소스 부분 수정            | PATCH      |
  | Delete    | 리소스 삭제                | DELETE     |

## API (Application Programming Interface)
- 어플리케이션이 요청과 응답을 주고 받는 체계
- Open API
  - 누구나 쓸 수 있도록 공개된 API
  - e.g. [공공데이터포털](https://www.data.go.kr/), 카카오, 네이버, google, [서울시 Open API](https://data.seoul.go.kr/together/guide/useGuide.do#sample-code-3), [한국투자증권 github](https://github.com/koreainvestment/open-trading-api/tree/main/postman)  

## RESTful API
- REST API (REpresentational State Transfer)
- API를 구현하는 대표적인 방식

## REST 구성 3가지
- 자원 (Resource)
  - 접근할 대상
- 메서드 (Method)
  - GET
  - POST
  - PUT (전체 수정)
  - PATCH (부분 수정)
  - DELETE

  | Method     |
  |:-----------|
  | POST       |
  | GET        |
  | PUT        |

## 호출
- URI (Uniform Resource Identifier)
	- 특정 리소스를 식별하는 통합 자원 식별자를 의미
- URN (Uniform Resource Name)
- URL (Uniform Resource Locator)
	- URI의 하위개념
	- 인터넷에서 웹페이지, 이미지, 비디오 등 리소스의 위치를 가리키는 문자열
	- HTTP 맥락에서 URL은 웹주소 또는 링크

## postman
- API를 디자인, 빌드, 테스트를 반복하기 위한 API 플랫폼






## markdown 글자색 변경
<span style="color:red"> red </span>  
<span style="color:yellow"> yellow </span>  
<span style="color:blue"> blue </span>  
<span style="color:brown"> brown </span>  
<span style="color:orange"> orange </span>  
<span style="color:green"> green </span>  
<span style="color:violet"> violet </span>  
<span style="color:yellowgreen"> yellowgreen </span>  
<span style="color:blueviolet"> blueviolet </span>  
<span style="color:gray"> gray</span>  
<span style="color:indigo"> indigo </span>  

<span style="background-color:#fff5b1"> 노란형광펜 </span>  
<span style="background-color:#FFE6E6"> 빨강형광펜 </span>  
<span style="background-color:#E6E6FA"> 보라형광펜 </span>  
<span style="background-color:#C0FFFF"> 파랑형광펜 </span>  
<span style="background-color:#FFFFF0"> 노란형광펜 </span>  
<span style="background-color:#F5F5F5"> 회색형광펜 </span>  
<span style="background-color:#DCFFE4"> 초록형광펜 </span>  

Name  
: aaa  
: bbb  