교수님 email : leonard.kwak@gmail.com
    이 강의는 Q&A 중심
    매 시간 목차마다 Question 주고 수업 끝나기 전에 Feedback 함.
        1. 디지털 공학 개론이란 무엇인가?
        2. 내가 왜 이 과목을 배워야 하는가?
    주교재 : 처음 만나는 디지털 논리회로(2판), 임석구 외 1인, 한빛아카데미 2024

    Q1: 컴퓨터 하드웨어의 구조와 동작원리
        하드웨어:
    Q2: 기사(deep vs whole)
    Q2: 컴공(소프트웨어 프로그래밍)-> 하드웨어를 잘 알아야 함


    디지털 공학이란? 
    - 하드웨어의 구조와 동작원리를 배움
    - 하드웨어 : CPU RAM Input/Output

    AND, OR, NOT 

    디공을 배우는 내부목표 : 컴공은 하드웨어를 잘 알아야 한다.
    디공을 배우는 외부목표 : 기사 자격증을 따기 위한 관점
                            -자격증 시험에서 디지털 공학의 내용이 어느정도 나올 수 있다. 

    디지털 공학 & 컴퓨터구조 과목과의 관계

    - Digital computer(예전 : 특정 목적의 기능만 수행)
        A general purpose digital system 
        Program 변화에 의한 융통성을 제공 : 폰 노이만 구조
    
    - 복잡도 수준에 따른 digital computer의 구분
        Processor 수준 : CPU, Memory, I/O Processor (High-Level)
        Register 수준: Multiflexer, Decoder, Encoder, Register, Counter
        Gate 수준 : AND, OR, NOT, NAND, NOR
        Device 수준 : Transistor(Low-Level)

    - Digital Computer 설계를 위해서
        - Device 수준의 설계 : 반도체공학
        - Gate, Register 수준의 설계 : 디지털공학
        - Processor 수준의 설계 : 컴퓨터 구조

    진수 변환 기본 : Devide 
    Ex. 10진수 -> 2진수 변환

    10진수 (10)

    ASCII Code (아스키 코드) 1000001(65) - > 'A'
    에러 검출코드 : 홀수, 짝수

    
    불대수

    AND OR NOT 을 이용해 표현 
    F = AB : A=1 AND B=1 일 때, 출력을 1로 만드려는 경우 출력 논리식 (AND)
    F = A + B : A=1 OR B = 1 일 때, 출력을 1로 만드려는 경우 출력 논리식 (OR)
    F = A' : A = 0 일 때, 출력을 1로 만드려는 경우 출력 논리식(NOT)

    - 디지털 회로 - > 불대수 -> 간략화 -> 비용절감

    A + A' = 1 
    0   1
    1   0 
    A   A' = 0
    0   1 
    1   0


    공부에 참고용 블로그 
    https://homubee.tistory.com/27



    조합 논리회로
    - 현재출력= 현재입력
    - 반가산기, 전가산기, 디코더, 멀티플렉서
    - cpu의 alu를 만들 때 사용

    순차 논리회로 
    - 




    플립 플롭 

    - 래치 -> 플립플롭 : 1비트 기억소자


    동기순서논리회로
    - 순서논리 
        현재출력 = 현재입력 + 과거출력
        과거출력 = 메모리 = 플립플롭
        카운터, 레지스터