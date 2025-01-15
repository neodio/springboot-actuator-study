# 스프링 부트 - 핵심 원리와 활용

인프런 스프링 부트 - 핵심 원리와 활용 스터디

강의 학습 내용 학습 자료 - actuator

https://www.inflearn.com/course/%EC%8A%A4%ED%94%84%EB%A7%81%EB%B6%80%ED%8A%B8-%ED%95%B5%EC%8B%AC%EC%9B%90%EB%A6%AC-%ED%99%9C%EC%9A%A9

# 실행환경
- java 17
- Gradle 7.6
- Springboot 3.0.2

### actuator 전체 엔드포인트
 - http://localhost:8080/actuator

### actuator 헬스체크 엔드포인트
 - http://localhost:8080/actuator/health

### actuator 어플리케이션 정보 엔드포인트
 - http://localhost:8080/actuator/info

### actuator 로거 엔드포인트
 - http://localhost:8080/actuator/loggers

### actuator 셧다운 엔드포인트
 - (POST) http://localhost:8080/actuator/shutdown

### Local prometheus, grafana 실행
- 실행방법
  ```
  $ cd docker-prometheus && docker-compose up -d
  ```
- 도커 종료방법
  ```
  $ cd docker-prometheus && docker-compose down -v
  ```

### prometheus
local: http://localhost:9090
![prometheus.png](image%2Fprometheus.png)

### grafana
local: http://localhost:3000
![grafana.png](image%2Fgrafana.png)