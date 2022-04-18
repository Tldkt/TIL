# 출력

강의: 코딩테스트
문제번호: 2557
작성자: 익명
플랫폼: 백준

### 정답

```java
class Main{ 
    public static void main(String[] args){ 
        System.out.println("Hello World!"); 
    } 
}
```

백준에서는 main.java에서 컴파일하므로 클래스를 메인으로 설정해줘야 함

틀렸던 이유

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, world!");
    }
}
```

클래스 이름을 헬로월드로 맘대로 설정해서!