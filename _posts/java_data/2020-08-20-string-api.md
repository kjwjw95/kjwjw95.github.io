---
layout: post
title: Java String 관련 Method
subtitle: 계속 update중(마지막 update 20.08.21)
categories: [java_data]
tags: [자바,java,string]
comments: true
---

이번 포스트는 자바에서 string에 관련된 method들을 모두 정리 하겠습니다.

* length()
  - 설명 : string의 길이를 반환하는 메소드.
  - 리턴값 : string의 길이를 int로 리턴.
  - 예시
  
  ```java
	test="abcd";
	System.out.println("test의 길이는 "+test.length());
  ```
  output : test의 길이는 4

* isEmpty()
  - 설명 : string의 길이가 0인지(비어 있는지) 확인하는 메소드.
  - 리턴값 : boolean으로 string의 길이가 0이라면 true를, 0이 아니라면 false를 리턴.
  - 예시
  
  ```java
	test="";
		if(test.isEmpty())
			System.out.println("test가 비어있습니까? 답 : "+test.isEmpty());
  ```
  output : test가 비어있습니까? 답 : true
  
* charAt(int index)
  - 설명 : index번째의 문자를 리턴하는 메소드. index의 범위는 0~length()-1 까지다.
  - 리턴값 : string의 길이를 int로 리턴.
  - 예시
  
  ```java
	test="abcd";
	System.out.println("test의 길이는 "+test.length());
  ```
  output : test의 길이는 4