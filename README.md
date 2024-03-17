<h1>🏭 문구공장 생산관리 MES 웹 프로젝트 </h1>

### 📌 프로젝트 주제  
    "생산관리"에 중점을 두어, 문구 공장의 생산품 관리에 기여하는 웹 어플리케이션을 구현하였습니다.

<br/>

### 📍 목차
1. [제작 기간 · 참여 인원](#제작-기간--참여-인원)
2. [사용 기술](#사용-기술)
3. [역할](#역할)
4. [ERD 설계](#erd-설계)
5. [구현 부분](#구현-부분)
6. [실제 구현 화면](#실제-구현-화면)
7. [성과 · 결과](#성과-·-결과)

---

</br>

## 1. 제작 기간 · 참여 인원
- 2023.01.03 ~ 2023.01.20
- 팀 프로젝트 (10명)

</br>

## 2. 사용 기술
#### <span style='background-color:#fff5b1'>Back-End</span>
- Language&nbsp;&nbsp;  | JAVA 11
- Framework | Spring Boot 2.7.5, MyBatis, JPA
- DB &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | MySQL

#### <span style='background-color:#f6f8fa'>Front-End</span>
- HTML5
- CSS3
- JavaScript
- Thymeleaf

#### <span style='background-color:#f6f8fa'>Tools</span>
- STS 3.9.14
- MySQL WorkBench 8.0
- Git, GitHub
- Notion

</br>

## 3. 역할
- 화면 기획
- ERD 설계
- 생산실적 관리 구현

</br>

## 4. ERD 설계
- 프로젝트 전체 ERD
![image](https://github.com/bono039/munguFactory/assets/67899934/9ebde328-50fd-48a6-8cee-4ee1b2f5aa3a)

 

</br>

## 5. 구현 부분
### **생산실적 관리 기능**
- **생산실적 목록** - 작업일시 기준 내림차순 정렬. 생산번호 클릭 시 상세 정보 확인 가능.
- **생산실적 등록**
- **생산실적 조회**&nbsp; - 원하는 조건(품번/품명/사원번호/공장코드)으로 검색 가능.
- **생산실적 수정/삭제**

</br>

## 6. 실제 구현 화면
- 생산실적 리스트
![image](https://github.com/bono039/munguFactory/assets/67899934/0039619b-dfe5-4815-8e0e-58214dddfae0)


</br>

- 생산실적 상세 정보
![image](https://github.com/bono039/munguFactory/assets/67899934/3beff938-cc6c-4a71-9922-0ae57c58ed69)


</br>

- 등록된 생산실적 수정 결과
![image](https://github.com/bono039/munguFactory/assets/67899934/b09f54ca-f2c0-4051-8b04-f4c8c4ab95f9)


</br>

## 7. 성과 · 결과
- MyBatis와 JPA를 함께 사용하여 목적에 따라 각각의 장점을 활용했습니다.
- JPA를 사용하여 간단한 CRUD 작업을 효율적으로 구현하고, 코드 중복성과 가독성, 유지보수성을 향상시켰습니다.
- MySQL을 이용하여 시퀀스 생성 및 페이징 처리 방법을 습득하였습니다.
- Ajax를 활용한 비동기 데이터 처리 방식에 대한 이해를 높였습니다.
