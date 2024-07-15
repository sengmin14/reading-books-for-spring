# 스프링 부트 3로 백엔드 입문하기
<img src="https://github.com/user-attachments/assets/2ade74f0-c506-4198-882a-5d6a5376f9f4" alt="image" width="400"/>

<br>

## 배우는 기술

- FrontEnd
  - 템플릿 엔진
  - thymeleaf
  - javascript
  - html

- BackEnd
  - `SpringBoot`
    - Spring
    - IoC
    - Bean
  - `Spring Security`
    - Stateful Server  
    - Authentication
    - Authorization
    - Spring Security
      - 세션 기반 인증 방식
  - `JPA`
    - ORM
    - Hibernate
    - Spring Data Jpa
  - `OAuth2.0`
    - 용어
      - 리소스 오너
        - 리소스 오너 정보를 가지고 오는 4가지 방법
          - authorization code grant type : 권한 부여 코드 승인 타입(중요, 채택)
            - 권한요청
              - client_id
              - redirect_uri
              - response_type
              - scope
            - 데이터 접근용 권한 부여
              - 최초 1회
            - 인증코드 제공
            - 액세스 토큰 응답
              - client_secret
              - grant_type
            - 액세스 토큰으로 API 응답 & 반환
          - client credentials grant : 클라이언트 자격증명 승인 타입(중요)
          - implicit grant type : 암시적 승인 타입
          - resource owner password credentials : 리소스 소유자 암호 자격증명 승인 타입
      - 리소스 서버
      - 인증 서버
      - 클라이언트 애플리케이션
    - Cookie
      - 액세스 토큰
  - `JWT`
    - Stateless Server
    - 토큰 기반 인증 방식
    - Filter
    - SecurityContext
      - Thread Local 
      - SecurityContestHolder
    - Refresh Token
  - `JUnit Test`
    - AssertJ
    - Assertion
  - AWS
  - 깃허브 액션을 통한 CI/CD


#### 출처 및 참고

[신선영 백엔드 개발자님의 스프링부트 3 백엔드 개발자 되기 자바편](https://github.com/shinsunyoung/springboot-developer)

[신선영 개발자님 소스코드](https://github.com/shinsunyoung/springboot-developer) 
