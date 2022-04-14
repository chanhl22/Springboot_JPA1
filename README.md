# JPASHOP
> [정리 바로가기](https://near-apparatus-275.notion.site/JPA-1-4f6376b167914c5aa49d44e873dbb3bc)

## Description
스프링 부트와 JPA를 사용해서 개발한 쇼핑몰 웹 애플리케이션 설계하고 개발하기

## Project Goal
Spring Data JPA를 좀 더 깊이 이해하고 사용할 수 있도록 JPA에 익숙해지기 위한 프로젝트

## 기능
* 회원 가입, 회원 목록 조회
* 상품 등록, 상품 목록 조회
* 상품 수정
* 상품 주문, 주문 내역 조회
* 주문 목록 검색, 취소

## Tech Stack
java, SpringBoot, JPA, H2, Thymeleaf

## Overview
* ##### 홈
  * 메인 화면
    ![image](https://user-images.githubusercontent.com/77683221/163298636-2b550d9a-9ff9-42b6-b462-5301b61b9521.png)
* ##### 회원 기능
  * 회원 가입
    ![image](https://user-images.githubusercontent.com/77683221/163298354-38b86683-e602-423b-ac7c-3d9be935bc5e.png)
  * 회원 목록 조회
    ![image](https://user-images.githubusercontent.com/77683221/163298467-3bcf3231-ea78-438e-9e17-a9fccc227d33.png)
* ##### 상품 기능
  * 상품 등록
    ![image](https://user-images.githubusercontent.com/77683221/163298796-03daf54e-52fa-4af7-ae63-5ea7c89d21e8.png)
  * 상품 조회
    ![image](https://user-images.githubusercontent.com/77683221/163298885-d134e9b8-e348-46e3-8631-1b75533c48d6.png)
* ##### 주문 기능
  * 주문 등록
    ![image](https://user-images.githubusercontent.com/77683221/163298961-b41ef2cb-0839-4a9b-aec1-e432eb0d979f.png)
    ![image](https://user-images.githubusercontent.com/77683221/163299012-98d5cd47-1786-4c19-a567-3381be021474.png)
  * 주문 조회
    ![image](https://user-images.githubusercontent.com/77683221/163299101-f5dd882b-8edd-416e-95a6-edf529fab17b.png)


## 추후 업데이트 필요
* set 제거
* 엔티티 반환 제거 -> DTO or 폼 객체
* Movie, Album 추가
* 다양한 상품 받는 기능 추가
* 주문 결과 페이지 추가