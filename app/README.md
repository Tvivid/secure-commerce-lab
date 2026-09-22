# secure-commerce

## 사용 기술

- Java 21
- Spring Boot 3.5.16
- Maven
- Spring Web, Spring Data JPA, Validation, MySQL Driver, Lombok

## 실행 방법

```bash
./mvnw spring-boot:run
```

Windows PowerShell에서는 `.\mvnw.cmd spring-boot:run`을 실행한다.

## 테스트 방법

```bash
./mvnw test
```

Windows PowerShell에서는 `.\mvnw.cmd test`를 실행한다.

## 현재 구현 상태

Day 2 초기 애플리케이션으로, 애플리케이션 뼈대와 `GET /api/health`만 구현되어 있다. 데이터베이스 연결은 아직 비활성화되어 있다.
