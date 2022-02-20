## Hyuko의 Spring boot 공부 노트 블로그

[hyuko12 GitHub](https://github.com/hyuk12) 



### JPA 영속성 컨테스트

JPA에서 가장 중요한 2가지  
1. 객체와 관계형 데이터 베이스 매핑하기(정적)  
2. 영속성 컨텍스트  
    - 엔티티를 영구 저장하는 환경이라는 뜻
    - EntityManger.persist(entity): ->  
    엔티티를 영속성 컨텍스트라는 곳에 저장을 한다.  

- 영속성 컨텍스트는 논리적인 개념이다.  
  
  
```markdown
    영속성 컨텍스트의 종류

    - 영속(managed)
        - 영속성 컨텍스트에 관리되는 상태
        - 매니저 안에 객체를 넣었을 때
    
    - 비영속(new/transient)
        - 영속성 컨텍스트와 전혀 관계가 없는 새로운 상태
        - 사용할 객체만 생성한 단계
```


