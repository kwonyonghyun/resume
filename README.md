# <span style="color: #2B5797">권용현 | 백엔드 개발자</span>

## <span style="color: #4B79B7">인적사항</span>
```
생년월일: 1999.05.23  |  이메일: rnjs990523@naver.com 
Blog: https://kwon-record.tistory.com  
GitHub: https://github.com/kwonyonghyun
```

## <span style="color: #4B79B7">소개</span>
사용자 경험 증대를 위한 시스템 성능 최적화에 집중하는 백엔드 개발자 권용현입니다. 탄탄한 기본기와 빠른 학습력을 바탕으로 다양한 기술을 도입해 <strong><u>시스템 성능을 개선</u></strong>했으며, 새로운 기술을 접하면 깊이 있게 습득하여 Spring Security와 Apache Kafka 등의 <strong><u>오픈소스에 기여</u></strong>하며 지속적으로 성장하고 있습니다.

## <span style="color: #4B79B7">보유기술</span> 
Java, Spring, Redis, MySql, Docker, AWS

## <span style="color: #4B79B7">프로젝트</span>

### <span style="color: #6E9BD2">Modulo (2024.11 ~ 현재) </span>
이력서 모듈을 자유롭게 조합하여 맞춤형 이력서를 간편하게 작성할 수 있는 서비스 (https://modulo.co.kr)

주요 성과:
1. **Redis 캐싱을 통한 응답시간 87% 개선**
   - Scale out 상황에서도 데이터를 일관되게 관리
   - Redis Template API와 Lua Script의 특성을 비교하고, 이를 바탕으로 TTL 연장 구현시 Redis Template API 채택

2. **X-Real-IP를 통한 클라이언트 식별 로직 구현**
   - 운영 환경에서 발생하는 예외를 효과적으로 추적하기 위해 HTTP 헤더 관련 지식을 습득하여 체계적인 로깅 시스템 구축
   - X-Real-Ip와 X-Forwarded-For의 특성을 비교하고, 이를 바탕으로 X-Real-Ip 채택
   - 추후 악성 유저를 판별하기 위한 기반 마련

3. **인덱싱을 통한 응답시간 60% 개선**
   - 데이터베이스 최적화 기법을 학습하여 인덱스 설계
   - ManyToOne 관계의 FK 컬럼 인덱싱 적용

4. **Lazy Write을 통한 DAU 측정 시스템 구축**
   - 낙관락, 비관락, Lazy Write을 비교하여 DAU 측정 시 Lazy Write 채택
   - 단일 스레드 비동기 처리로 Write Back 패턴 구현 및 주기적인 스케줄링으로 DB 접근 오버헤드 감소

5. **Fetch Join을 통한 N+1 문제 해결**
   - 쿼리를 분석하여 N+1 문제 발견
   - 연관관계에서 발생하는 N+1 문제 해결하여 쿼리 성능 67.7% 개선

### <span style="color: #6E9BD2">PinUp (2024.08 ~ 2025.03)</span>
친구들과 장소 공유를 할 수 있는 소셜 미디어 서비스

주요 성과:
1. **Redis, Future, Lua Script를 활용한 Cache Stampede 문제 해결**
   - 분산 시스템의 동시성 이슈를 파악하여 Redis pub/sub과 Future 조합으로 Cache Stampede 문제 해결

2. **Redis 캐싱을 통한 응답시간 75.8% 개선**
   - Scale out 상황에서도 데이터를 일관되게 관리
   - Redis Template API와 Lua Script의 특성을 비교하고, 이를 바탕으로 TTL 연장 구현시 Lua Script 채택

## <span style="color: #4B79B7">활동</span>

### <span style="color: #6E9BD2">오픈소스 기여</span>
- **Spring Security**
  - https://github.com/spring-projects/spring-security/pull/15898
- **Spring Kafka**
  - https://github.com/spring-projects/spring-kafka/pull/3550
- **Apache Kafka**
  - https://github.com/apache/kafka/pull/17464

### <span style="color: #6E9BD2">수상이력</span>
- **디지랩 챌린지: 기술로 바꾸는 세상 대상**
- **2024년도 AWS와 함께하는 소중한 상명 해커톤 우수상**

### <span style="color: #6E9BD2">스터디 & 동아리</span>
- **자료구조 스터디 멘토** (인하대학교 컴퓨터공학과 땅울림 주최 | 2025.03 ~ 2025.06)
- **자료구조 스터디 스터디장** (인하대학교 학생회 주최 | 2024.03 ~ 2024.06)
- **스프링 서버 스터디 멘티** (인하대학교 컴퓨터공학과 땅울림 주최 | 2023.07 ~ 2023.09)
- **땅울림 컴퓨터공학과 축구 소모임** (2022.03 ~ 현재)
- **인하대학교 컴퓨터공학과 학생회** (2022.03 ~ 현재)
