### Hello, I'm Dongmin Cha

Backend Developer who values efficiency and practicality, striving for automation and optimization

at [GenesisNest ](https://genesisnest.com/) 😃

<img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExcDl1a3h5OTZqZDNsN2NhZ2EzcXRrc29hazhqM3k0cTc1bHl1Y2lwZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/13HgwGsXF0aiGY/giphy.gif" width="300"> 


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=chadongmin&langs_count=8&layout=compact&include_orgs=true&theme=transparent&hide_border=true)](https://github.com/anuraghazra/github-readme-stats)
---
### Opensource Contribution

**assertj/assertj-core**

Handle non-existent field check in recursive comparison containers - [PR](https://github.com/assertj/assertj-core/pull/3857)
- `usingRecursiveComparison`에서 `List`, `Optional` 등 컨테이너 내부의 존재하지 않는 필드를 검사할 때, 예외를 발생시키지 않고 통과하던 문제를 해결. 검증 로직이 컨테이너 내부 요소까지 필드 존재 여부를 확인하도록 수정

**openfeign/querydsl**

[[QueryDSL 6.12 Released]](https://github.com/OpenFeign/querydsl/releases/tag/6.12) Fix: Improve handling of contains() on JPA collections mapped with @Converter to basic types - [PR](https://github.com/OpenFeign/querydsl/pull/1199)  
- Hibernate의 JPQL 검증이 강화되면서 런타임 예외를 유발하던, @Converter 적용 컬렉션의 부적합한 JPQL 생성 문제를 JPQLSerializer에 사전 검증 로직을 추가하여 해결 (JPQLSerializer가 'MEMBER OF' 절을 생성하기 전에 사전 검증하여 명시적인 예외를 발생시키도록 수정)
 
[[QueryDSL 6.12 Released]](https://github.com/OpenFeign/querydsl/releases/tag/6.12) Add TypeWrapperFactoryExpression for Type-Safe Custom Number Mapping in Querydsl Aggregations - [PR](https://github.com/OpenFeign/querydsl/pull/1181)  
- querydsl-core에 TypeWrapper 클래스를 추가하여, sumAggregate() 등 집계 함수의 결과를 Money와 같은 커스텀 Number 타입으로 변환할 수 있는 기능 제공

[[QueryDSL 6.11 Released]](https://github.com/OpenFeign/querydsl/releases/tag/6.11) Fix Enum Serialization in CaseBuilder for Hibernate Compatibility - [PR](https://github.com/OpenFeign/querydsl/pull/966)  
- CaseBuilder의 Enum 직렬화 방식을 수정하여 Hibernate 매핑 오류 해결
