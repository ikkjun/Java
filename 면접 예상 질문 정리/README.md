# Java 면접 예상 질문
## 제너릭 타입
```java
Tv t = new Tv();
```
- Tv t: W(쓰기)
  - Tv에 올 수 있는 타입: Object, Product, Tv
- new Tv(): R(읽기)
  - 사용할 수 있는 생성자 타입: Tv, SmartTv

- 역변(contravariant): 위로 푸는 것 
- 불변(invariant): 참조변수의 타입과 생성자의 타입이 일치하는 것 
- 공변(covariant): 아래로 푸는 것