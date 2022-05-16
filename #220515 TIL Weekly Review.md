# #220515 TIL

Git: No
분야: TIL
작성일시: May 15, 2022 6:47 PM
📌 주간 회고: https://www.notion.so/b0007a0cd7294b139b84ec8cd19ddb95

# #220515 TIL

22.05.09~22.05.14

## ****✅오늘 한 일****

- [x]  어제 review
- [x]  보충학습

앞선 모든 코스에서 **당일 해결되지 않은 부분을 모아 학습**하는 시간입니다. 

매일 TIL에 작성했던 **질문을 카테고리별**로 모읍니다. 

관련 링크를 학습하고, 어떤 개념을 몰라 어려움을 겪었는지 최대한 기록합니다. 

추가 학습이 필요한 부분이 생기면 과목을 새로 개설하거나, 여유시간 학습을 위해 클리핑합니다. 

## 💌Details⭕❌

---

### ⭕Review

[https://www.notion.so/370be7b7bc5a4d7ca5527b9ee04e44a1?v=c0615eeb50094875a3bc9e7c1902eded](https://www.notion.so/370be7b7bc5a4d7ca5527b9ee04e44a1)

![Untitled](#220515%20TIL%2047adf959c4694e8b86de0228cb8146cb/Untitled.png)

월요일에 자료 정리하고 시간 흐를수록 클리핑 양이 줄어드는 게 보인다.. 목요일까지 반짝 학습하고 금토일 암전 무슨일이죠?

결국 같은 질문의 반복처럼 보인다. 상위개념이 무엇인지를 모르니 계속 파편적인 질문이 나오는 것 같다. 

### ⭕이번 주의 보충학습

- **🔑 기나긴 탐색과정...**
    - stream()에서 other jobs 비교하는 부분 람다식
        - 람다식이란?
    - break는 if else 대신 간략히 하는 용도로 쓴다.
        - break를 쓰는 이유
    
    ❓서비스에서 public void로 선언해줬는데 왜 컨트롤러에서는 public String일까?
    
    ❓**`java: incompatible types`** deleteAllById를 썼는데 deleteById를 써야 하는 자리였다고 한다. 둘의 차이는?
    
    🐱**생각의 흐름**
    
    ### G) difference btw delteallby id deletebyid
    
    R)
    
    [deleteById vs delete in spring jpa](https://stackoverflow.com/questions/56065583/deletebyid-vs-delete-in-spring-jpa)
    
    JPA에 대한 언급이 나온다. JPA가 무슨 역할인지 모르니 더욱 알 수가 없다. 난 delete메서드가 있는지도 몰랐고, deletebyid를 원하는 게 아닌데.... 흠
    
    그래서 정확히 레파지토리가 뭘까?
    
    ## what is ‘JPA Repository’?
    
    **연관질문**
    
    ### **What is difference between CrudRepository and JpaRepository?**
    
    → CrudRepository and JPA repository both are the **interface of the spring data repository library.**
    
    [Difference Between CrudRepository and JPARepository in Java](https://www.tutorialspoint.com/difference-between-crudrepository-and-jparepository-in-java)
    
    내가 알기로 인터페이스라는 건...(모름)
    
    ### Spring Data JPA
    
    [Spring Data JPA - save(), findById(), findAll(), deleteById() Example](https://www.javaguides.net/2019/07/spring-data-jpa-save-findbyid-findall-deletebyid-example.html)
    
    JPA 튜토리얼인데 여전히 무슨 소린지 모르겠다. 
    
    adds extra layer of abstraction이라는데 뭔소리지 싶어서
    
    ### G) JPA구조 검색
    
    R)
    
    [Spring Data JPA 1. 상속구조와 주요 인터페이스](https://100100e.tistory.com/348)
    
    JPA는 제일 하단에서 영속화에 특화되어 있다고 한다. 영속화가 뭐예요..
    
    ### G) 영속성
    
    R) 
    
    ![Untitled](#220515%20TIL%2047adf959c4694e8b86de0228cb8146cb/Untitled%201.png)
    
    [영속성(Persistence)이란?](https://sugerent.tistory.com/587)
    
    DTO랑 DAO랑 비슷한 거 아녔냐,,, 저 그림이 이해가 잘 될 거란ㄴ데 여전히 뭔소린지 모르겠다..
    
    두번째로는 
    
    김영한 강사 요약글이 나옴
    
    [[JPA/김영한] JPA를 쓰는 이유와 JPA 소개](https://velog.io/@sooyoungh/JPA%EB%A5%BC-%EC%93%B0%EB%8A%94-%EC%9D%B4%EC%9C%A0%EC%99%80-JPA-%EC%86%8C%EA%B0%9C)
    
    그래도 대체 뭔소린지 모르겠어서 첫 글부터 정독
    
    JPA의 필요부터 설명해준다. 
    
    그러고보니 SQL의 한계로 JPA가 생겼다는 말을 들은 것 같다. RDB에 객체를 저장하는 게 힘들었다고....
    
    한마디로 JPA는 **자바 어플리케이션에서 관계형 데이터베이스를 사용하는 방식을 정의한 인터페이스**
    
    ## what is ‘Repository’?
    
    엔티티, 레파지토리 설명이 나와있다. 
    
    레파지토리는 DB접근 메서드를 쓰기 위한 인터페이스 
    
    사용방식을 정의한 인터페이스라는 게 이런 말인 건가 
    
    엔티티를 선언해 데이터베이스 구조를 만들었다면 기본적인 CRUD를 위해 레파지토리가 필요하다. 그중에 하나가 JPA인 거고...
    
    데이터 구조라는 표현이 뭔가 더 큰그림으로 가는 키워드인 것 같아서 repository 구조를 검색해봤다. 
    
    [스프링 부트 : 기본 개념 1) Entity, Repository 개념](https://whitepro.tistory.com/265)
    
    **Repository 구조**
    
    역시나 MVC패턴 얘기가 나온다
    
    안그래도 평소에 헷갈렸던 DTO,DAO, Domain 얘기가 나오는데 간단히 생각하면 레파지토리는 DAO랑 유사한 것으로 영구저장소(MySQL, Oracle 등)에 접근할 때 로직이랑  API 사이의 돼지코 같은 기능이라고 한다. 로직이 뭔데요,,,,, 
    
    그러고 보면 아까 위에서도 RDBS는 데이터 중심인데, 객체는 관계 중심?이라서 아다리가 안 맞는다고 했다.  참고로 JPA는 객체의 상태를 관리하는 거지 영구저장소가 아니다. 
    
    도메인은 예를 들어 쇼핑몰이 하나의 도메인이 될 수도 있고, 도메인 하위구조로 관리자, 멤버 도메인을 나눌 수 있다고 한다. 
    
    [VO vs DTO, DAO vs Repository, 그리고 Domain과 프로젝트 구조](https://xengom.com/spring/vo-dto-dao-repository-domain/)
    
    [[4] 스프링 부트와 JPA 활용 (3) - 아키텍처 구조 / Service, Repository 개발](https://velog.io/@neity16/4-%EC%8A%A4%ED%94%84%EB%A7%81-%EB%B6%80%ED%8A%B8%EC%99%80-JPA-%ED%99%9C%EC%9A%A9-3-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98-%EA%B5%AC%EC%A1%B0-Service-Repository-%EA%B0%9C%EB%B0%9C)
    
    이쯤에서 다시 JPA 강의 정리가 나온다. 아키텍처 구조라고 하는데, 왜 여기는 M이 없을까? MVC패턴과 아키텍처 구조는 어떻게 다른 걸까?
    
    ![Untitled](#220515%20TIL%2047adf959c4694e8b86de0228cb8146cb/Untitled%202.png)
    
    **MVC pattern**
    
    [](https://www.baeldung.com/spring-mvc-and-the-modelattribute-annotation)
    
    repository가 mvc패턴에서 무슨 역할을 하는지 알려준다. 
    
    [Controller, Service, Repository 가 무엇일까?](https://velog.io/@jybin96/Controller-Service-Repository-%EA%B0%80-%EB%AC%B4%EC%97%87%EC%9D%BC%EA%B9%8C)
    
    MVC 패턴을 얘기할 때는 자꾸 JSP가 언급된다. 
    
    [MVC(Model, View, Controller) Pattern](https://junhyunny.github.io/information/design-pattern/mvc-pattern/)
    
    [MVC는 알겠는데 Service와 DAO는 뭘까?](https://www.kurien.net/post/view/24)
    
    - 이건 JSP로 구현하는 것 같은데 완전히 똑같지는 않다. 굳이 따지자면 내 케이스는 어노테이션으로 주입받는 ? 것? 같다
    
    [01.Model Object을 파라미터로 받는 예제](http://wiki.gurubee.net/pages/viewpage.action?pageId=10453040)
    
    - 내가 알기로는 파라미터는 변수인데, 변수를 어떤 객체로 가져오는 게 신기하다.
        
        [매개변수 (컴퓨터 프로그래밍) - 위키백과, 우리 모두의 백과사전](https://ko.wikipedia.org/wiki/%EB%A7%A4%EA%B0%9C%EB%B3%80%EC%88%98_(%EC%BB%B4%ED%93%A8%ED%84%B0_%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D))
        
    - 변수의 자료형 정도만 설정하는 건 줄 알았는데, 객체를 변수로도 쓸 수 있다니!
    - 
    
    **큐와 리스트의 관계**
    
    1. [https://lee-mandu.tistory.com/462](https://lee-mandu.tistory.com/462)
    2. 큐는 말 그대로 어떤 기능을 하는 구조일 뿐이고, 구현을 arraylist라는 기능을 통해 하는 거다. 마치 스케줄러라는 기능을 만들기 위해 내가 노션을 쓰든 종이 다이어리를 쓰든 그 템플릿과 기능만 하면 되는 것처럼
    
    [[자료구조] 큐 - 설명 및 자바 구현](https://youtu.be/udEQK435mWM)
    
    [[자료구조] Java Queue 구현 / 자바 큐 구현](https://dev-whoan.xyz/24)
    
    ❓리스트로 돌아가는 건 단순히 리스트 html을 보여줘! 가 아니라 redirect를 쓰게 된다. 
    
    `**return "redirect:/board/list";**`
    

### 🚩내 언어로 다시 정리해보기

1. **큐와 리스트의 관계**
    
    큐는 추상적인 어떤 기능을 의미하는 것 같다.
    
    프린터라는 기능을 구현하기 위해서 arraylist라는 걸 쓸 수 있다는 말이다.
    
    arraylist는 이미 있는 기능이고, 그 기능을 조합해 큐를 만드는 것 같다.
    
    예를 들어 내가 10분 단위 시간기록을 하고 싶을 때, 그 툴은 노션이든 종이 플래너이든 상관없는 것처럼, 큐의 기능을 하는 게 실물 프린터일 수도, 소프트웨어일 수도 있는 거다. 
    
2. **Model을 파라미터로 갖는 메서드**
    
    우선 파라미터라는 건 매개변수이다. 
    
    일반적으로 변수 자료형을 선언할 때 쓰던 변수(variables)의 한 종류라고 보면 된다. 
    
    ```java
    @GetMapping("/board/list")
    public String boardList(Model model){//보드리스트 url로 가면 Model을 통해서 보드서비스의 보드리스트를 받아올 건데 그 이름을 "리스트"
        model.addAttribute("list",boardService.boardList());
        return "boardlist";//html 보드리스트 보여줘
    }//아직 뭐가 객체고 뭐가 메소든지 좀 헷갈린다...(220507)
    ```
    
    ![Untitled](#220515%20TIL%2047adf959c4694e8b86de0228cb8146cb/Untitled%203.png)
    
    이때 Model은 인터페이스이다..... 여기까지만 이해했다 3주째 헤매고 있는 중,,
    
3. **MVC pattern이란? repository의 필요성**
효율적으로 소프트웨어를 관리하기 위한 디자인을 의미한다. 스터디그룹을 만든다고 했을 때 효율적인 관리를 위해 팀장을 뽑고, 그 팀장의 팀장이 있고... 이런 식으로 구조를 만드는 걸 design pattern이라고 이해하면 될 것 같다.  Model, Controller, View 파트를 나누어서 분업을 시킨다. 이렇게 분업하면 규모가 커져도 관리가 쉬워진다. 
한편, repository라는 건 데이터에 접근할 때 CRUD 기능 등을 수행하기 쉽게 만들어주는 것이다. 원래 Model이 DB접근, 관리, 처리까지 다 했는데 스프링에서는 service, DAO, repository를 통해 모델의 기능도 분업해준다. 
더 자세한 정리는 블로그에!  [https://kindspoon.tistory.com/41](https://kindspoon.tistory.com/41)

### ⭕일간회고 summary

**KEEP🚩**

- 일주일의 학습내용을 잘 정리했다

**Problem🚨**

- 우선순위를 자주 잊어버린다.
- 여러가지를 챙기려다보니 부담감이 크다.

**Try🌱**

- 딥워크를 항상 챙기자