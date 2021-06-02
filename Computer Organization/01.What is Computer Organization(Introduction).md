## What is Computer Organization ( Introduction )

### :one: Organization of a Computer

##### 컴퓨터의 전형적인 다섯 가지 구성 요소 - 입력(Input) / 출력(Output) / 메모리(Memory) / 데이터 경로(Data Path) / 제어(Control)
##### Data Path + Control = Processor ( CPU )

![image](https://user-images.githubusercontent.com/52204522/120496989-013d4e00-c3f9-11eb-8d12-0cd4daed2c6a.png)

### :two: Introduction Set Architecture

![image](https://user-images.githubusercontent.com/52204522/120498999-a9074b80-c3fa-11eb-8609-760a39895d3e.png)

##### Introduction Set Architecture가 소프트웨어와 하드웨어 사이를 연결해주는 인터페이스 역할을 함.

##### 즉, ISA는 소프트웨어와 하드웨어 사이의 약속이다. ISA는 여러 명령어들을 정의하며 현재 시스템의 상태가 어떻게 구성되어 있는지, 명령어를 실행할 때 그 상태가 어떻게 바뀌는지에 대해 정의하는 것임.
##### 따라서 이 덕분에 프로그래머는 ISA를 통해 작성한 프로그램이 컴퓨터에서 어떻게 실행될 것인지 알 수 있고, 하드웨어 설계자는 어떤 명령이 수행 되었을 때 하드웨어가 어떻게 수행되도록 설계해야 하는 지에 대한 명세서 역할을 수행함.
##### 즉, 프로그래머 입장에서의 인터페이스, 하드웨서 설계자 입장에서의 하드웨어 구현을 '분리' 할 수 있음.

##### AMD사의 프로세서와 Intel사의 프로세서에서 소프트웨어들이 프로세서 구분 없이 잘 작동하는 이유는 공통의 Instruction Set이 있고, 하드웨어 각 회사가 다르게 구현하기 때문이다.
##### 프로세서 하드웨어의 구현에 있어 더 싸고, 더 빠르도록 제작하거나 Instruction Set에 다른 명령어들을 추가할 수 있지만, Core Introduction Set을 바꿀 경우 기존에 동작하던 소프트웨어들이 동작하지 않을 수 있기 때문에 Core Introduction Set은 건드리지 않음.

#### ISA는 다음과 같은 항목들을 포함 한다.
##### - Organization of storage ( 저장 공간이 얼마나 있고 어떻게 구성되어 있는가 )
##### - Data types ( 이 장치가 어떤 데이터 타입들을 제공하고 있는가 )
##### - Encoding and representing introductions ( 명령어들을 어떻게 암호화 하고 표현하는가 )
##### - Introduction Set (or opcodes) ( 어떤 명령어 집합 또는 명령어 종류를 가지고 있는가 )
##### - Modes of addressing data items / introductions ( 어떻게 데이터 혹은 명령어들을 지정하는가 )
##### - Program visible exception handling ( 어떤 예외 처리가 프로그램에 시각적으로 표시되는가 )

### :three: Case Study : MIPS ISA

![image](https://user-images.githubusercontent.com/52204522/120517102-0905ee00-c40b-11eb-97b9-395cea48c69b.png)

#### 참고

#### [CS-224 Computer Organization Lecture 01](https://www.youtube.com/watch?v=CDO28Esqmcg)
#### [나무위키 - 명령어 집합](https://namu.wiki/w/%EB%AA%85%EB%A0%B9%EC%96%B4%20%EC%A7%91%ED%95%A9)


