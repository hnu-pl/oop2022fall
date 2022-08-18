# OOP course @ HNU CE undergrad
Object-Oriented Programming course @ HNU CE undergrad

2022년 2학기 한남대학교 컴퓨터공학과 객체지향프로그래밍 과목 홈페이지입니다.

## Textbooks
### 이번 수업 교재
* [처음 해보는 자바 프로그래밍](https://www.rubypaper.co.kr/entry/%EC%B2%98%EC%9D%8C-%ED%95%B4%EB%B3%B4%EB%8A%94-%EC%9E%90%EB%B0%94-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D), 오정임 지음, 루비페이퍼
* [코틀린으로 배우는 함수형 프로그래밍](https://blog.insightbook.co.kr/2019/12/12/%EC%BD%94%ED%8B%80%EB%A6%B0%EC%9C%BC%EB%A1%9C-%EB%B0%B0%EC%9A%B0%EB%8A%94-%ED%95%A8%EC%88%98%ED%98%95-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D/), 조재용 우명인 지음, 인사이트

너무 한 교재로만 오래 강의하면 매너리즘에 빠질 수 있기도 하고 변화를 주기 위해 조금은 실험적으로 교재를 바꿔보았다.

자바 교재는 어떻게 보면 요즘 기준으론 조금 올드한 스타일이다.
그러니까 핵심 아이디어 위주로 정리하고 자세한 것은 인터넷으로 찾아보도록 두께를 좀 가볍게 가져가는 방식이 어찌 보면 입문서로는 요즘 스타일인데,
이 책은 상당히 자세한 부분까지 작성해 놓아 두껍고 요즘 스타일 입문서에 비해서 한눈에 확 들어오는 다자인은 아니다.
대신에 인터넷 창을 열어보지 않아도 대부분의 내용을 찾아볼 수 있고 한 단계 한 단계 그대로 따라하면서 그 결과가 어떻게 되는지까지 그림으로 굉장히 친절하고 자세하게 설명한다는 장점이 있다.
코틀린 책은 입문서가 아니라서 사실 강의에서 이 책 내용의 1/4정도 다룰까말까 싶어서 그런 점에서 보면 교재라고 하기에는 조금 부적합한 측면도 있다.
하지만 수업에서 직접 다루거나 하지는 못하더라도 국내 현업 개발자들이 이러한 내용에 높은 관심을 갖고 계속해서 공부해 나가면서 책까지 쓴다는 것을 접하는 것 자체도 의미가 있을 수 있다는 생각에 선정하였다. 오히려 코틀린에 대해 전혀 모르는 상태라면 아래의 이전 수업 교재와 같은 책을 참고하는 것도 좋다.

두 책 모두 객체지향이나 함수형 프로그래밍 패러다임에 대해서 역사적 맥락이나 학문적 의미를 개념적으로 깔끔하게 정리해서 전달하는 목적의 책은 아니다. 특히 함수형 프로그래밍에 대한 설명들에서는 더욱 그러하다. 자바나 코틀린을 사용하는 입장에서 함수형 프로그래밍을 어떻게 바로 코드에 적용해 볼 수 있는지를 중점으로 이야기하고 있다는 점에 유의할 필요가 있다.

### 이전 수업 교재
* [Do it! 자바 프로그래밍 입문](http://www.easyspub.co.kr/20_Menu/BookView/267), 박은종 지음, 이지스퍼블리싱
  - 출판사 유투브 채널에 올라온 [저자직강 동영상 재생목록](https://www.youtube.com/playlist?list=PLG7te9eYUi7typZrH4fqXvs4E22ZFn1Nj)
* [Do it! 코틀린 프로그래밍](http://www.easyspub.co.kr/20_Menu/BookView/312), 황영덕 지음, 이지스퍼블리싱
  - 출판사 유투브 채널에 링크된 [저자직강 동영상 재생목록](https://www.youtube.com/playlist?list=PLccJpFPBw-NxL6agtfLvjtX8ohcZqDc17)

참고로, Do it! 자바 책에서 개념적으로 바람직하지 않은 표현
두잇 자바 책에서 좀 개념적으로 바람직하지 않은 표현

어떤 클래스를 생성한다 (x) <=== 이런 표현을 반복적으로 쓰고 있음

어떤 클래스의 인스턴스를 생성한다 (o)

어떤 클래스의 오브젝트를 생성한다 (o)

## Programming languages and related tools for course activities
 * [Java](https://www.oracle.com/kr/java/)
   with [Jupyter notebook](https://jupyter.org/)
   using the [java-notebook](https://github.com/jbindinga/java-notebook) Docker image
   running [IJava](https://github.com/SpencerPark/IJava) kernel
   based on [JShell](https://docs.oracle.com/javase/9/jshell/introduction-jshell.htm)
* [Kotlin](https://kotlinlang.org/)
   with [JetBrains Datalore](https://datalore.jetbrains.com/)

## Links

### Docker and WSL2
* [Docker가 뭐고 왜 쓰는건가요?](https://youtu.be/tPjpcsgxgWc) -- *얄팍한 코딩사전* on YouTube
* [WSL 2: Getting started](https://youtu.be/_fntjriRe48) -- *David Bombal* on YouTube
* [WSL 2 with Docker getting started](https://youtu.be/5RQbdMn04Oc) -- *David Bombal* on YouTube
* [WSL 2(Windows Subsystem For Linux 2) 정식 버전 사용하기](https://www.lesstif.com/software-architect/wsl-2-windows-subsystem-for-linux-2-89555812.html)
    - 윈도우 개발자 프로그램(베타 버전 체험)이 아니라 최신 정식 출시 버전(Windows 10 버전 2004) 기준으로 WSL2 설치를 자세하게 주의사항 포함 정리가 잘 되어 있다. Windows 11에서도 설치 방법은 대략 방법은 비슷하다.

### on Programming paradigms
* [함수형 프로그래밍이 뭔가요?](https://youtu.be/jVG5jvOzu9Y) -- *얄팍한 코딩사전* on YouTube
* [객체지향 디자인패턴 1](https://youtu.be/lJES5TQTTWE) -- *얄팍한 코딩사전* on YouTube
* [객체지향 디자인패턴 2](https://youtu.be/q3_WXP9pPUQ) -- *얄팍한 코딩사전* on YouTube
* [Why Isn't Functional Programming the Norm? – Richard Feldman](https://youtu.be/QyJZzq0v7Z4) -- Elm 언어 핵심 개발자인 Richard Feldman의 Clojoure 2019 컨퍼런스 강연. 제목에서 주는 인상과는 달리 함수형 프로그래밍보다 OOP, OOPL 관련 내용에 대한 이야기가 더 많다.

